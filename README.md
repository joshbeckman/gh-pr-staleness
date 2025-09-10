# gh-pr-staleness

A [GitHub CLI extension](https://docs.github.com/en/github-cli/github-cli/creating-github-cli-extensions) that calcluates the staleness (how many commits behind TARGET branch) of a pull request. This is very useful for determining which PRs are actionably mergeable, especially in highly active monorepo or merge-queue environments.

## Installation

Install this GitHub CLI extension using:

```bash
gh extension install joshbeckman/gh-pr-staleness
```

Or with the full URL:

```bash
gh extension install https://github.com/joshbeckman/gh-pr-staleness
```

## Prerequisites

- [GitHub CLI (`gh`)](https://cli.github.com/) must be installed and authenticated

## Usage

```bash
gh pr-staleness <github_pr_url_or_number>
```

### Examples

**View an issue:**
```bash
gh pr-staleness https://github.com/owner/repo/issues/123
```

## Features

### Output Format
The script returns a clean integer output.

## License

This project follows standard open source practices. Check the repository for specific license information.
