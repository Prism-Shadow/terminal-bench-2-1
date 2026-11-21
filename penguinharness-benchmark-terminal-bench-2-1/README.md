# Terminal-Bench 2.1

The [upstream release](https://github.com/harbor-framework/terminal-bench-2-1/tree/12b7565679ce5006230b820666353673a133db93) provides the task environments, instructions, time limits and verifiers. [tasks.txt](tasks.txt) lists the 89 members of this directory.

Follow the [checkout instructions](../README.md) and the configuration in the Evaluation Center Case.

From the data repository root, validate the 89-task job with `uvx --from harbor==0.23.0 harbor run -c penguinharness-benchmark-terminal-bench-2-1/job.yaml --dry-run`. The job defaults to Harbor’s no-op agent.

Evaluation Center Case `CASE-038-install-windows-3-11` runs the upstream Harbor task `install-windows-3.11`.
