# Django Starter Project by @mrsyafapri

## Important: Change the `SECRET_KEY` in [`settings.py`](core/settings.py)

## Custom User Model

Open the [`users/models.py`](users/models.py) file and change the `User` model to the following:

```python
class User(AbstractUser):
    # other user fields
```

Open the [`users/admin.py`](users/admin.py) file and change the `UserAdminConfig` class to the following:

```python
class UserAdminConfig(UserAdmin):
    # other user admin fields
```

## Migrate Database

Run `python manage.py makemigrations` and `python manage.py migrate` to update the database.

## Create Admin User

Run `python manage.py createsuperuser` to create an admin user.

## Start Project

Run `python manage.py runserver` to start the project.

## Please give star to this project if you like it or fork it if you want to improve it.