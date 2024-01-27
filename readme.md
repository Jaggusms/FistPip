## python -m build
## need to add .pypirc file in home directory with following
- [pypi]
* username = __token__
+ password = pypi-tokenID
## pip install wheel setuptool twine
## python -m twine upload dist/*
