# API reference

This page gives an overview of all functions available in `zenquotespy` package.

## zenquotespy.random()
Get a random quote on each request.
    
Returns:

* `str`: A string of the random quote.

Example:
```py
import zenquotespy

quote = zenquotespy.random()

print(quote)
```

## zenquotespy.today()
Get the quote of the day on each request.

Returns:

* `str`: A string of today's quote.

Example:
```py
import zenquotespy

quote = zenquotespy.today()

print(quote)
```

## zenquotespy.get_bulk_quotes()
Get 50 random quotes on each request.

Returns:

* `list[str]`: A list where each element is a formatted string containing a quote and its author.

Example:
```py
import zenquotespy

quotes = zenquotespy.get_bulk_quotes()

for quote in quotes:
    print(quote)
```

## zenquotespy.image()
Get a random inspirational image on each request.

Args:

* `save_path (str)` (optional): The file path where the image will be saved. Defaults to 'quote_image.jpg' in the current working directory.

Returns:

* `str`: The file path where the image has been saved.

Example:
```py
import zenquotespy

img = zenquotespy.image()

print(f"Quote image successfully saved to {img}")
```

Example with custom path:
```py
import zenquotespy

img = zenquotespy.image("images/quote.jpg")

print(f"Quote image successfully saved to {img}")
```

## zenquotespy.attribution()
Attribution for inspirational quotes provided by <a href="https://zenquotes.io/" target="_blank">ZenQuotes API</a>

Returns:

* `str`: Returns a string *"Inspirational quotes provided by ZenQuotes API (<a href="https://zenquotes.io/" target="_blank">https://zenquotes.io</a>)"*

Example:
```py
import zenquotespy

attrib = zenquotespy.attribution()

print(attrib)
```