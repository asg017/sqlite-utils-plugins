# sqlite-utils plugins

A directory of plugins for [sqlite-utils](https://sqlite-utils.datasette.io/).

Here's how to [build a sqlite-utils plugin](https://sqlite-utils.datasette.io/en/stable/plugins.html#building-a-plugin). You can use [this cookiecutter template](https://github.com/simonw/sqlite-utils-plugin) to get started.

- **[sqlite-migrate](https://github.com/simonw/sqlite-migrate)** is an experimental migrations system for managing database changes, built on top of `sqlite-utils` and applied using the `sqlite-utils migrate` command.
- **[sqlite-utils-dateutil](https://github.com/simonw/sqlite-utils-dateutil)** adds date utility SQL functions, such as `select dateutil_parse('3rd november')`.
- **[sqlite-utils-litecli](https://github.com/simonw/sqlite-utils-litecli)** adds an interactive SQLite shell, started using `sqlite-utils litecli data.db`. This provides syntax highlighted SQL and auto-completion against keywords, table and column names plus other features provided by the [litecli](https://github.com/dbcli/litecli) project.
- **[sqlite-utils-shell](https://github.com/simonw/sqlite-utils-shell)** adds a more basic interactive SQLite shell, started using `sqlite-utils shell` for an in-memory database or `sqlite-utils shell data.db` to run against a database file.
- **[sqlite-utils-ml](https://github.com/rclement/sqlite-utils-ml)** by Romain Clement adds a family of functions for training machine learning models and running predictions directly in SQLite.
- Alex Garcia released the following plugins for his [family of SQLite extensions](https://github.com/asg017/sqlite-ecosystem):
  - `sqlite-utils-sqlite-regex`
  - `sqlite-utils-sqlite-path`
  - `sqlite-utils-sqlite-url`
  - `sqlite-utils-sqlite-ulid`
  - `sqlite-utils-sqlite-lines`
  - `sqlite-utils-sqlite-http`
  - `sqlite-utils-sqlite-html`
  - `sqlite-utils-sqlite-jsonschema`
  - `sqlite-utils-sqlite-fastrand`
  - `sqlite-utils-sqlite-vss`

