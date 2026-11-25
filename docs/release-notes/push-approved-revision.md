---
type: feature
---

- `lore-client`: From a materialized working tree, `lore push <branch> --expect-revision <hash>
  --expect-base <hash>` limits a push to one revision directly following the expected branch point.
  The push refuses plans that would upload any other revision or update another branch or repository.
