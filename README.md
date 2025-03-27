# Test Generator Action

This repository demonstrates a GitHub Action that automatically generates test files.

## How it Works

1. When code is pushed to the `main` branch, the action is triggered
2. The action pulls a custom Docker image from GitHub Container Registry (GHCR)
3. The Docker container generates a simple test file
4. A new branch (`test/example-test-branch`) is created
5. The test file is committed and pushed to the new branch
6. A pull request is created to merge the new test into `main`

## Setup

- Push a new commit to the `main` branch to trigger the workflow.

Enjoy automatic test generation via **Docker & GitHub Container Registry (GHCR)**! 🚀
