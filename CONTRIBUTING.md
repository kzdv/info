# Contributing to ZDV

:+1::tada: First off, thanks for taking the time to contribute! :tada::+1:

The following is a general guide for contributing to ZDV.

#### Table Of Contents

[What should I know before I get started?](#what-should-i-know-before-i-get-started)
  * [Code Editor](#code-editor)

[How Can I Contribute?](#how-can-i-contribute)
  * [Reporting Bugs](#reporting-bugs)
  * [Your First Code Contribution](#your-first-code-contribution)
  * [Pull Requests](#pull-requests)

[Styleguides](#styleguides)
  * [Git Commit Messages](#git-commit-messages)
  * [JavaScript Styleguide](#javascript-styleguide)

[Licensing](#licensing)
 * [Open Source First](#open-source-first)

## What should I know before I get started?

### Code Editor

The first thing you're going to need to get started is a code editor.  There are many out there with many opinionated approaches that suit different needs.  Use the one that you are most comfortable with, but can also abide by this guide.  Some examples:
* Visual Studio Code - Useful for pretty much all languages
  * You will need some extensions to make your life easier:
    * JavaScript/TypeScript: eslint prettier
    * Golang: Go extension by the Go Team at Google
    * PHP/Laravel: PHP IntelliSense by Felix Becker, Laravel Blade Snippets by  Winnie Lin
* PHPStorm - Useful for PHP, HTML, CSS, Javascript [alternative: WebStorm for basic HTML, CSS, JavaScript/TypeScript]
  * Add a Laravel plugin to help QOL
* Goland - Useful for Golang, HTML, CSS

## How Can I Contribute?

### Reporting Bugs

This section guides you through submitting a bug report. Following these guidelines helps maintainers and the community understand your report :pencil:, reproduce the behavior :computer: :computer:, and find related reports :mag_right:.

Before creating bug reports, please check the issues for the project, as you might find out that you don't need to create one. When you are creating a bug report, please [include as many details as possible](#how-do-i-submit-a-good-bug-report). Fill out [the required template](BUG_REPORT.md), the information it asks for helps us resolve issues faster.

> **Note:** If you find a **Closed** issue that seems like it is the same thing that you're experiencing, open a new issue and include a link to the original issue in the body of your new one.

#### How Do I Submit A (Good) Bug Report?

Bugs are tracked as [GitHub issues](https://guides.github.com/features/issues/). After you've determined which project your bug is related to, create an issue on that repository and provide the following information by filling in [the template](BUG_REPORT.md).

Explain the problem and include additional details to help maintainers reproduce the problem:

* **Use a clear and descriptive title** for the issue to identify the problem.
* **Describe the exact steps which reproduce the problem** in as many details as possible. For example, start by explaining how you accessed the project, e.g. which command exactly you used in the terminal, etc. otherwise. When listing steps, **don't just say what you did, but explain how you did it**. For example, if you moved the cursor to the end of a line, explain if you used the mouse, or a keyboard shortcut, and if so which one?
* **Provide specific examples to demonstrate the steps**. Include links to files or GitHub projects, or copy/pasteable snippets, which you use in those examples. If you're providing snippets in the issue, use [Markdown code blocks](https://help.github.com/articles/markdown-basics/#multiple-lines).
* **Describe the behavior you observed after following the steps** and point out what exactly is the problem with that behavior.
* **Explain which behavior you expected to see instead and why.**
* **Include screenshots and animated GIFs** which show you following the described steps and clearly demonstrate the problem if possible. You can use [this tool](https://www.cockos.com/licecap/) to record GIFs on macOS and Windows, and [this tool](https://github.com/colinkeenan/silentcast) or [this tool](https://github.com/GNOME/byzanz) on Linux.
* **If the problem wasn't triggered by a specific action**, describe what you were doing before the problem happened and share more information using the guidelines below.

Provide more context by answering these questions:

* **Did the problem start happening recently** or was this always a problem?
* **Can you reliably reproduce the issue?** If not, provide details about how often the problem happens and under which conditions it normally happens.

Include details about your configuration and environment:

* **What's the name and version of the OS you're using?**
* **What's the name and version of the webbrowser you're using?**

### Your First Code Contribution

Unsure where to begin contributing? Ask us for guidance or find an issue you think you can tackle.

Both issue lists are sorted by total number of comments. While not perfect, number of comments is a reasonable proxy for impact a given change will have.

### Pull Requests

The process described here has several goals:

- Maintain code quality
- Fix problems that are important to users
- Enable a sustainable system for maintainers to review contributions

Please follow these steps to have your contribution considered by the maintainers:

1. Follow all instructions in [the template](PULL_REQUEST_TEMPLATE.md)
2. Follow the [styleguides](#styleguides)
3. After you submit your pull request, verify that all [status checks](https://help.github.com/articles/about-status-checks/) are passing <details><summary>What if the status checks are failing?</summary>If a status check is failing, and you believe that the failure is unrelated to your change, please leave a comment on the pull request explaining why you believe the failure is unrelated. A maintainer will re-run the status check for you. If we conclude that the failure was a false positive, then we will open an issue to track that problem with our status check suite.</details>

While the prerequisites above must be satisfied prior to having your pull request reviewed, the reviewer(s) may ask you to complete additional design work, tests, or other changes before your pull request can be ultimately accepted.

## Styleguides

### Git Commit Messages

* Use the present tense ("Add feature" not "Added feature")
* Use the imperative mood ("Move cursor to..." not "Moves cursor to...")
* Limit the first line to 72 characters or less
* Reference issues and pull requests liberally after the first line
* When only changing documentation, include `[ci skip]` in the commit title

### JavaScript Styleguide

Javascript stylings must match one or both of the following:
* [Prettier](https://prettier.io)
* [Airbnb](https://github.com/airbnb/javascript)

You must use eslint to apply linting.

### PHP

All PHP must comply with PSR-2

### Golang

Use standard Golang conventions as enforced by the complier and `go fmt`.

## Licensing

### Open Source First

Going forward, all new ZDV projects must utilize Open Source licensing to the maximum extent possible.  Examples of authorized licenses:

* GNU Public License (GPL) v3 and newer
* Afferno GNU Public License (AGPL)
* BSD License
* MIT License
* Apache License
* Creative Common licenses that allow deviations