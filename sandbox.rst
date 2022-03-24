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


:Authors:
    Tony J. (Tibs) Ibbs,
    David Goodger

:Version: 1.0 of 2001/08/08
:Dedication: To my father.


Block quotes are just:

    Indented paragraphs,

        and they may nest.