# Contributing to keepassxc_site

> :+1::tada: First off, thanks for taking the time to contribute! :tada::+1:

The following is a set of guidelines for contributing to the KeePassXC website on GitHub Pages.
These are just guidelines, not rules. Use your best judgment, and feel free to propose changes to this document in a pull request.

## Table of contents

[Getting started](#getting-started)

[How can I contribute?](#how-can-i-contribute)
  * [Bug reports](#bug-reports)
  * [Discuss with the team](#discuss-with-the-team)
  * [Pull requests](#pull-requests)

[Styleguides](#styleguides)
  * [Git branch strategy](#git-branch-strategy)
  * [Git commit messages](#git-commit-messages)

## Getting started

### Open Source Contribution Policy

> **Source**: [Version 0.3, 2015–11–18](https://medium.com/@jmaynard/a-contribution-policy-for-open-source-that-works-bfc4600c9d83#.i9ntbhmad)

#### Policy

We will accept contributions of good code that we can use from anyone.

#### What this means

 - “We will accept”: This means that we will incorporate your contribution into the project’s codebase, adapt it as needed, and give you full credit for your work.
 - “contributions”: This means just about anything you wish to contribute to the project, as long as it is good code we can use. The easier you make it for us to accept your contribution, the happier we are, but if it’s good enough, we will do a reasonable amount of work to use it.
 - “of good code”: This means that we will accept contributions that work well and efficiently, that fit in with the goals of the project, that match the project’s coding style, and that do not impose an undue maintenance workload on us going forward. This does not mean just program code, either, but documentation and artistic works as appropriate to the project.
 - “that we can use”: This means that your contribution must be given freely and irrevocably, that you must have the right to contribute it for our unrestricted use, and that your contribution is made under a license that is compatible with the license the project has chosen and that permits us to include, distribute, and modify your work without restriction.
 - “from anyone”: This means exactly that. We don’t care about anything but your code. We don’t care about your race, religion, national origin, biological gender, perceived gender, sexual orientation, lifestyle, political viewpoint, or anything extraneous like that. We will neither reject your contribution nor grant it preferential treatment on any basis except the code itself. We do, however, reserve the right to tell you to go away if you behave too obnoxiously toward us.

#### If Your Contribution Is Rejected

If we reject your contribution, it means only that we do not consider it suitable for our project in the form it was submitted. It is not personal. If you ask civilly, we will be happy to discuss it with you and help you understand why it was rejected, and if possible improve it so we can accept it.

#### Revision History
 * 0.1, 2011–11–18: Initial draft.
 * 0.2, 2011–11–18: Added “If Your Contribution Is Rejected” section.
 * 0.3, 2011–11–19: Added “irrevocably” to “we can use” and changed “it” to “your contribution” in the “if rejected” section. Thanks to Patrick Maupin.

## How can I contribute?

We're always looking for suggestions to improve our web site. If you have a suggestion for an improvement, or would like to suggest completely new content for the KeePassXC site, please use the [issue tracker on GitHub][issues-section].

### Bug reports

Our web site isn't always perfect, but we strive to always improve our work. You may file bug reports in the issue tracker.

Before submitting a bug report, check if the problem has already been reported; add a comment to that issue if you have something to add rather than creating another issue.

### Discuss with the team

You can talk to the KeePassXC team about anything relating to the project or its web site on the dedicated issue tracker or in the IRC channel on Freenode (`#keepassxc-dev` on `irc.freenode.net`, or use the [webchat](https://webchat.freenode.net/?channels=%23keepassxc-dev)).

### Pull requests

Along with our desire to hear your feedback and suggestions, we're also interested in accepting direct assistance in the form of code.

All pull requests must comply with the above requirements and with the styleguides below.

## Styleguides

### Git branch strategy

The Branch Strategy is based on [git-flow-lite](http://nvie.com/posts/a-successful-git-branching-model/).

* **master** – points to the latest public release
* **develop** – points to the development of the next release, contains tested and reviewed code
* **feature/**[name] – points to a branch with a new feature, one which is candidate for merge into develop (subject to rebase)
* **hotfix/**[name] – points to a branch with a fix for a particular issue ID

### Git commit messages

* Use the present tense ("Add feature" not "Added feature")
* Use the imperative mood ("Move cursor to…" not "Moves cursor to…")
* Limit the first line to 72 characters or less
* Reference issues and pull requests liberally
* If your pull request fixes an existing issue, add "Fixes #ISSUENUMBER" to your pull request description

[issues-section]:https://github.com/keepassxreboot/keepassxreboot.github.io/issues
