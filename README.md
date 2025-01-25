# Merge Queu(e)

Quick MVP to test out behavior with pull requests and merge queues.

## Scenario

- Workflows 'a' and 'b' each run as a check on each PR and when a PR is added to the merge queue.
- The PR is only merged into main if both workflows succeed
- If either workflow fails, we need to take action to cleanup changes made by each