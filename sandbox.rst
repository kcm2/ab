################
Sandbox title
################

Header order
*************

* ``#`` with overline, for parts
* ``*`` with overline, for chapters
* ``=``, for sections
* ``-``, for subsections
* ``^``, for subsubsections
* ``"``, for paragraphs

.. _warningboxes:

Box things
*************

.. DANGER:: 
    | High voltage!

.. WARNING:: 
   Lewd content? Beware.

.. IMPORTANT:: 
   Something important here.

.. NOTE:: 
    | Something here!

.. ADMONITION::
   Text goes here.

.. CAUTION::
   Text goes here.

.. ERROR::
   Text goes here.

.. HINT::
   Text goes here.

.. SEEALSO::
   Text goes here.


Tabs
*************

.. tabs::

   .. tab:: reStructuredText

      This is on the "reStructuredText" tab.

      .. code-block:: rst

         - :ref:`guides/cross-referencing-with-sphinx:explicit targets`.
         - :ref:`Custom title <guides/cross-referencing-with-sphinx:explicit targets>`.

   .. tab:: MyST (Markdown)

      This is on the "Markdown" tab.

      .. code-block:: md

         - {ref}`guides/cross-referencing-with-sphinx:explicit targets`.
         - {ref}`Custom title <guides/cross-referencing-with-sphinx:explicit targets>`.


Table
*************

.. list-table:: Title
   :widths: 33 33 33
   :header-rows: 1

   * - Romaji
     - Kanji
     - English
   * - Miwataseru basho ni kesa wa tadoritsuku
     - 
     - [english]
   * - Row 2, column 1
     - Row 2, column 2
     - Row 2, column 3

Footnotes
*************

Some text goes here [#Some-ref]_. 

.. [#Some-ref] Some text also here that is a footnote.


Definition lists
*************

what
  Definition lists associate a term with
  a definition.

how
  The term is a one-line phrase, and the
  definition is one or more paragraphs or
  body elements, indented relative to the
  term. Blank lines are not allowed
  between term and definition.

References 
*************

Reference using the name from the link. :ref:`warningboxes`

Reference using changed name. :ref:`Test <warningboxes>`


Glossary 
*************

.. glossary::

   aaaaaaaaaaa
      bbbbbbbbbbbbbbb.

   cccccc
      ddddddddd.