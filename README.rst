GitHub App Boilerplate
----------------------

A starter webservice for building a GitHub App using gidgethub (v4.1.0+), aiohttp, and
deployment to Heroku.

Heroku Setup
------------


|Deploy|

.. |Deploy| image:: https://www.herokucdn.com/deploy/button.svg
   :target: https://heroku.com/deploy?template=https://github.com/mariatta/github_app_boilerplate


Add the following config vars in Heroku.

``GH_SECRET``: The secret key from your GitHub App

``GH_APP_ID``: The ID of your GitHub App

``GH_PRIVATE_KEY``: The private key of your GitHub App. It looks like:

```
-----BEGIN RSA PRIVATE KEY-----
...somereallylongtext...
-----END RSA PRIVATE KEY-----

```
