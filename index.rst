===========================
 Search --- Omeka S Module
===========================

`Search`_ is a module that adds search capabilities to Omeka S.

More precisely, it provides foundations for search-related features that can be
extended by other modules. It can be extended in two ways:

Adapters
   Adapters do the real work of indexing and querying resources. Think of them
   as bridges between Omeka S and a search engine.

Forms
   Forms are responsible for displaying a search form to the user and for
   transforming the user's input into a query understandable by this module.

While this module provides a standard form, it does not provide any adapter. So
in order to use the search features of this module you will need to find and
install a module that implements an adapter.

The `Solr module <https://github.com/biblibre/omeka-s-module-Solr>`_ implements an adapter for the `Solr search engine <https://solr.apache.org/>`_.

.. toctree::
   :hidden:

   installation

.. toctree::
   :hidden:
   :caption: Configuration

   configuration/search-indexes
   configuration/search-pages

.. _Search: https://github.com/biblibre/omeka-s-module-Search
