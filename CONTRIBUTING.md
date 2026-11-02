# Contributing to Mirage-91

Thanks for helping out! This guide applies to every repository in the Mirage-91 organization, unless a repository has its own `CONTRIBUTING.md`.

## Issues

- Check the open issues before you create a new one.
- Use the issue templates (bug, feature/idea, documentation, organizational) so we have the context we need.
- If you want to work on an issue, assign yourself or leave a comment so nobody duplicates the work.

## Branches

You can push small fixes directly to `main`. For anything bigger, use a branch and open a pull request:

| Prefix | Use for | Example |
|---|---|---|
| `feature/` | new functionality | `feature/csp-classifier` |
| `fix/` | bug fixes | `fix/epoch-offset` |
| `docs/` | documentation, notebooks | `docs/p300-howto` |
| `exp/` | experiments that may never be merged | `exp/riemann-features` |

## Commits

- Write short messages in the imperative: `Add laplacian filter`, not `added stuff`.
- Commit small, logical steps rather than one huge commit at the end.

## Pull requests

- Fill in the pull request template.
- Ask someone from the relevant team to look at it, especially for changes to the online pipeline before a competition.
- Delete the branch once it is merged.

## Data and large files

- **Never commit EEG recordings, personal data of pilots, or trained models.** Keep them out of git (see `.gitignore`) and share them through the team's storage.
- Keep notebooks small. Clear large outputs before you commit.

## Python setup

Most projects use Python 3.10+:

```bash
python -m venv .venv
.venv\Scripts\activate        # Windows
source .venv/bin/activate     # macOS / Linux
pip install -r requirements.txt
```

## Starting a new project

Create a new repository from [project-template](https://github.com/Mirage-91/project-template) (*Use this template*), or ask the **Admins** team to create one for you.

## Questions

Open a discussion or issue, ask in the team chat, or contact the Admins team (`@Mirage-91/admins`).

Please follow our [Code of Conduct](CODE_OF_CONDUCT.md).
