## Reuse check

- [ ] Existing BTree/rle/core APIs were checked before adding helpers or public types.
- [ ] Any new helper is justified as non-duplicative (or this is docs/config only).

## Validation

- [ ] `NEW_MOON_MOD=0 moon fmt --check`
- [ ] `NEW_MOON_MOD=0 moon check --deny-warn`
- [ ] Release tests pass for wasm, wasm-gc, js, and native.
- [ ] `git diff --check` passes.

## Public interface drift

- [ ] `moon info` was run in root and `proof/`; generated `.mbti` drift is intentional or absent.

## Proof boundary

- [ ] Proof checks/tests/prove pass; scalar guarantees and documented limitations remain accurate.

## Benchmarks

- [ ] `moon bench --release` was run and any meaningful change is explained.
