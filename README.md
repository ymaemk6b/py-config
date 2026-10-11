# py-config

Declarative configuration objects with validation and defaults.

## Why

I kept rewriting the same thirty lines in every project, so I pulled them out.

## Install

```bash
pip install py-config
```

## Usage

```python
from py_config import pyConfig

result = pyConfig("example")
print(result)
```

## Notes

- No runtime dependencies outside the standard library.
- Tested on Python 3.9 and newer.

## License

MIT
