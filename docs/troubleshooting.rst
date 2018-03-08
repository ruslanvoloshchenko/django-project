Troubleshooting
=====================================

This page contains some advice about errors and problems commonly encountered during the development of Cookiecutter Django applications.

#. ``project_slug`` must be a valid Python module name or you will have issues on imports.

#. ``jinja2.exceptions.TemplateSyntaxError: Encountered unknown tag 'now'.``: please upgrade your cookiecutter version to >= 1.4 (see # 528_)

.. _528: https://github.com/pydanny/cookiecutter-django/issues/528#issuecomment-212650373
