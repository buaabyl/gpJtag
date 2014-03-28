Testing...
==================================

Hello world.

.. code-block:: js

    #!js
    alert('hi');

hi

.. code-block:: c

    //!c
    int a = 1;

    int fun(int a, int b)
    {
        return a + b;
    }


still hello world!

*italics*, **bold**

bulleted list\:\:

* This is a bulleted list.
* It has two items, the second
  item uses two lines.

explict numbered list\:\:

1. This is a numbered list.
2. It has two items too.

auto-increase numbered list\:\:

#. This is a numbered list.
#. It has two items too.


###############
H2 Part Markup
###############

******************
H3 Chapter Markup
******************

================
H4 Title Markup
================



- ``#`` with overline, for parts
- ``*`` with overline, for chapters
- ``=`` for sections
- ``-`` for subsections
- ``^`` for subsubsections
- ``"`` for paragraphs

+------------------------+------------+----------+----------+
| Header row, column 1   | Header 2   | Header 3 | Header 4 |
| (header rows optional) |            |          |          |
+========================+============+==========+==========+
| body row 1, column 1   | column 2   | column 3 | column 4 |
+------------------------+------------+----------+----------+
| body row 2             | ...        | ...      |          |
+------------------------+------------+----------+----------+

.. image:: images/google_logo.png

Lorem ipsum [#f1]_ dolor sit amet ... [#f2]_

.. rubric:: Footnotes

.. [#f1] Text of the first footnote.
.. [#f2] Text of the second footnote.
