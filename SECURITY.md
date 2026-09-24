# Reporting a security problem

If you've found a security problem in Auto Tournament, report it through GitHub's private
vulnerability reporting: open the **Security** tab on the affected repo and use
**"Report a vulnerability"** (or go straight to
`https://github.com/Auto-Tournament/<repo>/security/advisories/new`). It's enabled on every
repo in this org. Please don't open a public issue or pull request for it — anyone running an
Auto Tournament instance would see it before they had a chance to update.

## What to send

Enough to reproduce it: what you did, what happened, what you expected, and which version or
component you were on. A rough note is fine. If you're not sure it counts, send it anyway.

Test against your own install rather than somebody else's.

## Which versions get fixes

The newest release. Each part of Auto Tournament is released from its `main` branch, and there
are no older branches that fixes get backported to.

## What happens after

Auto Tournament is maintained by one person, so there's no promised response time. Anything that
would let someone take over an instance, run code on it — including through the module installer
or signed modules — or hijack game servers (RCON, server tokens) goes ahead of everything else.

Once a fix is out, the problem gets a security advisory on the repository the fix is in. There's
no bug bounty. If you'd like credit, you get it in the advisory and the release notes.
