# pre-commit-mirrors
Mirror of packages for pre-commit.

For pre-commit: see https://github.com/pre-commit/pre-commit

For standard: see https://github.com/Flet/semistandard

For tslint: see https://github.com/palantir/tslint

### Using semistandard with pre-commit

Add this to your .pre-commit-config.yaml:

-   repo: git://github.com/CardioLogs/pre-commit-mirrors
    sha: ''  # Use the sha you want to point at
    hooks:
    -   id: semistandard
    -   id: tslint
