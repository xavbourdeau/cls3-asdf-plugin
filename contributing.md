# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

asdf plugin test cls3 https://github.com/xavbourdeau/asdf-cls3.git "cls3 --version"
```

Tests are automatically run in GitHub Actions on push and PR.
