# Contributing

1. **Start from an issue.** Every change has a GitHub Issue. Use the issue forms and
   fill in the type, module and priority; add the audit and user-story references
   where they apply. Record decisions and progress as comments on the issue.
2. **Branch** as `<type>/<issue-id>-<short-slug>`, for example `fix/142-login-timeout`.
3. **Commit** with [Conventional Commits](https://www.conventionalcommits.org/) and the
   issue ID, for example `fix(auth): handle expired sessions (#142)`.
4. **Open a pull request** that says `Closes #142`, with test evidence. Never push
   directly to the default branch.
5. **Changelog:** add an entry under *Unreleased* in `CHANGELOG.md`, with the issue ID.
   User-facing "What's New?" text is written separately, in plain language, with no
   issue IDs or labels.
