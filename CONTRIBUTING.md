# Contribution Guidelines

Thanks for helping keep this list accurate. Please read this page before opening a pull request.

## What belongs here

A tool belongs on this list when it is one of the following:

- An editor or IDE whose agents can plan and change code across a project.
- A desktop workspace, orchestration app, or terminal built for running and supervising coding agents, especially several at once.
- A first-party desktop app from an agent maker, or a phone or browser client for agents that run on your own machines.
- An open standard for connecting editors and agents, or a definition, guide, or essay that helps people work this way.

It also has to be:

- Publicly available today, with a download, public documentation, or source code.
- Maintained: the repository is not archived, the project has not announced that it is unmaintained, and it has shipped a commit or release in roughly the last six months. Projects that have announced a shutdown stay listed only while they still work, with the announcement noted.
- The official project, not a mirror, a rebrand of someone else's work, or a fork without meaningful changes of its own.

Chat-only assistants, autocomplete plugins, and general terminal emulators without agent features belong elsewhere.

## Entry format

Add one line to the section that fits best:

```markdown
- [Name](https://link.to/official/site-or-repo) - What the tool does and who makes it, in one or two plain sentences. macOS. Open source (MIT).
```

- Link to the official repository, product page, or documentation.
- Write the description yourself. Describe what it does; leave out superlatives, rankings, pricing claims, and benchmark numbers.
- Label the license as `Open source (SPDX-ID)`, `Source-available (license name)`, or `Proprietary`.
- Add `macOS` when the tool only runs on a Mac.
- Reading entries skip the license label and say who wrote the piece. Mark pieces written by a vendor in this category as vendor-written.
- Keep entries alphabetical within the section (case-insensitive). Descriptions start with a capital letter and end with a period.

## Pull requests

- One entry per pull request. Separate pull requests are easier to review and to revert.
- Use the tool's name as the pull request title, and say in the body why it belongs here.
- Check that every link resolves and that the repository is not archived.
- Run `npx awesome-lint` before you push.

## Corrections and removals

Open an issue or a pull request when a link breaks, a project is renamed, archived, or shut down, or a description has gone stale. Removing dead entries is as useful as adding new ones.
