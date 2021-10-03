# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

#
asdf plugin test vercel-cli https://github.com/sotalbireo/asdf-vercel-cli.git "vercel --help"
```

Tests are automatically run in GitHub Actions on push and PR.
