==============
pytest-example
==============

.. image:: https://travis-ci.org/paulross/pytest-example.svg?branch=master
    :target: https://travis-ci.org/paulross/pytest-example
    :alt: See Build Status on Travis CI

.. image:: https://ci.appveyor.com/api/projects/status/github/paulross/pytest-example?branch=master
    :target: https://ci.appveyor.com/project/paulross/pytest-example/branch/master
    :alt: See Build Status on AppVeyor

A simple plugin to use with Pytest

----

This `Pytest`_ plugin was generated with `Cookiecutter`_ along with `@hackebrot`_'s `Cookiecutter-pytest-plugin`_ template.


Features
--------

* TODO


Requirements
------------

* TODO


Installation
------------

You can install "pytest-example" via `pip`_ from `PyPI`_::

    $ pip install pytest-example


Usage
-----

* TODO

Contributing
------------
Contributions are very welcome. Tests can be run with `tox`_, please ensure
the coverage at least stays the same before you submit a pull request.

License
-------

Distributed under the terms of the `MIT`_ license, "pytest-example" is free and open source software


Notes
---------

Create a cookiecutter in /Users/paulross/dev/cookiecutter/pytest-example:

  502  . ~/venvs/Cookiecutter_00/bin/activate
  503  which cookiecutter

In the following the plugin is 'example'

  513  cookiecutter https://github.com/pytest-dev/cookiecutter-pytest-plugin
  
(Cookiecutter_00) pauls-mbp-2:cookiecutter paulross$ cookiecutter https://github.com/pytest-dev/cookiecutter-pytest-plugin
You've cloned /Users/paulross/.cookiecutters/cookiecutter-pytest-plugin before. Is it okay to delete and re-clone it? [yes]: 
full_name [Raphael Pierzina]: Paul Ross
email [raphael@hackebrot.de]: apaulross@gmail.com
github_username [hackebrot]: paulross           
plugin_name [foobar]: example
module_name [example]: 
short_description [A simple plugin to use with Pytest]: 
version [0.1.0]: 
pytest_version [3.1.1]: 
Select docs_tool:
1 - mkdocs
2 - sphinx
3 - none
Choose from 1, 2, 3 [1]: 2
Select license:
1 - MIT
2 - BSD-3
3 - GNU GPL v3.0
4 - Apache Software License 2.0
5 - Mozilla Public License 2.0
Choose from 1, 2, 3, 4, 5 [1]: 1
INFO:post_gen_project:Moving files for sphinx.
INFO:post_gen_project:Removing all temporary license files
INFO:post_gen_project:Removing jinja2 macros
(Cookiecutter_00) pauls-mbp-2:cookiecutter paulross$ ls -l

  514  ls -l
  515  cd pytest-example/
  516  ls -l
  517  ls -la
  
 
In Eclipse create an Pydev project 'pytest-example'. 

In /Users/paulross/dev/cookiecutter/pytest-example:

  518  cp -r * ~/Documents/workspace/pytest-example/
  519  ls -la ~/Documents/workspace/pytest-example/

In ~/Documents/workspace/pytest-example/ create a venev, install and run tests:  

  501  cd ~/Documents/workspace/pytest-example/
  502  which python3
  503  python3 -m venv --copies ~/venvs/pytest-example_00
  504  . ~/venvs/pytest-example_00/bin/activate
  505  pip list
  506  pip install pytest
  507  pip install pytest-runner
  508  pip list
  509  pwd
  510  ls -l
  511  vi setup.py 
  512  ls -l tests/
  513  pytest -vs tests/
  514  grep -nrI europython2015 .
  515  pytest tests/
  516  python setup.py install
  517  pytest tests/
  518  pytest -vs tests/





Issues
------

If you encounter any problems, please `file an issue`_ along with a detailed description.

.. _`Cookiecutter`: https://github.com/audreyr/cookiecutter
.. _`@hackebrot`: https://github.com/hackebrot
.. _`MIT`: http://opensource.org/licenses/MIT
.. _`BSD-3`: http://opensource.org/licenses/BSD-3-Clause
.. _`GNU GPL v3.0`: http://www.gnu.org/licenses/gpl-3.0.txt
.. _`Apache Software License 2.0`: http://www.apache.org/licenses/LICENSE-2.0
.. _`cookiecutter-pytest-plugin`: https://github.com/pytest-dev/cookiecutter-pytest-plugin
.. _`file an issue`: https://github.com/paulross/pytest-example/issues
.. _`pytest`: https://github.com/pytest-dev/pytest
.. _`tox`: https://tox.readthedocs.io/en/latest/
.. _`pip`: https://pypi.python.org/pypi/pip/
.. _`PyPI`: https://pypi.python.org/pypi
