# dbt + duckdb + poetry

This repo is simply a slightly different take on the
[jaffle_shop_duckdb](https://github.com/dbt-labs/jaffle_shop_duckdb) repo.

Whereas the original relies on manual dependency and environment management with `venv` and
 `pip` and `requirements.txt` files, this version relies solely on [poetry](https://python-poetry.org/)
for package and environment management.

![](https://i.imgur.com/QDYNC3m.gif)

## sqlfluff + pre-commit
This repo also uses [sqlfluff](https://docs.sqlfluff.com/en/stable/index.html) and
[pre-commit](https://pre-commit.com/) to lint and fix .sql files.

*more head taps*

It even has a [basic sqlfuff lint setup](https://github.com/sqlfluff/sqlfluff-github-actions/tree/main/menu_of_workflows/sunrise_movement)
in a CI pipeline.
