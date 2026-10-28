# Contributing

Thanks for wanting to help. These rules apply to all public repositories under
[eduralph](https://github.com/eduralph), [Ralphovi](https://github.com/Ralphovi)
and [getwyrd](https://github.com/getwyrd). A project can add stricter rules in
its own `CONTRIBUTING.md`. Where it does, the project's rules win.

## Talk first, then code

For anything beyond a small fix, open an issue (or comment on an existing one)
and wait for a maintainer to agree before you write code. Describe the problem
you want solved, not only the fix you have in mind. This saves you from spending
time on a change that won't be merged.

When you open the pull request, link the issue in its description:

- `Closes #123` if the PR fully resolves it
- `Refs #123` if it is part of the work

Pull requests that change code without a linked issue get the `needs-issue`
label. They are not closed automatically, but they wait until an issue exists
and a maintainer has agreed to the change. If the change isn't wanted, the PR
will be closed.

## What you can send without an issue

- Typo fixes
- Documentation fixes and clarifications

Some projects require an issue for every pull request, documentation included.
Their checks will tell you. In that case, open a short issue first.

## What won't be merged unless an issue asked for it

- Formatting or style changes across many files
- Refactors, renames or moving code around
- Dependency bumps
- New features nobody discussed
- Changes to CI, release or tooling configuration
- Large changes spread across the codebase

## AI-assisted contributions

Using AI tools is fine. The maintainers use them too. What matters is that a
person understands every change in the pull request and stands behind it:

- You can explain why each change is there and answer review questions about it
  yourself.
- You ran the project's checks and tests, and they pass.
- The PR description is short and accurate, written for the person reviewing it.

A pull request that nobody can answer for will be closed.

## Pull request basics

- One change per pull request. Small PRs get reviewed sooner.
- Run the project's checks before opening the PR. The project's README or
  `CONTRIBUTING.md` says how.
- Sign off every commit with the [Developer Certificate of Origin](https://developercertificate.org/)
  (DCO). This is a statement that you wrote the change or have the right to
  submit it. `git commit -s` adds the `Signed-off-by:` line for you.
- Your contribution is licensed under the project's license.

## Reporting bugs

Open an issue with the steps to reproduce, what you expected, what happened
instead, and the versions you used. Use the project's issue templates if it has
any.

## Security issues

Don't report security problems in a public issue. Use **Report a vulnerability**
on the project's Security tab, or follow the project's `SECURITY.md` if it has
one.

## Response times

These projects are maintained in spare time. There is no promised response time
for issues or pull requests.
