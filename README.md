# django_init_admin
Django admin command to create an admin/admin superuser if no user exists


The main purpose is to init an admin user for the applications you deliver. Your end-user will be able to login with admin (pwd: admin) and manage his users.

# usage 
* Install the command in your python environment:
  ```bash
  pip install django_init_admin_command
  ```
* Include this command in you project settings.py file:
   ```python
   INSTALLED_APPS = [
    # ...
    'init_admin_command',
    # ...
   ```
* Create the admin user in a deploy / install script:
   ```bash
   python manage.py initadmin
   ```
