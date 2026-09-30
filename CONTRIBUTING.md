# Contributing to 'Eclipse Keypop'

**Welcome to the Eclipse Keypop Community!**

We are thrilled to have you onboard and look forward to your contributions. Whether you're a coder, designer,
documenter, or enthusiast, your involvement is invaluable to us. Here's how you can start contributing to Eclipse
Keypop:

## Project Description

Eclipse Keypop provides Java and C++ transcriptions of the Ticketing Terminal APIs defined by the Calypso Networks
Association.

This repository aggregates and publishes the API documentation of all Eclipse Keypop libraries, both Java (Javadoc)
and C++ (Doxygen), available at https://docs.keypop.org. The documentation itself is generated in each library
repository; this repository only hosts the aggregation and publication automation.

* Project home: https://projects.eclipse.org/projects/iot.keypop
* Developer resources: https://projects.eclipse.org/projects/iot.keypop/developer

## Quick Start

1. **Read the Contribution Guidelines**: Before starting, please visit our detailed contributing guide at the
[Eclipse Keypop Contribution Guide](https://keypop.org/community/contributing/).
This guide covers all the necessary information about contributing to the project.

2. **Sign the Eclipse Contributor Agreement**: See the [Eclipse Contributor Agreement](#eclipse-contributor-agreement)
section below.

3. **Join the mailing list**: Connect with other contributors on our
[mailing list](https://accounts.eclipse.org/mailing-list/keypop-dev/).
It's a great place to ask questions, share ideas, and collaborate.

4. **Explore Open Issues**: Check out the issues tab of this GitHub repository.

## How to Contribute

- **Publication automation**: Submit pull requests against the `main` branch to improve the workflows
(`.github/workflows/`) and the publication script (`.github/scripts/`).

- **Documentation aggregation**: Submodule definitions and site configuration live on the `gh-pages-source` branch.
The `gh-pages` branch is generated automatically and must never be edited manually.

- **API content**: Errors in the API documentation itself must be reported and fixed in the corresponding library
repository, not here.

- **Feedback**: Share your experience using Eclipse Keypop. Feedback on usability, features, and your overall experience
is incredibly valuable.

- **Community Support**: Answer questions on the mailing list, help with user support, and participate in
discussions.

**Security issues must not be reported through public issues or pull requests.** Please follow the process described
in the [Security Policy](SECURITY.md).

## Eclipse Contributor Agreement

In order to be able to contribute to Eclipse Foundation projects you must electronically sign the Eclipse Contributor
Agreement (ECA).

* https://www.eclipse.org/legal/ECA.php

The ECA provides the Eclipse Foundation with a permanent record that you agree that each of your contributions will
comply with the commitments documented in the Developer Certificate of Origin (DCO). Having an ECA on file associated
with the email address matching the "Author" field of your contribution's Git commits fulfils the DCO's requirement
that you sign-off on your contributions.

For more information, please see the Eclipse Committer Handbook:
https://www.eclipse.org/projects/handbook/#resources-commit

## Project License

This project is licensed under the MIT License (see the [LICENSE](LICENSE) file). Contributions are received under
the terms of the project license.

## Eclipse Foundation Development Process

This Eclipse Foundation open project is governed by the Eclipse Foundation Development Process and operates under the
terms of the Eclipse IP Policy.

* https://www.eclipse.org/projects/dev_process
* https://www.eclipse.org/org/documents/Eclipse_IP_Policy.pdf

This repository is subject to the Terms of Use of the Eclipse Foundation.

* https://www.eclipse.org/legal/termsofuse.php

## Code of Conduct

Please adhere to the [Eclipse Foundation Community Code of Conduct](CODE_OF_CONDUCT.md) when participating in this
project.

## Need Help?

If you have any questions or need assistance, please reach out on the
[mailing list](https://accounts.eclipse.org/mailing-list/keypop-dev/).

---

_Your contribution is the key to the success of Eclipse Keypop. Let's build something amazing together!_
