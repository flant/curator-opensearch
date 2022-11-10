# curator-opensearch

Этот проект является форком от https://github.com/elastic/curator. Основная причина его создания - несовместимость elastic/curator и OpenSearch. 
Оригинальный curator хорошо работал с OpenDistro, но когда мы решили переходить на OpenSearch выяснилось, что поддержки OpenSearch у elastic/curator - нет.

Для обеспечиня совместимости с OpenSearch был использован opensearch-py - "is [a community-driven, open source fork](https://aws.amazon.com/blogs/opensource/introducing-opensearch/) of elasticsearch-py."


`Curator API Documentation`_
----------------------------

Curator ships with both an API and a wrapper script (which is actually defined
as an entry point).  The API allows you to write your own scripts to accomplish
similar goals, or even new and different things with the `Curator API`_, and
the `Elasticsearch Python API`_.

.. _Curator API: http://curator.readthedocs.io/

.. _Curator API Documentation: `Curator API`_

.. _Elasticsearch Python API: http://elasticsearch-py.readthedocs.io/


`Curator CLI Documentation`_
----------------------------

The `Curator CLI Documentation`_ is now a part of the document repository at
http://elastic.co/guide at http://www.elastic.co/guide/en/elasticsearch/client/curator/current/index.html

.. _Curator CLI Documentation: http://www.elastic.co/guide/en/elasticsearch/client/curator/current/index.html

`Getting Started`_
------------------

.. _Getting Started: https://www.elastic.co/guide/en/elasticsearch/client/curator/current/about.html

See the `Installation guide <https://www.elastic.co/guide/en/elasticsearch/client/curator/current/installation.html>`_
and the `command-line usage guide <https://www.elastic.co/guide/en/elasticsearch/client/curator/current/command-line.html>`_

Running ``curator --help`` will also show usage information.
