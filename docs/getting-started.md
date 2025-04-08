# Getting Started

ZenQuotes Python is a lightweight Python package that provides easy access to motivational and inspirational quotes from the ZenQuotes.io API. This documentation page provides a strong understanding of the functions available in the `zenquotes` package. If you are a python developer, you can contribute through code to this package by creating an issue or a pull request in the [GitHub repository](https://github.com/nilaysarma).

## Installation

ZenQuotes Python is published as a Python package called [zenquotes](https://pypi.org/project/zenquotes) and can be installed with `pip`. It is recommended to create a virtual environment first.

```
pip install zenquotes
```

To update the package use this command:

```
pip install --upgrade zenquotes
```

## Quick usage
Here's a quick example of how to use it.

```py
import zenquotes

quote = zenquotes.random()

print(quote)
```

## What's Next?

Checkout the [API reference](api-reference.md) page next to know more about the functions available in `zenquotes` package.