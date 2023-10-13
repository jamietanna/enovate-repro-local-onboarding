# Renovate repro for `local` platform must be onboarded

As part of https://github.com/renovatebot/renovate/discussions/25203

When running:

```sh
env LOG_LEVEL=debug npx renovate@37 --platform=local
```

You can see that this fails to scan, as the onboarding branch is attempted to check.
