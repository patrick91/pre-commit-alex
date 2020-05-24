alex pre-commit
================

For pre-commit: see https://github.com/pre-commit/pre-commit

For alex: see https://github.com/get-alex/alex


### Using alex with pre-commit

Add this to your `.pre-commit-config.yaml`:

    -   repo: https://github.com/patrick91/pre-commit-alex
        rev: ''  # Use the sha / tag you want to point at
        hooks:
        -   id: alex
