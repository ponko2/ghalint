# Usage

<!-- This is generated by scripts/generate-usage.sh. Don't edit this file directly. -->

```console
$ ghalint --help
NAME:
   ghalint - GitHub Actions linter

USAGE:
   ghalint [global options] [command [command options]]

VERSION:
   1.4.0

COMMANDS:
   run              lint GitHub Actions Workflows
   run-action, act  lint actions
   version          Show version
   help, h          Shows a list of commands or help for one command
   completion       Output shell completion script for bash, zsh, fish, or Powershell

GLOBAL OPTIONS:
   --log-color string          log color. auto(default)|always|never [$GHALINT_LOG_COLOR]
   --log-level string          log level [$GHALINT_LOG_LEVEL]
   --config string, -c string  configuration file path [$GHALINT_CONFIG]
   --help, -h                  show help
   --version, -v               print the version
```

## ghalint run

```console
$ ghalint run --help
NAME:
   ghalint run - lint GitHub Actions Workflows

USAGE:
   ghalint run

OPTIONS:
   --help, -h  show help
```

## ghalint run-action

```console
$ ghalint run-action --help
NAME:
   ghalint run-action - lint actions

USAGE:
   ghalint run-action

OPTIONS:
   --help, -h  show help
```

## ghalint version

```console
$ ghalint version --help
NAME:
   ghalint version - Show version

USAGE:
   ghalint version

OPTIONS:
   --json, -j  Output version in JSON format (default: false)
   --help, -h  show help
```

## ghalint completion

```console
$ ghalint completion --help
NAME:
   ghalint completion - Output shell completion script for bash, zsh, fish, or Powershell

USAGE:
   ghalint completion

DESCRIPTION:
   Output shell completion script for bash, zsh, fish, or Powershell.
   Source the output to enable completion.

   # .bashrc
   source <(ghalint completion bash)

   # .zshrc
   source <(ghalint completion zsh)

   # fish
   ghalint completion fish > ~/.config/fish/completions/ghalint.fish

   # Powershell
   Output the script to path/to/autocomplete/ghalint.ps1 an run it.


OPTIONS:
   --help, -h  show help
```