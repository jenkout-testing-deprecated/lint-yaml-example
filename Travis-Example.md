# Homebrew

## Travis input

```yaml
homebrew:
  packages:
  - cmake
  casks:
  - google-chrome
```

Or

```yaml
homebrew:
- cmake
```

### Transformed Github Action

```yaml
run: |-
  brew install cmake
  brew install google-chrome
```

### Unsupported Options

- brewfile
