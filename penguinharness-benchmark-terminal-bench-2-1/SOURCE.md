# Terminal-Bench 2.1 sources

- Upstream: Terminal-Bench 2.1, https://github.com/harbor-framework/terminal-bench-2-1 (Apache-2.0)
- Pinned: commit `12b7565679ce5006230b820666353673a133db93`
- Published dataset: the Harbor Hub dataset `terminal-bench/terminal-bench-2-1`, whose per-task digests are recorded in `dataset.toml`
- Images are referenced by the tag upstream wrote in `task.toml` (`alexgshaw/<task>:<tag>`), not by digest: Terminal-Bench publishes its environment images under a contributor namespace with build-date tags, and a pull resolves them to a mutable manifest. Record the digest of a measured run from `docker image inspect` if a score needs to be pinned further.

The task checkout uses the Git submodule at `12b7565679ce5006230b820666353673a133db93`; the [membership list](tasks.txt) has all 89 IDs.
