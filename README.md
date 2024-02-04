# read-the-docs

[URL](https://read-the-docs-240204.readthedocs.io/ja/latest/)

## command

~~~
docker run -it -v $(pwd):/docs sphinxdoc/sphinx sphinx-quickstart
docker run -v $(pwd):/docs sphinxdoc/sphinx sphinx-build /docs/source /docs/build
~~~
