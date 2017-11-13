===================
Sphinx Nameko Theme
===================

Forked from the official `theme <https://github.com/onefinestay/sphinx-nameko-theme>`_ for `nameko <https://github.com/onefinestay/nameko>`_.

**Changes so far:**
- Increase font size to 120%

Nameko theme was originally forked from `Sphinx Readable Theme <https://github.com/ignacysokolowski/sphinx-readable-theme>`_, combined with elements of the `Read The Docs <https://github.com/snide/sphinx_rtd_theme>`_ theme.


Installation and setup
======================

**Make sure the PyPI version of sphinx-nameko-theme is uninstaled.**

Clone repo then install::

    $ git clone https://github.com/AJZ229/sphinx-nameko-theme.git
    
    $ cd sphinx-nameko-theme

    $ python3 setup.py install
    
And add this to your Sphinx ``conf.py``:

.. code-block:: python

    import sphinx_nameko_theme

    html_theme_path = [sphinx_nameko_theme.get_html_theme_path()]
    html_theme = 'nameko'


Example
=======

The official `nameko <https://nameko.readthedocs.org>`_ documentation uses this theme.

License
=======

Sphinx Nameko Theme is licensed under the MIT license.


Changelog
=========

Version 0.0.3
-------------

Add colours to admonitions
Nicer styles for inline literals

Version 0.0.2
-------------

Remove symlink confusing ReadTheDocs

Version 0.0.1
-------------

Initial fork
