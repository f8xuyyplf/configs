# CI Notes

- All workflow files live in `.github/workflows` and are named after the trigger.
- Use `actions/checkout@v4` unless a specific version is required.
- Cache dependencies with `actions/cache` to speed up jobs.
- Keep secrets in GitHub Environments, not in the repo.
