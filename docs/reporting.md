# Reporting guide

## Open a form

Start at [New issue](https://github.com/shesshdotapp/support/issues/new/choose), choose a form, fill in the fields, and submit.
Questions, bugs, feature requests, and feedback all stay in **Issues**, so you can track them in one place.
GitHub sign-in is required to submit. English and Bahasa Indonesia are welcome.

| Form | When to use it |
| --- | --- |
| [Bug report](https://github.com/shesshdotapp/support/issues/new?template=bug_report.yml) | Something looks wrong or does not work, including the website or installer |
| [Feature request](https://github.com/shesshdotapp/support/issues/new?template=feature_request.yml) | A new capability or a change to an existing workflow |
| [Connection or login](https://github.com/shesshdotapp/support/issues/new?template=connection_login.yml) | Connecting, passwords, identity files, SSH agent, Keychain, or reconnect |
| [Performance or memory](https://github.com/shesshdotapp/support/issues/new?template=performance_memory.yml) | High memory or CPU, freezes, or lag |
| [Ask for help](https://github.com/shesshdotapp/support/issues/new?template=help_question.yml) | Setup questions, unexpected behavior, or uncertainty about which form to choose |
| [Feedback](https://github.com/shesshdotapp/support/issues/new?template=feedback.yml) | General feedback or a topic not covered by the other forms |

You do not need to diagnose the cause. If you cannot reproduce a problem, describe what happened before you noticed it.
Write “Not sure” for unavailable information. Fields marked as optional can be left blank.

## Make the report easy to understand

Use a specific title, such as:

- `[Bug]: Terminal becomes blank after closing a duplicate VPS tab`
- `[Feature]: Transfer files between my Mac and VPS using SFTP`
- `[Question]: How do I import a host from my SSH config?`

For bugs, explain what you did, what happened, and what you expected. Include the app and macOS versions if relevant.
For features, describe the task you want to complete and how the proposed change would help.
One issue should cover one problem or feature. Search [existing issues](https://github.com/shesshdotapp/support/issues) before submitting a duplicate.

## Optional troubleshooting

The [troubleshooting guide](troubleshooting.md) can help you collect useful details.
Testing the same connection in macOS Terminal is helpful for connection problems, but it is not required to ask for help.

## Screenshots and logs

Remove passwords, private keys, tokens, and private server details before uploading.
Use placeholders such as `user@example.com` instead of real login details.
Sensitive vulnerabilities follow the separate [security reporting guide](../SECURITY.md).

## Follow-up

The maintainer may ask for missing details, link a duplicate, or update the issue when a fix is available.
Reply in the original issue. Feature requests are not promises of a release date.
