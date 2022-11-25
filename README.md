# curator-opensearch

This project is a fork of https://github.com/elastic/curator. The main motivation behind its creation was the lack of compatibility between elastic/curator and [OpenSearch](https://aws.amazon.com/blogs/opensource/introducing-opensearch/). 
The original curator worked well with OpenDistro. However, when trying to switch to OpenSearch, we found that elastic/curator does not support OpenSearch.

To ensure compatibility with OpenSearch, we used [`opensearch-py`](https://opensearch-project.github.io/opensearch-py/) — a community-driven, Open Source fork of `elasticsearch-py`.


## Curator API Documentation

Curator ships with both an API and a wrapper script (which is actually defined
as an entry point). The API allows you to write your own scripts to accomplish
similar goals, or even new and different things with the Curator API _and
the Elasticsearch Python API_.

* Curator API: http://curator.readthedocs.io/

* OpenSearch Python API: https://github.com/opensearch-project/opensearch-py/blob/main/USER_GUIDE.md


## Curator CLI Documentation

The [Curator CLI Documentation](http://www.elastic.co/guide/en/elasticsearch/client/curator/current/index.html) is now a part of the document repository at http://elastic.co/guide. 


## Getting Started

The Getting Started guide is avaialble at https://www.elastic.co/guide/en/elasticsearch/client/curator/current/about.html

curator-opensearch can be installed using the pip package manager:
````
$ pip install curator-opensearch
````

Running ``curator --help`` will show usage information.

## Community

Please feel free to reach developers/maintainers and users via [GitHub Discussions](https://github.com/flant/curator-opensearch/discussions) for any questions regarding curator-opensearch.

You're also welcome to follow [@flant_com](https://twitter.com/flant_com) to stay informed about all our Open Source initiatives.

## License

Apache License 2.0, see [LICENSE](LICENSE).
