# Troubleshooting

These optional checks help narrow down common shessh issues. You can [ask for help](https://github.com/shesshdotapp/support/issues/new?template=help_question.yml) without completing them.

## Connection Fails

Try the same connection from macOS Terminal:

```sh
ssh user@host
```

If Terminal also fails, the issue is likely with the server, network, credentials, firewall, or SSH configuration.

If Terminal works but shessh fails, open a [connection report](https://github.com/shesshdotapp/support/issues/new?template=connection_login.yml) and include:

- Shessh version
- macOS version
- Authentication type
- Whether the host came from `~/.ssh/config`
- The exact error message shown by shessh

## Password Keeps Asking Again

Check whether the profile has Remember in Keychain enabled.

If the profile was not used for more than the credential expiry window, shessh may ask again.

## Blank Terminal Or Split Pane

Open a [bug report](https://github.com/shesshdotapp/support/issues/new?template=bug_report.yml) with:

- Number of tabs
- Number of split panes
- Whether the same VPS was opened more than once
- What action made the terminal blank
- Whether resizing the window changes anything

## High Memory Use

Open a [performance report](https://github.com/shesshdotapp/support/issues/new?template=performance_memory.yml) with:

- Number of tabs and split panes
- How long shessh was running
- Whether a VPS was streaming output
- Whether the Mac slept and woke during the session
- A screenshot from Activity Monitor if available

