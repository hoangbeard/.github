# Contributing

Thanks for taking the time to help. Fixes, ideas and questions are all welcome.

## Before you start

- For a small fix, such as a typo or a broken link, open a pull request directly.
- For a bigger change, open an issue first so we can agree on the approach.
- For a security issue, do not open an issue. Follow [SECURITY.md](SECURITY.md).

## Making a change

1. Fork the repository and create a branch from `main`.
2. Install the pre-commit hooks: `pre-commit install`.
   They scan for secrets before every commit.
3. Keep the change focused on one thing.
4. Use [Conventional Commits](https://www.conventionalcommits.org/) for commit
   messages, for example `fix: handle empty config file`.
5. Update the README or docs if the behavior changes.
6. Open a pull request and fill in the template.

## Ground rules

- Never commit real secrets, keys, tokens or internal hostnames.
  Use placeholders such as `example.com` and `123456789012`.
- Labs and examples must be safe to run on your own machine or test account.
- Be kind. See the [Code of Conduct](CODE_OF_CONDUCT.md).

By contributing, you agree that your work is released under the repository's license.
