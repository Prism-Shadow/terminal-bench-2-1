# Terminal-Bench 2.1

- [Terminal-Bench 2.1](penguinharness-benchmark-terminal-bench-2-1/), 89 tasks.
- [Terminal-Bench 2.1 evolve 18](penguinharness-benchmark-terminal-bench-2-1-evolve-18/), 18 tasks.

## Checkout

Check out the data commit named in the Case, then initialize the pinned upstream release from the root of this repository.

```sh
git submodule update --init upstream
```

The Git submodule records the [official release](https://github.com/harbor-framework/terminal-bench-2-1/tree/12b7565679ce5006230b820666353673a133db93) at `12b7565679ce5006230b820666353673a133db93`. The full release is under `penguinharness-benchmark-terminal-bench-2-1/tasks/`. For the 18-task sample, use `penguinharness-benchmark-terminal-bench-2-1-evolve-18/tasks/`. The data checkout and the [shared Penguin adapter](https://github.com/Prism-Shadow/penguin-harness-benchmark/tree/8f6443919789488fb275deead8fc322191284db7/agents) have independent revisions. Set `ADAPTER_DIR` to the absolute path of `agents/` at the adapter revision specified in the Case.
