================
Sandbox title
================

Header order
================

Header 1
=========

Header 1.1
-----------

Header 1.1.1
~~~~~~~~~~~~


.. _warningboxes:

Box things
================

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

.. versionchanged:: 1.3
   Something changed.

.. sidebar:: Optional Sidebar Title
   :subtitle: Optional Sidebar Subtitle

   Subsequent indented lines comprise
   the body of the sidebar, and are
   interpreted as body elements.

.. deprecated:: 1.2
   Old thing removed.

Tabs
================

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
================

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
================

Some text goes here [#Some-ref]_. 

.. [#Some-ref] Some text also here that is a footnote.

Footnotes2
=================

Lorem ipsum [#f1]_ dolor sit amet ... [#f2]_

.. rubric:: Footnotes

.. [#f1] Text of the first footnote.
.. [#f2] Text of the second footnote.

Citations 
=================

Lorem ipsum [Ref]_ dolor sit amet.

.. [Ref] Book or article reference, URL or whatever.

References 
=================

Reference using the name from the link. :ref:`warningboxes`

Reference using changed name. :ref:`Test <warningboxes>`


Interlinks
=================


Using doc
-----------

* Link to whole pages on a different level - ``:doc:test/sometest`` - :doc:`test/sometest`

* Link to a section in a page, on a different level - ``:doc:test/sometest#header-1`` - :doc:`test/sometest#header-1`

* Link to a whole file on the same level - ``:doc:hoverxref`` - :doc:`hoverxref`

* Link to a section in a page on the same level. - :doc:`hoverxref#section 1`

Using ref
-----------

* Link to whole pages on a different level - :ref:`hoverxref:hoverxref`

* Link to a section in a page, on a different level - :ref:`hoverxref:section 1`

* Link to a whole file on the same level - :ref:`docs/test/sometest:some test`

* Link to a section in a page on the same level. - :ref:`docs/test/sometest:header 1`

* Testing = :ref:`docs/ideas/music/lyrics/littlebustersfull:little busters (full)zzzzz Little Busters (full)zzzzz`

* Testing2 = :ref:`docs/ideas/music/lyrics/littlebustersfull:little busters (full)zzzzz`


Definition lists
=================

what
  Definition lists associate a term with
  a definition.

how
  The term is a one-line phrase, and the
  definition is one or more paragraphs or
  body elements, indented relative to the
  term. Blank lines are not allowed
  between term and definition.


Glossary 
=================

.. glossary::

   aaaaaaaaaaa
      bbbbbbbbbbbbbbb.

   cccccc
      ddddddddd.


Hover tool-tip
=================

This will :hoverxref:`show a tooltip <hoverxref:hoverxref>` in the linked words to ``hoverxref``. - This shows the whole doc.

This :hoverxref:`tool tip <hoverxref:section 1>` will show only a section though. And will show sub sections. - it shouldn't show section 2.

This should only show a section with no sub sections. - :hoverxref:`tool tip <hoverxref:Sub-section 1>` - it shouldn't show section 2.