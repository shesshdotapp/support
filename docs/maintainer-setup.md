# Support form setup

## Make the forms visible on GitHub

1. In repository **Settings → General → Features**, enable **Issues**.
2. Publish `.github/ISSUE_TEMPLATE/`, README, and the support guides to the repository's **default branch**. Local files or files on another branch do not activate the forms.
3. Open [the issue chooser](https://github.com/shesshdotapp/support/issues/new/choose) while signed in. Confirm all six forms appear.
4. Open each form from the README. Check the required fields and example text before submitting any report.
5. Under **Issues → Labels**, ensure `bug`, `enhancement`, `question`, `connection`, and `performance` exist. Forms reference these labels; they do not create them.

Discussions are not required for this support flow. Existing discussions can remain available, but direct new requests to the issue chooser.
For private vulnerability reports, enable **Private vulnerability reporting** in repository settings if available.

## Maintainer review

- Check whether the report duplicates an existing issue and link it when appropriate.
- Ask for missing details in the same issue.
- Use labels to separate bugs, features, questions, connection issues, and performance issues.
- When resolving a bug, mention the fixed release or workaround before closing it.
- Treat feature submissions as proposals, not promised release commitments.

## If forms do not appear

Check the default branch, Issues setting, `.github/ISSUE_TEMPLATE` path, and `.yml` file extension.
A YAML parse check only checks file syntax; GitHub must also accept the issue-form schema.
These are issue forms, so they appear under **Issues → New issue**, not under Discussions.

References: [GitHub template configuration](https://docs.github.com/en/communities/using-templates-to-encourage-useful-issues-and-pull-requests/configuring-issue-templates-for-your-repository)
and [issue form syntax](https://docs.github.com/en/communities/using-templates-to-encourage-useful-issues-and-pull-requests/syntax-for-issue-forms).
