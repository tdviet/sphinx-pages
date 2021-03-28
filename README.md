# Sphinx Pages

This GitHub Action build html documentation by Sphinx, and push to branch gh-pages. 
It is based on [seanzhengw/sphinx-pages](https://github.com/seanzhengw/sphinx-pages).

Changes (in comparison with the original repository):
- including additional tools (build-essential, python3-dev) for building, see [Dockerfile](https://github.com/tdviet/sphinx-pages/blob/master/Dockerfile#L10)
- default document directory to /docs, see [entrypoint.sh](https://github.com/tdviet/sphinx-pages/blob/master/entrypoint.sh#L117)

See [seanzhengw/sphinx-pages](https://github.com/seanzhengw/sphinx-pages) for full usage.

## Example 

See [https://github.com/tdviet/fedcloudclient/blob/master/.github/workflows/sphinx-pages.yml](https://github.com/tdviet/fedcloudclient/blob/master/.github/workflows/sphinx-pages.yml) for 
workflow and [https://fedcloudclient.fedcloud.eu/](https://fedcloudclient.fedcloud.eu/) for 
output.
