---
"zerithdb-db": patch
---

Implement `$unset` operator in `CollectionClient.update()`. Previously, only `$set` was handled and `$unset` was silently ignored despite being defined in the `UpdateSpec` type.
