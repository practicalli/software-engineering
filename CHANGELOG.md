# Changelog

# Unreleased

## Changed

dev: latest github actions via `make dependencies-update`

| :file                                          | :name                   | :current | :latest |
|------------------------------------------------|-------------------------|----------|---------|
| .github/workflows/changelog-check.yaml         | actions/checkout        | v5       | v6.0.2  |
| .github/workflows/megalinter.yaml              | actions/checkout        | v5       | v6.0.2  |
|                                                | actions/upload-artifact | v4       | v7.0.1  |
| .github/workflows/publish-book.yaml            | actions/cache           | v4       | v5.0.4  |
|                                                | actions/checkout        | v5       | v6.0.2  |
| .github/workflows/scheduled-version-check.yaml | actions/checkout        | v5       | v6.0.2  |



## Added
- mkdocs: google analytics property identity
- dev: standard GitHub workflow and MkDocs configuration
- dev: url and path exclusions for spell lychee url check in megalinter
- dev: `a` & `img` html elements allowed in markdown
- dev: ci scheduled stale issue & pr check (monthly)
