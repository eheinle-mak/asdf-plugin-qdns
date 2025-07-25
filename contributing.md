# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

#
asdf plugin test qdns https://github.com/eheinle-mak/asdf-qdns.git "q --version"
```

Tests are automatically run in GitHub Actions on push and PR.
