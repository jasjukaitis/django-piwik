Django-Piwik
============

A simple app to add the Piwik JS tracking code to your template.


Requirements
------------

 * Django


Installation
------------

Using PyPI you can simply type into a terminal:

    pip install django-piwik

or

    easy_install django-piwik


Configuration
-------------

Add ``piwik`` to the list of ``INSTALLED_APPS`` in your ``settings.py`` file.

Also ``PIWIK_SITE_ID`` (e.g. ``1``) and ``PIWIK_URL`` (e.g. ``'piwik.example.com'``) are required.


In the template, put ``{% load piwik_tags %}`` to the top and add ``{% tracking_code %}`` before the ``</body>`` tag.


That's it. Happy tracking!


Author
------

Copyright 2013 Raphael Jasjukaitis <webmaster@raphaa.de>


Released under the BSD license.
