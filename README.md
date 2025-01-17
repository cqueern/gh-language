# GitHub Language Analyzer
This is an extension to the `gh` command-line tool for analyzing the count of programming languages used in repositories across a GitHub organization. It retrieves a list of repositories and their associated languages, and then aggregates the data to produce a report of language frequency.

# Pre-requisites
1. Install the GitHub CLI: https://github.com/cli/cli#installation

# Installation
To install this extension, run the following command:
```
gh extension install CallMeGreg/gh-language
```

# Usage
Examples:
```
gh language count YOUR_ORG_NAME
```

```
gh language count YOUR_ORG_NAME --limit 1000 --top 20
```

For help, run:
```
gh language -h
```

``` 
Usage:
  language [command]

Available Commands:
  completion  Generate the autocompletion script for the specified shell
  count       Analyze the count of programming languages used in repos across an organization
  help        Help about any command

Flags:
  -h, --help              help for language
  -L, --language string   The language to filter on
  -l, --limit int         The maximum number of repositories to evaluate (default 100)
  -t, --top int           Return the top N languages (default 10)

Use "language [command] --help" for more information about a command.
```

# License
This tool is licensed under the MIT License. See the [LICENSE](https://github.com/CallMeGreg/gh-language/blob/main/LICENSE) file for details.
