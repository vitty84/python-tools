# python-tools package

Some handy tools to make developing python in Atom even more enjoyable. Goes along really nicely with the [python-autocomplete](https://atom.io/packages/autocomplete-python) package to provide a full python IDE experience in Atom.

Uses [Jedi](https://pypi.python.org/pypi/jedi) internally to provide the following functionality:
* **Show usages**: select the usages of a specific symbol in your file.
This should allow you to quickly refactor/rename variable within your code.
* **Goto definition**: goto to the original definition of the symbol under the cursor.
This will open any corresponding files if they are not already open (even if they form part of the standard library / are installed as a third party module)
* More to come?

Please note that this Atom package is very much a Work In Progress and is far from currently
being perfect! There are a lot of things I will be looking to improve.

If you find anything which does not seem like expected behavior or have any suggestions, feel free to open an [Issue](https://github.com/michaelaquilina/python-tools/issues) on my Github page.
