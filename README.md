# Welcome to MkDocs

[![Documentation Status](https://readthedocs.org/projects/example-mkdocs-basic/badge/?version=latest)](https://example-mkdocs-basic.readthedocs.io/en/latest/?badge=latest)

For full documentation visit [mkdocs.org](https://www.mkdocs.org).

## Commands

* `mkdocs new [dir-name]` - Create a new project.
* `mkdocs serve` - Start the live-reloading docs server.
* `mkdocs build` - Build the documentation site.
* `mkdocs -h` - Print help message and exit.

# Example Project usage

This project has a standard MkDocs layout which is built by Read the Docs almost the same way that you would build it locally (on your own laptop!).

You can build and view this documentation project locally - we recommend that you activate [a local Python virtual environment first](https://packaging.python.org/en/latest/guides/installing-using-pip-and-virtual-environments/#creating-a-virtual-environment):

```console
# Install required Python dependencies (MkDocs etc.)
pip install -r docs/requirements.txt

# Run the mkdocs development server
mkdocs serve
```

$$
\mathbb{E}[x] = \int_x x f(x) dx
$$

Using the example in your own project
-------------------------------------

If you are new to Read the Docs, you may want to refer to the [Read the Docs User documentation](https://docs.readthedocs.io/).

If you are copying this code in order to get started with your documentation, you need to:

1. place your `docs/` folder alongside your Python project. If you are starting a new project, you can adapt the `pyproject.toml` example configuration.
1. use your existing project repository or create a new repository on Github, GitLab, Bitbucket or another host supported by Read the Docs.
1. copy `mkdocs.yml`, `.readthedocs.yaml` and the `docs/` folder into your project.
1. customize all the files, replacing example contents.
1. Rebuild the documenation locally to see that it works.
1. *Finally*, register your project on Read the Docs, see [Importing Your Documentation](https://docs.readthedocs.io/en/stable/intro/import-guide.html).


Read the Docs tutorial
----------------------

To get started with Read the Docs, you may also refer to the [Read the Docs tutorial](https://docs.readthedocs.io/en/stable/tutorial/). It provides a full walk-through of building an example project similar to the one in this repository.
