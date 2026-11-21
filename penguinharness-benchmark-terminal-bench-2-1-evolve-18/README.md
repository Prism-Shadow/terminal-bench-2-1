# Terminal-Bench 2.1 evolve 18

The [upstream release](https://github.com/harbor-framework/terminal-bench-2-1/tree/12b7565679ce5006230b820666353673a133db93) provides the task environments, instructions, time limits and verifiers. [tasks.txt](tasks.txt) lists the 18 members of this directory.

The RRSI training sample uses seed 42. Its `tasks/` directory links only these 18 tasks to the pinned 2.1 release.

Follow the [checkout instructions](../README.md) and the configuration in the Evaluation Center Case.

From the data repository root, validate the 18-task job with `uvx --from harbor==0.23.0 harbor run -c penguinharness-benchmark-terminal-bench-2-1-evolve-18/job.yaml --dry-run`. The job defaults to Harbor’s no-op agent.
