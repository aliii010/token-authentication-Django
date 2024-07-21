## Overview

This Django app provides a secure and efficient method for authenticating users via token-based authentication. Upon successful login, the app generates an authentication token and stores it in a cookie, which is then used for subsequent requests to access protected resources. This approach ensures that user sessions are securely maintained without relying on traditional session-based authentication mechanisms

## Endpoints

`api/users/singup/` For creating a user instance.

`api/users/login/` For generating an auth token and store in cookies.

`api/users/logout/` To logout a user by removing the user's auth token in the cookies.

`api/users/me/` To get the current logged in user's information.

## Run Locally

Clone the project

```bash
  git clone https://github.com/aliii010/token-authentication-Django.git
```

Go to the project directory

```bash
  cd token-authentication-Django
```

Set up a vertual environment

```bash
  Python3 -m venv venv
```

Activate the vertual environment (on macOS)

```bash
  source venv/bin/activate
```

Install the dependencies

```bash
  pip install -r requirements.txt
```

Run the server

```bash
  Python3 manage.py runserver
```
