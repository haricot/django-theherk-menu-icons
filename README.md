TheHerk Menu Icons
==================

TheHerk Menu Icons is a django CMS navigation modifier that allows attaching icons to menu nodes. These icons can be: a link to an external icon resource, an uploaded icon image file, or by using a class to call a Font Awesome icon.

Due to a dramatic change in the process for modifying the page model in django CMS, TheHerk Menu Icons v1.3 was the last version that supported less than django CMS v3.

Version 2.0.0 support django CMS 3
-------------------------

TheHerk Menu Icons has been upgraded to support django CMS v3. Version 2.0.0 now supports adding via the cmstoolbar on the frontend. This has been tested using Python 3.4.0.

Version 2.0.1 support django CMS >= 3.4.4
-------------------------

+ Add field Menu Class for Link Icon
+ Add frontend editing Menu Icon


Usage
-----

1. Add "menu_icons" to your INSTALLED_APPS

        INSTALLED_APPS = (
            ...
            'menu_icons',
        )

2. Run `python manage.py migrate menu_icons`.

**note** South was necessary for Django before 1.7  - This assumes you are using `south`. If you aren't you can just use `syncdb`.

I have included the template that I use in the menus, so that you can see how it can be implemented.

