# Agent instructions

This is a throwaway sandbox repository for factory-orchestrator acceptance tests.

- Never push to `main`. Commit on your branch and open a pull request.
- Start the pull request title with the ticket key (for example, `KRG-123: add a file`).
- After you open the pull request, wait for the `check` CI job to pass (`gh pr checks <number> --watch`).
- When `check` passes, merge the pull request with a merge commit: `gh pr merge <number> --merge`. Do not squash or rebase.
- Then report that you are done.
