Selventa Knowledge
==================
Updated versions of the Selventa Small and Large Corpus

Licenses
--------
Both the Selvanta Small Corpus and Selventa Large Corpus are distributed under
the Creative Commons Attribution-Non-Commercial-ShareAlike 3.0 Unported
License.

Installation
------------
``selventa_knowledge`` can be installed from [GitHub](https://github.com/cthoyt/selventa-knowledge) with:

.. code-block:: sh

   $ pip install git+https://github.com/cthoyt/selventa-knowledge.git

Usage
-----
The combine graph can be loaded with:

.. code-block:: python

    >>> import selventa_knowledge
    >>> graph = selventa_knowledge.get_graph()

If you need granularity, you can load each graph in a dictionary where
all of the names of the files creating each graph are the keys and the
values are also BEL graphs with:

.. code-block:: python

    >>> import selventa_knowledge
    >>> graphs = selventa_knowledge.get_graphs()
