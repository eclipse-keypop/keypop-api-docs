# Keypop API Documentation

[![License](https://img.shields.io/badge/License-EPL_2.0-blue.svg)](https://www.eclipse.org/legal/epl-2.0/)

Central repository for API documentation of all Eclipse Keypop libraries, including both Java (Javadoc) and C++ (Doxygen) references.

## Overview

This repository aggregates documentation from all Keypop libraries using Git submodules, pointing to the `gh-pages` branches of individual library repositories. The documentation is automatically published using GitHub Pages with Jekyll.

## Managing Documentation Sources

### Adding a New Library Documentation

To add documentation for a new library:

```bash
# Add the submodule pointing to the gh-pages branch
git submodule add -b gh-pages https://github.com/eclipse/keypop-[library-name].git [library-name]

# Commit the changes
git add .
git commit -m "feat: add documentation for [library-name]"
```

### Removing a Library Documentation

To remove documentation for a library:

```bash
# Remove the submodule
git submodule deinit -f [library-name]
rm -rf .git/modules/[library-name]
git rm -f [library-name]

# Commit the changes
git commit -m "feat: remove documentation for [library-name]"
```

## Automatic Updates

This repository includes a GitHub Action that automatically updates all submodules to their latest commits. The action:

- Runs on manual trigger, repository dispatch event, or push to main
- Updates all submodules recursively
- Commits and pushes changes if updates are detected
- Uses a dedicated bot account for commits

You can view the action workflow in `.github/workflows/update-submodules.yml`.

## Contributing

Please read our [contribution guidelines](https://keypop.org/community/contributing/) before submitting any changes.

## License

This project is licensed under the Eclipse Public License - v 2.0. See [LICENSE](LICENSE) for details.
