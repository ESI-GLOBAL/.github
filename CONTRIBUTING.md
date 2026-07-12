# Contributing

ESI Global's primary engineering repositories are private. Authorized contributors should:

1. start from a tracked issue with clear acceptance criteria;
2. create a focused branch rather than pushing to the default branch;
3. during the temporary rollout, send `feat/*`, `fix/*`, `docs/*`, `chore/*`, and `hotfix/*` branches to `dev`, then promote only `dev -> test -> stage -> main`;
4. keep commits reviewable and free of secrets or generated credentials;
5. run the repository's documented validation commands locally and record the exact commands/results in the PR;
6. open a pull request using the shared template;
7. address failed checks and review conversations before merge.

Repository-specific guidance takes precedence when it is stricter than this shared baseline.
