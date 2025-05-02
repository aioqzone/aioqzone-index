# aioqzone-index

aioqzone package index implemented with GitHub Page, following [PEP 503][pep-0503].

![Dynamic XML Badge](https://img.shields.io/badge/dynamic/xml?url=https%3A%2F%2Faioqzone.github.io%2Faioqzone-index%2Fsimple%2F&query=count(%2F%2Fa)&label=packages)

## Usage

### Poetry

```toml
[[tool.poetry.source]]
name = "aioqzone-index"
url = "https://aioqzone.github.io/aioqzone-index/simple"
priority = "supplemental"
```

### Pip

```sh
pip install <package> -i "https://aioqzone.github.io/aioqzone-index/simple"
```

## Packages

- [qzemoji][qzemoji]
- [aioqzone-feed][aioqzone-feed]
- [pychaosvm][pychaosvm]
- [slide-tc][slide-tc]


[pep-0503]: https://peps.python.org/pep-0503/
[qzemoji]: https://github.com/aioqzone/QzEmoji
[aioqzone-feed]: https://github.com/aioqzone/aioqzone-feed
[pychaosvm]: https://github.com/aioqzone/pychaosvm
[slide-tc]: https://github.com/aioqzone/slide-tc
