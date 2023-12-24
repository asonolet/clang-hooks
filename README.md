clang-hooks
===========

Mirror of `clang-format` and `clang-tidy` packages for pre-commit.

For pre-commit: see https://github.com/pre-commit/pre-commit

For clang-format: see https://github.com/ssciwr/clang-format-wheel

For clang-tidy: see https://github.com/ssciwr/clang-tidy-wheel


### Using clang-hooks with pre-commit

Add this to your `.pre-commit-config.yaml`:

```yaml
- repo: https://github.com/asonolet/clang-hooks
  rev: ''  # Use the sha / tag you want to point at
  hooks:
    - id: clang-format
    - id: clang-tidy
```
