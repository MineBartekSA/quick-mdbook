# Quick mdBook

Quick and simple action for setting up [rust-lang/mdBook](https://github.com/rust-lang/mdBook)

This action runs on any runner with consistent and short execution times (from limited tests, up to 10s).

## Usage

```yaml
- name: Install latest mdBook
  uses: MineBartekSA/quick-mdbook@v1.1
```

You can also use an optional `version` input to specify the target mdBook version you want to install.

```yaml
- name: Install mdBook v0.4.21
  uses: MineBartekSA/quick-mdbook@v1.1
  with:
    version: 0.4.21
```

You can also use optional `arch` and `clib` inputs to specify the target build architecture and C Library.

```yaml
- name: Install latest mdBook for the aarch64 architecture build on musl
  uses: MineBartekSA/quick-mdbook@v1.1
  with:
    arch: aarch64
    clib: musl
```
