# pre-commit standard mirror

Mirror of `standard` package for pre-commit.

For pre-commit: see https://github.com/pre-commit/pre-commit

For standard: see https://github.com/feross/standard

###  ATTN: I just broke SemVer :astonished: :scream:
With f6052bc3c8b2257fc05536574b71e4b897ecea91 I used [pre-commit-maker](https://github.com/pre-commit/pre-commit-mirror-maker) to mirror every release of `standard`. If you were used an old sha and things broke, **I'm sorry**. Just grab the most recent one for your `pre-commit-config.yaml` and you'll be good to go.

### Using standard with pre-commit

Add this to your `.pre-commit-config.yaml`:

    -   repo: git://github.com/elidupuis/pre-commit-hooks
        sha: ''  # Use the sha you want to point at
        hooks:
        -   id: standard
