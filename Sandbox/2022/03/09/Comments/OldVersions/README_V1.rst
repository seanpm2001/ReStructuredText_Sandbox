
----

Sandbox test for ReStructuredText source code blocks
====


GitAttributes simple
-----------------

::

*.rst linguist-detectable=true
*.rst linguist-documentation=false

::

Advanced version
-----------------

::

    # ReStructuredText (*.rst)
    *.rst linguist-detectable=true
    *.rst linguist-documentation=false

::

----

Don't know why this happens

----

Syntax highlighting
====

>>> # This is a comment
>>> print("Hello World")
>>> x = int(1)
>>> while (x == 1):
>>>   print("Recursion")
>>> else:
>>>   print("No recursion")

Source code for this example directly below, no need to view the source of the file

::

>>> # This is a comment
>>> print("Hello World")
>>> x = int(1)
>>> while (x == 1):
>>>   print("Recursion")
>>> else:
>>>   print("No recursion")

::

----

..
  Comment block
..

  ..
    Indented comment block
  ..

----

**File version:** ``1 (2022, Wednesday, March 9th at 4:23 pm)``

----
