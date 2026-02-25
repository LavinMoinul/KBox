## Contributing to kbox

Thanks for your interest in contributing to `kbox`!

### Workflow overview

- **Fork and clone**: Fork the repository to your own account and clone it locally.
- **Sync often**: Keep your local `main` branch up to date with the upstream `main`.
- **Code style**: Follow existing conventions in C and C++ code once they are established in this repo.

### Main branch mindset

- **Protected in spirit**: Treat `main` as a protected branch.
- **No direct pushes**: Avoid pushing directly to `main`; always use pull requests.

### Branching model

- **Feature branches**: Create short-lived feature branches from `main`, for example:
  - `feature/cli-scaffolding`
  - `feature/file-vault-metadata`
- **Yoshua integration branch**: Aggregate work for a set of related features in a `yoshua` branch when appropriate.

### Commits

- **Small commits**: Prefer small, focused commits with clear messages.
- **Single responsibility**: Each commit should represent one logical change.

### Pull requests

- **Source branch**: Open pull requests from the `yoshua` branch into `main`.
- **Scope**: Keep PRs small and easy to review.
- **Discussion**: Use PRs for code review, questions, and design discussion.

This project is still in its early layout phase; please avoid adding encryption logic or build tooling until there is agreement on the initial design.
