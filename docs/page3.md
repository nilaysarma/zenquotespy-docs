# Page 3

For full documentation visit [mkdocs.org](https://www.mkdocs.org).

Open <a href="https://www.mkdocs.org" target="_blank">mkdocs.org</a> in new tab.

## Commands

* `mkdocs new [dir-name]` or `mkdocs new .` - Create a new project.
* `mkdocs serve` - Start the live-reloading docs server.
    * `mkdocs serve -a localhost:8080` - for me.
* `mkdocs build` - Build the documentation site.
* `mkdocs -h` - Print help message and exit.

[Getting started](getting-started.md){ .md-button .md-button--primary }

## Project layout

    mkdocs.yml    # The configuration file.
    docs/
        index.md  # The documentation homepage.
        ...       # Other markdown pages, images and other files.

## Code Annotation Examples

### Codeblocks

Some `code` goes here

### Plain codeblocks

A plain codeblock:

```
from isoddeven import isoddeven

# Example for codeblock
print(isoddeven.isodd(2))
```

#### Code for a specific language

Some more code with the `py` at the start:

```py
from isoddeven import isoddeven

# Example for codeblock
print(isoddeven.iseven(2))
```

#### With title

```py title="main.py"
from isoddeven import isoddeven

# Example for codeblock
print(isoddeven.state(2))
```

#### With line numbers
```py linenums="1"
from isoddeven import isoddeven

# Example for codeblock
print(isoddeven.state(2))
```

#### Highlight lines
```py hl_lines="1 4"
from isoddeven import isoddeven

# Example for codeblock
print(isoddeven.state(1))
```

## Icons and Emojis

### Icons
:fontawesome-brands-twitter:{ .twitter }

:octicons-heart-fill-24:{ .heart }

### Emojis
:smile:

:fontawesome-regular-face-laugh-wink: