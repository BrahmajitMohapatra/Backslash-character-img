# Backslash-character-img

We know that, strings in Python can be defined using either single or double quotations. They are functionally equivalent.
```
x = 'Pluto is a planet'
y = "Pluto is a planet"
x == y
```
> True

Double quotes are convenient if your string contains a single quote character (e.g. representing an apostrophe).

Similarly, it's easy to create a string that contains double-quotes if you wrap it in single quotes:
```
print("Pluto's a planet!")
print('My dog is named "Pluto"')
```
>Pluto's a planet!
>My dog is named "Pluto"

If we try to put a single quote character inside a single-quoted string, Python gets confused:

`'Pluto's a planet!**'**`
>  File "<ipython-input-3-a43631749f52>", line 1
>    'Pluto's a planet!'
>          ^
>SyntaxError: invalid syntax


- We can fix this by "escaping" the single quote with a ***backslash***.
``'Pluto**\**'s a planet!'``
>"Pluto's a planet!"
