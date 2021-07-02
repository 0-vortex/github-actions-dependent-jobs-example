# github-actions-dependent-jobs-example

[![Commitizen friendly](https://img.shields.io/badge/commitizen-friendly-brightgreen.svg)](http://commitizen.github.io/cz-cli/)

TL;DR: It's not a new job if you need the same build context.

## Requirements

In order to run the project from a container we need `node>=16` and `npm>=7` installed on our development machines.

## Installation

Clone the package via `git`:

```shell
git clone git@github.com:0-vortex/github-actions-dependent-jobs-example.git
```

Go into the cloned repository and install `node` dependencies:

```shell
npm ci
```

## How to use

To develop locally just run:

```shell
npm start
```

## Contributing

This repository uses `husky` with pre-commit and message hooks. All you need to do after staging some files is to run:

```shell
npm run push
```
