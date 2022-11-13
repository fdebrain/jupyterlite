# JupyterLite Demo

[![lite-badge](https://jupyterlite.rtfd.io/en/latest/_static/badge.svg)](https://jupyterlite.github.io/demo)

JupyterLite is a JupyterLab distribution that runs entirely in the browser .

## ✨ Try it in your browser ✨

➡️ **https://fdebrain.github.io/jupyterlite/**

![github-pages](https://user-images.githubusercontent.com/591645/120649478-18258400-c47d-11eb-80e5-185e52ff2702.gif)

## Use additional Python packages

JupyterLite comes with a few pre-installed packages such as Numpy, Pandas, Scikit-Learn, Scipy, etc...  

You can install additional packages within the Jupyter Notebook: 
```python
import piplite
await piplite.install("package_name")
```

Note: Packages without a wheel available on PyPI might be incompatible. [[learn more]](https://pyodide.org/en/stable/usage/packages-in-pyodide.html)

## Further Information and Updates

For more info, keep an eye on the JupyterLite documentation:

- How-to Guides: https://jupyterlite.readthedocs.io/en/latest/howto/index.html
- Reference: https://jupyterlite.readthedocs.io/en/latest/reference/index.html
