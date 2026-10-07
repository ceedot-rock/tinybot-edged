# Contributing to tinybot-edged

Thanks for helping build the 3x3 fractal self-building frame.

## Ground rules

- The dual license is the one thing that never changes: every contribution is
  distributed under AGPL-3.0-or-later and the Slid Phi Labs Commercial License.
  Do not edit `LICENSE` or `LICENSE.AGPL-3.0`.
- Keep docs honest: if the README describes something, it should be true of
  the code in this repo.

## Quick checks

CI runs the audited-checks workflow on every pull request (license metadata,
README badges, secrets scan). You can run the same checks locally before you
push:

```sh
test -f LICENSE && test -f LICENSE.AGPL-3.0 && echo "license files OK"
grep -q "audited-checks.yml/badge.svg" README.md && echo "badges OK"
```

## Opening a pull request

1. Fork and branch from `main`.
2. Keep the diff focused; one logical change per pull request.
3. Use the pull request template and tick every check box.
4. Wait for CI to go green before asking for review.

## Licensing

tinybot-edged is dual-licensed (AGPL-3.0-or-later or the Slid Phi Labs
Commercial License; see LICENSE). By contributing you agree your contribution
may be distributed under both.
