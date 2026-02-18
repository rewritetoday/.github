# Contributing to Rewrite

Thank you for your interest in contributing to the **Rewrite open-source ecosystem**.
We maintain repositories, SDKs, and tools to help developers send SMS and OTP messages reliably, securely, and at scale.

These guidelines apply to **all repositories under the Rewrite organization**, unless stated otherwise in a specific repository.

---

## Code of Conduct

All contributors are expected to follow the **Rewrite Code of Conduct**.

Unacceptable behavior should be reported to:
**security@rewritetoday.com**

---

## Issues First

**Opening a GitHub Issue before submitting a Pull Request is required**, except for trivial changes such as:
- typos
- small documentation fixes
- non-functional formatting changes

Why this matters:
- Aligns contributions with maintainers and roadmap
- Avoids duplicated or rejected work
- Saves everyone time

Please wait for feedback or approval before starting significant work.

---

## Ways to Contribute

You can contribute by:
- Reporting bugs
- Suggesting features or improvements
- Improving documentation
- Adding examples or integrations
- Submitting code via Pull Requests

All contributions are welcome, as long as they follow these guidelines.

---

## Contribution Flow

1. **Fork** the repository you want to contribute to
2. **Create a branch** from the default branch (`main`)
3. **Follow the setup instructions** of that repository
4. **Write clean, focused changes**
   - Add tests when applicable
   - Update documentation if behavior changes
5. **Commit using Conventional Commits**
6. **Open a Pull Request**
   - Link the related Issue
   - Clearly describe what changed and why

---

## Commits

We use **Conventional Commits** across repositories.

Examples:
- `feat: add delivery receipt retry handling`
- `fix: validate E.164 phone numbers before send`
- `docs: update sms quickstart examples`
- `chore: update issue templates`

Guidelines:
- Keep commits focused and meaningful
- Do not mix unrelated changes
- Never commit secrets or credentials

---

## Versioning and Releases

Some repositories use **Changesets** for versioning.

If required by the project:

```bash
bunx changeset
```

Follow semantic versioning:

- **patch** - bug fixes
- **minor** - backward-compatible features
- **major** - breaking changes

Always follow the repository's existing release process.

---

## Review Process

- All Pull Requests are reviewed by maintainers
- CI checks must pass before approval
- Feedback is part of the process, so be ready to iterate

Maintainers may request changes to ensure consistency, security, and long-term maintainability.

---

## What to Avoid

- Submitting PRs without an approved Issue (when required)
- Mixing multiple unrelated changes in one PR
- Vague commit messages or PR descriptions
- Ignoring CI failures or review comments
- Introducing breaking changes without discussion

---

## Security

**Do not report security issues publicly.**

If you discover a vulnerability:

- Follow the instructions in `SECURITY.md`, or
- Contact: [security@rewritetoday.com](mailto:security@rewritetoday.com)

Thank you for contributing to **Rewrite**.
Your work helps build reliable, secure, and developer-friendly SMS infrastructure.
