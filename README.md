# okaysskeptic7u-kit

Validate JSON files and print a normalized form.

Small, dependency-free Python utility package generated for day-to-day file chores.
Standard library only — no third-party imports.

## Install

```bash
pip install -e .
```

## Usage

```bash
python -m okaysskeptic7u_kit.cli --help
```

```python
from okaysskeptic7u_kit.core import Okaysskeptic7uTool

tool = Okaysskeptic7uTool()
print(tool)
```

## Layout

```
okaysskeptic7u_kit/
  __init__.py
  core.py
  cli.py
tests/
  test_core.py
```

## License

MIT © 2026 okaysskeptic7u
