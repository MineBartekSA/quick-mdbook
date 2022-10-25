# Quick mdBook

Quick and simple action for setting up [rust-lang/mdBook](https://github.com/rust-lang/mdBook)

This action runs on any runner with consistent and short execution times (from limited tests, up to 10s).

## Usage

```yaml
- name: Install latest mdBook
  uses: MineBartekSA/quick-mdbook@v1
```

You can also use an optional `version` input to specify the target mdBook version you want to install.

```yaml
- name: Install mdBook v0.4.21
  uses: MineBartekSA/quick-mdbook@v1
  with:
    version: 0.4.21
```
