# .github

The organisation-wide defaults for SecuritySolution.tech repositories. GitHub applies the
files here to every public repository in the organisation that does not have its own:

- `profile/README.md` is the organisation's public profile page.
- `SECURITY.md` is the security policy shown on every repository's Security tab.
- `PULL_REQUEST_TEMPLATE.md` and `.github/ISSUE_TEMPLATE/` are the default templates.
- `workflow-templates/` are the starter workflows offered under Actions, "New workflow",
  so a new repository starts with the same gates as the rest: pinned actions,
  least-privilege permissions, and the quality and security checks the website runs.

How the company builds, and why these defaults look the way they do, is written up in the
handbook (`securitysolution-tech/handbook`, `company/how-we-build.md`).
