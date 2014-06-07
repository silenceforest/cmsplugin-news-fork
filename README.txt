ALPHA

Name: cmsplugin-news fork
Description: A news plugin for django-cms
Download: https://github.com/silenceforest/cmsplugin-news-fork

Requirements:
- django-cms-2.1.*

Setup
- make sure requirements are installed and properly working
- add cmsplugin_news to python path
- add 'cmsplugin_news' to INSTALLED_APPS
- run 'python manage.py syncdb'
- Create a page in cms and in the 'advanced settings' section of the admin for that page, for 'Navigation extenders' select 'news navigation' and for 'application' select 'news' (Restart of the server required due to caching!)
- Create the propper templates for your site, the ones included with the app are VERY basic

Suggestion:
To avoid confusion add a "application" template to the CMS which is like other templates but without any placeholders.
That way users won't get tempted to fill the placeholders and then complain they don't show up ;-)