# Contributing to Auto Tournament

Thanks for helping out. These rules apply to every repository in the
Auto-Tournament organization; a repository's own `CONTRIBUTING.md` adds how to
build and test it.

## Pull requests

Every pull request is read line by line, by one maintainer, in their spare
time. Before you open one:

- Found a bug? An issue with the logs is the most helpful thing you can send.
- Open an issue first for a new feature, a design change, a rewrite or a major
  dependency upgrade, and wait until we've agreed on the approach. A PR like
  that without an agreed issue is closed.
- Keep it to one fix or feature: under ~10 files and a few hundred changed
  lines. A bigger change goes in several small PRs.
- Have at most 3 PRs open at a time. The PRs of one agreed change count as one.
- Run it yourself on a real install (a real server for anything that touches
  one), and say in the PR what you ran and what you saw. Lint, CI and the
  test suite alone don't count as tested. A dependency upgrade means using
  what it powers, like sending a real email after an email library upgrade.
- If an AI tool wrote any of it, say which one, and read and understand every
  line before you open the PR. Only tick the box that says so when it's true.
  Large batches of AI-written PRs are closed without review.
- Leave the UI and the docs alone unless you've asked first: the maintainer
  does those.
- Follow the existing code style, and write commit messages that say what
  changed and why.

## Contributor License Agreement

Before your first pull request can be merged, you sign the
[CLA](https://github.com/Auto-Tournament/auto-tournament/blob/main/CLA.md) by
commenting on the pull request as the CLA bot asks.

## Questions

Ask on [Discord](https://discord.gg/n7gHYau7aW).
