# skye-db
[![Lang](https://img.shields.io/badge/lang-rust-brightgreen)](https://www.rust-lang.org/) [![Build](https://github.com/kinddevil/skye-db/actions/workflows/ci-workflow.yml/badge.svg)](https://github.com/kinddevil/skye-db/actions) [![Coverage Status](https://coveralls.io/repos/github/kinddevil/skye-db/badge.svg?branch=main)](https://coveralls.io/github/kinddevil/skye-db) [![MIT license](https://img.shields.io/badge/License-MIT-blue.svg)](https://lbesson.mit-license.org/)

A time serials KV database.

## Build and run
### run in local
```
make dev
```
### run in prod
```
make prod
```
### code coverage
Switch to nightly build.
```
cargo install grcov
rustup component add llvm-tools-preview
make cov
```
