Demo App for Heroku.
====================

Set up Heroku up:

.. code-block::

    heroku config:set BUILDPACK_URL=https://github.com/CHH/heroku-buildpack-php
    git push heroku master

This should install Symfony2 backend app, install and run bower for frontend
dependencies.
