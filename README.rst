==============================
cookiecutter-terraform-module
==============================

.. _Cookiecutter: http://cookiecutter.readthedocs.org
.. _Terraform: https://www.terraform.io/docs/index.html
.. _Terraform Module Registry: https://registry.terraform.io/
.. _publishing modules: https://www.terraform.io/docs/registry/modules/publish.html

This is a `Cookiecutter`_ template for creating a `Terraform`_ module
suitable for inclusion in the `Terraform Module Registry`_.

This project is based on the guidelines specified in
`publishing modules`_.

Template Project Features
-------------------------

.. _APL2 License: https://choosealicense.com/licenses/apache-2.0/

- `APL2 License`_

Template Application Features
-----------------------------

- Creation of a module package with empty required Terraform files
- Automatic inclusion of `APL2 License`_, or any license you specify

Usage
-----

.. _GitHub: https://github.com/QuiNovas/cookiecutter-terraform-module


Install Python requirements for using the template:

.. code-block:: console

    $ python -m pip install --requirement=requirements.txt --user


Create a new project directly from the template on `GitHub`_:

.. code-block:: console

    $ cookiecutter gh:QuiNovas/cookiecutter-terraform_module

Items
-----
- **author_name** The name of the author (you)
- **author_url** The url to your Github account
- **license** The license of your Lambda function
- **license_url** The URL to your license document
- **module_name** The name of your modules
- **provider** The Terraform provider this module is for
