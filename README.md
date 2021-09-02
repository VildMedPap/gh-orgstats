# gh-orgstats

## Description
Organisation specific extension for `gh cli` to retrieve different statistics

## Install
```sh
gh extension install VildMedPap/gh-orgstats
```

## Usage
General usage

```sh
# gh orgstats [flags]
```

Get a single statistic from an organisation

```sh
gh orgstats --org cli --stats repos
```

Get a single statistic from an organisation with very plain output (only the number)

```sh
gh orgstats --org cli --stats repos --plain
```

Get multiple statistics from an organisation and output as json

```sh
gh orgstats --org cli --stats open_issues,closed_issues --json
```

Get _all_ statistics from an organisation and output as json

```sh
gh orgstats --org cli --json
```

## Help
```sh
gh orgstats --help
```

## Issues and Feature Request
Any help or feedback are very welcome! 👋🏼

- https://github.com/VildMedPap/gh-orgstats/issues
