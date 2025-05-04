# Welcome!

To access simple api, goto [simple](./simple).
For further information about this template, goto [gh-simple-api][gh-simple-api].
For further information about `aioqzone-index`, goto our [repository][repo].

## Using simple index

### poetry

Add this section into `pyproject.toml`:

```toml
[[tool.poetry.source]]
name = "aioqzone-index"
url = "https://aioqzone.github.io/aioqzone-index/simple"
priority = "supplemental"
```

For more information, goto [poetry docs](https://python-poetry.org/docs/repositories/#simple-api-repository).

### uv

```toml
[[tool.uv.index]]
name = "aioqzone-index"
url = "https://aioqzone.github.io/aioqzone-index/simple/"
```

For more information, goto [uv docs](https://docs.astral.sh/uv/configuration/indexes/).

### pip

Install with [index-url](https://pip.pypa.io/en/stable/cli/pip_install/#cmdoption-i):

```sh
pip install <package> -i "https://aioqzone.github.io/aioqzone-index/simple"
```

[gh-simple-api]: https://github.com/aioqzone/gh-simple-api "Implement PEP 503 simple api with GitHub Page."
[repo]: https://github.com/aioqzone/aioqzone-index "aioqzone package index following PEP 503"
