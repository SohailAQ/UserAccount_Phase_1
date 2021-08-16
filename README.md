## User Accounts Phase-1
### A Starter project for user login-logout and Sign-up in Django.

Django has amazing built-in authentication system which needs to be implemented everytime a new project is started. Implementing the login-logout and Sign-up can sometimes feel redundant. This project aims to provide a basic starter pack for Developers.

The project relies on ``` django.contrib.auth ```  present under ```INSTALLED_APPS``` with implementing 3 base template files.
```
templates/registration/login.html
templates/base.html
templates/signup.html
```

A new app ```accounts``` is added which handles the signup functionality. 