<!-- omit in toc -->
# Hands-on Exercise: 

This hands-on exercise will guide you through the essential steps for using Tillicum:

You’ll create a working directory, start an interactive job, load modules, build a Conda environment, run Python code, submit a batch job.

> 🎯 **GOAL:** Learn how to build and run a simple workflow on Tillicum — from terminal to Jupyter.

**Overview**

- [0. Preparation](#0-preparation)
  - [Log in to `tillicum`](#log-in-to-tillicum)
  - [Create Your Working Directory](#create-your-working-directory)
- [1.](#1)

## 0. Preparation

### Log in to `tillicum`

```bash
# Below replace the word "UWNetID" with your UW NetID.
ssh UWNetid@tillicum.hyak.uw.edu
```

### Create Your Working Directory

For the following exercises, we will create a working directory for this tutorial. We recommend starting your working directory in a filesystem location where you have a large storage quota, not in your Home directory (limit 10GB; [Click here to learn more about storage limits on Tillicum](https://hyak.uw.edu/docs/tillicum/storage#user-storage)). For this demonstration, we will create a working directory to use Tillicum's free community storage under `/gpfs/scrubbed`.

First navigate to /gscratch/scrubbed:

```bash
cd /gpfs/scrubbed/
```

Create and navigate to your own directory in `/gpfs/scrubbed`:

```bash
mkdir $USER
cd $USER
```

clone the training repository to your directory:

```bash
git clone https://github.com/UWrc/tillicum-slurm.git
```

> 📝 **NOTE:** The `$USER` variable automatically expands to your username.

## 1.