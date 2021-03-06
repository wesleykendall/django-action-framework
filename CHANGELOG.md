# Changelog
## 1.0.0 (2020-06-25)
### Api-Break
  - Initial release of django-action-framework [Wes Kendall, 8ef57d1]

    django-action-framework (DAF) provides the ability to create actions from
    which a number of different interfaces can be built, including:

    1. Form views, update views, and bulk update views.
    2. Admin object actions, bulk object actions, and model page actions.
    3. DRF object actions.
    4. Wizard for all admin and normal form views.

    DAF is primarily built on top of python-args and django-args, which
    means that ``@arg.validators`` and other ``python-args`` decorators
    will work seamlessly with all DAF views and interfaces.

