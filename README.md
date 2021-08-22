# python-flask-pong

Simple Flask project that responds with text `pong` to requests to site's root

## Dependencies

- [Python 3](https://github.com/python/cpython)
- [pip (package installer for python)](https://github.com/pypa/pip)
- [Flask framework](https://github.com/pallets/flask)

## How to run:

- Use Python 3
If you have [pyenv (python version manager)](https://github.com/pyenv/pyenv):
If you have pyenv and feel safe:
```bash
# install Python version, stated in the .python-version file
pyenv install `cat .python-version`
# use Python version, stated in the .python-version file
pyenv shell `cat .python-version`
```
If you have pyenv and feel paranoid:
```bash
# install a particular Python version
pyenv install 3.9.1
# use a particular Python version
pyenv shell 3.9.1
```

- Install Python dependencies:
`pip install -r requirements.txt`

- Run flask:
`flask run`

It will respond with word `pong` when you open http://127.0.0.1:5000/
