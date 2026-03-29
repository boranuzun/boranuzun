#### 👋🏼

```python
# boran.py

# /// script
# requires-python = ">=3.14"
# dependencies = []
# ///

class BoranUzun:

    def __init__(self) -> None:
        self.name      : str       = 'Boran UZUN'
        self.degree    : str       = 'BSc in Business Information Technology'
        self.speaks    : list[str] = ['fr_FR', 'en_US', 'tr_TR']

    def status(self) -> str:
        return 'Open to DevOps / Network & Systems opportunities'

    def __str__(self) -> str:
        return self.name

if __name__ == '__main__':
    me = BoranUzun()
    print(me.status())
```

```console
$ uv run boran.py
Open to DevOps / Network & Systems opportunities
```
