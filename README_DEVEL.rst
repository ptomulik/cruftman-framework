CruftMan Framework - developer's notes
======================================

Starting from scratch
---------------------

If you're just cloned the repo, run the following script

.. code:: shell

   ./bootstrap-dev

this will download/install localy (in the project tree):

- composer_ - for adding/removing php components,
- docker-compose_ - for running multi-container docker applications,

Requirements
------------

All php extensions required by laravel installer should be installed, for
example, at the time of this writting (2018-11-29) zip extension is required:

.. code:: shell

   sudo apt-get install php-zip

.. _composer: https://getcomposer.org/
.. _docker-compose: https://docs.docker.com/compose/

.. <!--- vim: set expandtab tabstop=2 shiftwidth=2 syntax=rst: -->
