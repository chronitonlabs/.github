# Contributing to Chroniton Labs projects

Thank you for your interest in contributing. This guide applies to every Chroniton Labs project. Some projects add their own rules in a CONTRIBUTING.md in their repository, which applies as well.

## Where to start

| You have | Go to |
|---|---|
| An idea, a question, or something you want to discuss before writing code | [Discussions](https://github.com/orgs/chronitonlabs/discussions) |
| A bug or a specific, agreed piece of work | The GitHub Issues of the project concerned |
| A security vulnerability | Private reporting, see [SECURITY.md](SECURITY.md) |

## Before you start

- **Sign the contributor agreement.** Every individual contributor signs the Chroniton Labs Individual Contributor Assignment Agreement through the CLA Assistant check on their first pull request, even if their employer has signed the Entity agreement. If your employer owns relevant rights in your contributions, your employer also signs the Chroniton Labs Entity Contributor Assignment Agreement and lists you in Schedule A. A pull request cannot be merged until every individual contributor to it has signed. You sign once, and it covers every Chroniton Labs project. A new agreement version applies to your later contributions only if you separately sign that version. The agreements, a plain English summary and how to sign are in [contributor-agreements](https://github.com/chronitonlabs/contributor-agreements).
- **Talk to us first** for anything larger than a small fix, so the approach can be agreed before you write the code. Start a discussion for an idea, or open an issue for agreed work.

## Pull requests

- Every commit must be **signed** (GPG or SSH). See [Signing commits](https://docs.github.com/en/authentication/managing-commit-signature-verification/signing-commits).
- Keep a pull request to one change. Include tests that fail without the change and pass with it, where the project has tests.
- Pull requests are merged with a merge commit or squashed. Rebase merging is not used.

## Commit messages

```
Short summary in the imperative, under about 72 characters

What the change does and why, in plain sentences.

Fixes #123
Assisted-by: Claude Code
```

The `Fixes` and `Assisted-by` lines are optional.

## AI-assisted contributions

AI-assisted contributions are welcome, in any amount and for any part of a change. The person who submits a pull request is responsible for it, as with any other tool: they have reviewed it, they stand behind it, and they make sure it does not include material they have no right to contribute.

If you like, you can note AI assistance with an `Assisted-by:` line at the end of the commit message, naming the tool, for example `Assisted-by: Claude Code`. It is optional. It helps us see how contributions are made, and it makes no difference to how your contribution is reviewed.

## Code from other projects

If your contribution includes code you did not write, such as code from another open source project, say so in the pull request, say where it came from, and keep its copyright and licence notices.

## Security issues

Do not report security vulnerabilities in public issues or pull requests. See [SECURITY.md](SECURITY.md).
