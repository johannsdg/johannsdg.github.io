# Offline Documentation

## MkDocs

These documentation pages for Johann were created with [MkDocs] (https://www.mkdocs.org/).
As such, they can be cloned and taken with you in situations where you may not have internet access.
Note: This requires python and the mkdocs python library to function.

To host the documentation locally:

* Clone the [johannsdg repo](https://github.com/johannsdg/johannsdg.github.io.git) and move to that directory
``` sh
git clone https://github.com/johannsdg/johannsdg.github.io.git
cd johannsdg.github.io/
```
* Use `pip` to install mkdocs
``` sh
pip install mkdocs
```

* Use `mkdocs` to build the web pages
``` sh
mkdocs build
```

* And finally, use `mkdocs` again to host the site
``` sh
mkdocs serve
```
By default the webpage will be served at `http://http://127.0.0.1:8000/` for more information please see the mkdocs 
[getting started guide](https://docs.readthedocs.io/en/stable/intro/getting-started-with-mkdocs.html) 
