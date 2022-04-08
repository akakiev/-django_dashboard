=========
Dashboard
=========

Dashboard is a Django app of login-protected sales dashboard.
This project demonstrates essential techniques of web development with Django: writing views for HTML, authentication with forms, showing data from the DB, and including static assets.

Detailed documentation is in the "docs" directory.

Quick start
-----------

1. Add "core" to your INSTALLED_APPS setting like this::

    INSTALLED_APPS = [
        ...
        'core',
    ]

2. Include the core URLconf in your project urls.py like this::

    path('core/', include('core.urls')),

3. Run ``python manage.py migrate`` to create the polls models.

4. Start the development server and visit http://127.0.0.1:8000/admin/
   to add a new employee (you'll need the Admin app enabled).

5. Visit http://127.0.0.1:8000/core/ to see the changes in the Dashboard.