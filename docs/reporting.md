# Reporting Guide

This repository is the central public place for shessh support.

## Use Discussions For

- Setup questions
- Login troubleshooting
- SSH config import questions
- Keychain behavior questions
- Installer and update questions
- Asking whether something is expected
- Sharing general feedback

Start here when you are not sure whether the problem is a bug:

https://github.com/shesshdotapp/support/discussions

## Use Issues For

- Reproducible bugs
- Crashes
- Blank terminal panes
- Failed reconnect behavior
- Broken download or installer behavior
- Performance or memory problems
- UI issues with clear screenshots or steps

Open an Issue here:

https://github.com/shesshdotapp/support/issues

## Choose A Template

| Template | Use it for |
| --- | --- |
| Bug report | General reproducible app bugs |
| Connection or login issue | SSH login, password, identity file, SSH agent, Keychain, reconnect |
| Performance or memory issue | Memory growth, high CPU, freezes, terminal lag |
| Feature request | New workflows, UI improvements, planned feature ideas |

## What Makes A Good Bug Report

Include:

- Shessh version
- macOS version
- Mac model and chip
- Authentication type
- Whether the host was imported from `~/.ssh/config`
- Steps to reproduce
- Expected result
- Actual result
- How often it happens

For connection bugs, also include whether this works in macOS Terminal:

```sh
ssh user@host
```

## What Not To Post

Do not post:

- VPS passwords
- Private keys
- API tokens
- Recovery keys
- Full server inventories
- Logs containing credentials
- Screenshots with secret values

Redact sensitive values before uploading screenshots or logs.

## Issue Scope

Use one issue per problem.

Good:

- "Split pane becomes blank after closing duplicate VPS tab"
- "Keychain password is requested again after reconnect"

Too broad:

- "Several terminal bugs"
- "Login, tabs, and installer problems"

## Status Labels

Issues may be labeled by area or status:

- `bug`
- `enhancement`
- `question`
- `needs-info`
- `connection`
- `authentication`
- `keychain`
- `terminal`
- `performance`
- `installer`
- `website`
