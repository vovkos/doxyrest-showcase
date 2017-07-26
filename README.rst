Doxyrest Showcase
=================

Unfortunately, I can't use `Travic CI <https://travis.org>`__ and build documentation of large C++ libraries (like OpenCV), as part of the continuous integration pipeline for `Doxyrest <https://github.com/vovkos/doxyrest>`__ -- it times out during the Sphinx stage.

Therefore, I created this dedicated repository for holding pre-generated HTML pages on the ``gh-pages`` branch.

.. list-table::

	*	- OpenCV
		- `sphinx_rtd_theme <https://vovkos.github.io/doxyrest-showcase/opencv/sphinx_rtd_theme>`__
		- `sphinxdoc <https://vovkos.github.io/doxyrest-showcase/opencv/sphinxdoc>`__
		- vs
		- `original <http://docs.opencv.org/trunk>`__

	*	- POCO Libraries
		- `sphinx_rtd_theme <https://vovkos.github.io/doxyrest-showcase/poco/sphinx_rtd_theme>`__
		- `sphinxdoc <https://vovkos.github.io/doxyrest-showcase/poco/sphinxdoc>`__
		- vs
		- `original <https://pocoproject.org/docs>`__
