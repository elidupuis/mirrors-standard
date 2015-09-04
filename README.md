# pre-commit standard mirror

Mirror of `standard` package for pre-commit.

For pre-commit: see https://github.com/pre-commit/pre-commit

For standard: see https://github.com/feross/standard


### Using standard with pre-commit

Add this to your `.pre-commit-config.yaml`:

    -   repo: git://github.com/elidupuis/pre-commit-hooks
        sha: ''  # Use the sha you want to point at
        hooks:
        -   id: standard
