# wemake-python-styleguide mirror

Mirror of wemake-python-styleguide for pre-commit.

For pre-commit: see https://github.com/pre-commit/pre-commit

For wemake-python-styleguide: see https://github.com/wemake-services/wemake-python-styleguide


### Using wemake-python-styleguide with pre-commit

Add this to your `.pre-commit-config.yaml`:

```yml
- repo: https://github.com/ammarnajjar/mirrors-wemake-python-styleguide
  rev: ''        # Use the sha / tag you want to point at
  hooks:
    - id: wemake-python-styleguide
```
