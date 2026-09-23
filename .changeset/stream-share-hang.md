---
"effect": patch
---

Fix `Stream.broadcast` and `Stream.share` subscribers hanging when they subscribe after the upstream has ended, or when the `dropping` strategy discards the end while they are busy.
