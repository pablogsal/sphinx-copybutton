# sphinx-copybutton

[![PyPI](https://img.shields.io/pypi/v/sphinx-copybutton.svg)](https://pypi.org/project/sphinx_copybutton/) | [![Conda Version](https://img.shields.io/conda/vn/conda-forge/sphinx-copybutton.svg)](https://anaconda.org/conda-forge/sphinx-copybutton) | [![Documentation](https://readthedocs.org/projects/sphinx-copybutton/badge/?version=latest)](https://sphinx-copybutton.readthedocs.io/en/latest/?badge=latest)

A small sphinx extension to add a "copy" button to code blocks.

See [the sphinx-copybutton documentation](https://sphinx-copybutton.readthedocs.io/en/latest/) for more details!

![](docs/_static/copybutton.gif)

## Installation

You can install `sphinx-copybutton` with `pip`:

```bash
pip install sphinx-copybutton
```

Or with `conda` via `conda-forge`:

```bash
conda install -c conda-forge sphinx-copybutton
```


## Usage

In your `conf.py` configuration file, add `sphinx_copybutton` to your extensions list.
E.g.:

```python
extensions = [
    ...
    'sphinx_copybutton'
    ...
]
```

When you build your site, your code blocks should now have little copy buttons to their
right. Clicking the button will copy the code inside!

## Customization

If you'd like to customize the look of the copy buttons, you can over-write any of the
CSS rules specified in the Sphinx-CopyButton CSS file ([link](sphinx_copybutton/_static/copybutton.css))

## Development

Development should principally adhere to the [EBP Developer Conventions](https://github.com/executablebooks/.github/blob/master/CONTRIBUTING.md)

Sphinx-Copybutton is [hosted on the pypi repository](https://pypi.org/project/sphinx-copybutton/).
After a release - following the [EBP release instructions](https://github.com/executablebooks/.github/blob/master/CONTRIBUTING.md#releases-and-change-logs) - confirm that the new version of Sphinx-Copybutton [is posted to pypi](https://pypi.org/project/sphinx-copybutton/).
