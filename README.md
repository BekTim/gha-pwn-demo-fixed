# GitHub Actions Security Demo (Vulnerable)

> ⚠️ WARNING: This repository is intentionally vulnerable.
> It is for education only. Do not copy these workflows into real projects.

## About
This is a demo for the NYU Software Supply Chain Security course.
It shows how badly configured GitHub Actions workflows can be attacked.

## What is inside
- `.github/workflows/` — vulnerable workflows:
  - `pull_request_target` that runs code from a fork
  - script injection through the pull request title

## Secrets
The secret `DEMO_SECRET` is fake. There are no real tokens in this repo.

## Fixed version
The secure version of the same workflows: `gha-pwn-demo-fixed` (coming soon)

## Authors
- @dh2591 — attack
- @BekTim — defense
