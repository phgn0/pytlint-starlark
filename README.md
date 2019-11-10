# Pylint-starlark

Use pylint for Starlark files, by doing an AST transform of load() calls into python import statements.

Use it by running `pylint-starlark file.star`, which internally calls `pylint` with the `pylint-starlark-plugin` plugin enabled.
