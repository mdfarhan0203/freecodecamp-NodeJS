# Today Learing

# Version format — MAJOR.MINOR.PATCH
- version   -> 1.3.8
    - 1 → MAJOR version → Big updates, may break old code.

    - 3 → MINOR version → New features, but backward-compatible.

    - 8 → PATCH version → Small fixes or bug fixes, no new features.


# Summary Table

| Symbol | Example    | Updates Allowed       | Notes                          |
| :----- | :--------- | :-------------------- | :----------------------------- |
| None   | `"1.3.8"`  | None                  | Always stays on 1.3.8          |
| `~`    | `"~1.3.8"` | Patch only → 1.3.x    | Safe for bug fixes             |
| `^`    | `"^1.3.8"` | Minor + Patch → 1.x.x | Common default                 |
| `*`    | `"*"`      | Any version           | Not safe; use for testing only |



