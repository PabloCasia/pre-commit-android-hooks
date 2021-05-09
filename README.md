# pre-commit-android-hooks

Pre-commit hooks for Android development using [pre-commit](http://pre-commit.com/) tool.

## Using pre-commit-android-hooks

Add this to your `.pre-commit-config.yaml`

```yaml
    - repo: https://github.com/PabloCasia/pre-commit-android-hooks
      rev: v1.0.0
      hooks:
      - id: ktlint
```

## Available hooks

- `ktlint`: Runs `ktlintFormat`, requires [ktlint](https://github.com/pinterest/ktlint).
