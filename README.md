# dotenv-linter-pre-commit

A pre-commit hook for dotenv-linter

### Using dotenv-linter with pre-commit

```yaml
- repo: https://github.com/allganize/dotenv-linter-pre-commit
  rev: v0.1.0
  hooks:
    - id: dotenv-linter-docker
      files: env_files
      args: [--skip, UnorderedKey, --skip, ExtraBlankLine, --]
```

