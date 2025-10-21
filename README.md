# Tillicum Slurm Tutorial

## Overview

High-performance computing (HPC) clusters like **Tillicum** use a **job scheduler** to manage and optimize the allocation of compute resources. A scheduler coordinates how and when jobs are executed across available CPUs, GPUs, memory, and nodes, ensuring efficient and fair use of the system.

**Slurm** (Simple Linux Utility for Resource Management): the job scheduler used across Hyak clusters, including Tillicum. It handles job submission, resource allocation, and queueing, enabling thousands of users to share the cluster efficiently. For detailed reference, visit the [Slurm documentation](https://slurm.schedmd.com/documentation.html).

Tillicum is a **GPU-only** cluster designed for compute- and AI-intensive workloads. All jobs must request at least one GPU using the `--gpus` option in Slurm.

🎯 **By completing this tutorial, you’ll learn how to:**
- Submit and run interactive and batch jobs with Slurm
- Understand QOS (Quality of Service) and resource billing on Tillicum
- Monitor job status and resource usage
- Write Bash scripts to set up your workflows
- Launch array jobs for parallel workloads

## Repository Structure

Each topic in this tutorial is contained in its own Markdown file for easy navigation:

| Section | Description |
| :- | :- |
| [01-scheduling-jobs.md](./01-scheduling-jobs.md) | Introducing Slurm basics for scheduling interactive and batch jobs |
| [02-monitoring-resource.md](./02-monitoring-resource.md) | Understanding usage accounting and job monitoring tools |
| [03-bash-scripts.md](./03-bash-scripts.md) | Writing and using Bash scripts to automate your workflows |
| [04-job-arrays.md](./04-job-arrays.md) | Leveraging job arrays for large-scale or parameter-sweep tasks |
| [05-task.md](./05-task.md) | Hands-on exercise: submit and monitor your own jobs on Tillicum |

## Introduction Video

A link to the recording of the October 22, 2025 Tillicum Slurm workshop will be added here when available.

## Feedback

We’d love your feedback to help improve this tutorial and future Tillicum trainings. After completing the tutorial or attending the workshop, please take a moment to fill out our [feedback form]().

## Additional Resources

- [Tillicum Documentation](https://hyak.uw.edu/docs/tillicum/)
- [Slurm Documentation](https://slurm.schedmd.com/documentation.html)
- Previous Hyak Slurm:
  - [Basic Slurm](https://hyak.uw.edu/docs/hyak101/basics/syllabus_slurm)
  - [Advanced Slurm](https://hyak.uw.edu/docs/hyak101/basics/syllabus_advanced)