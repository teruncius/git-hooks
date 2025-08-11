# Git Hooks

## Installation

Clone the repository:

```shell
git clone git@github.com:teruncius/git-hooks.git
```

Enable the hooks by executing the following command:

```shell
git config --global --add core.hookspath ~/git-hooks
```

Check if the hooks are set up correctly:

```shell
git config --global --get-all core.hookspath
```

## License

See [LICENSE.md](./LICENSE.md).
