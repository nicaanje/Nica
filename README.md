# Gradient CLI in Python

A simple Python script that prints gradient-colored text in the terminal.

## Install

```bash
pip install rich rich-gradient
```

## Usage

```bash
python main.py
```

## Example

```python
from rich_gradient import print_gradient

print_gradient("Hello, Gradient!", colors=["#ff0000", "#ffff00", "#00ff00", "#00ffff", "#0000ff"])
```
