# Expected behavior
- Renovate should assign reviewers when checking MR status after a week, because MR has pipeline errors

# Actual behavior
- Renovate tries to automerge MR, failing due to Gitlab rules rejecting MR with failed pipeline
