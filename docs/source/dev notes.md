# Development Notes

## Documentation

The documentation web pages can be found in `docs/build/html/`. Please open `index.html` to enter the documentation which provides comprehensive descriptions and working examples for each class and function we provided.

The documentation is generated with [Sphinx](https://www.sphinx-doc.org/en/master/index.html). If you are not familiar with it, I would recommend two tutorials for quick-start:

- [A “How to” Guide for Sphinx + ReadTheDocs - sglvladi](https://sphinx-rtd-tutorial.readthedocs.io/en/latest/) provides an easy-to-follow learning curve but omitted some details.
- [Getting Started - Sphinx](https://www.sphinx-doc.org/en/master/usage/quickstart.html) is harder to understand, but provides some essential information to understand the background, which is vital even for very basic configuration.

## Project Code

The project code is stored in `mesh4d/` folder. Under it is a `config/` folder storing configuration variables and some `.py` files, including `utils.py`, `field.py`, `kps.py`, `obj3d.py`, and `obj4d.py`. These are **core modules** for this package. They provide a skeleton for building any downstream analysis task and shall not be modified unless there are very strong reasons to do so.

Other than these, there is an `analysis/` folder haven't been discussed. It's the `mesh4d.analysis` sub-package storing all downstream analysis modules. At current stage, it's not completed and is still under active development.

## Version Control

We use `git` as the version control tool, which is very popular among developers and works seamlessly with GitHub. If you are not familiar with it, I would recommend this tutorial for quick-start: [Git Tutorial - Xuefeng Liao](https://www.liaoxuefeng.com/wiki/896043488029600)

Following is a series of notes that summarise major commands:

- [001-Repository Initialisation](https://dynalist.io/d/98jG0ek7Inu6QtMoBTjP4vj6)
- [002-Local Repository Operation](https://dynalist.io/d/4L3UM0yhrYAriHjoQTptEMBk)
- [003-Remote Repository Operation](https://dynalist.io/d/0NozPTssxkVC8aVebCbNmBkR)

## Dependencies

This project is built upon various open-source packages. All dependencies are listed in `requirements.txt`, please install them properly under a Python 3 environment.