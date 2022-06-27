# flask-login

Flask LOGIN template

.
└── flask_auth_app
    └── project
        ├── __init__.py       # setup the app
        ├── auth.py           # the auth routes for the app
        ├── db.sqlite         # the database
        ├── main.py           # the non-auth routes for the app
        ├── models.py         # the user model
        └── templates
            ├── base.html     # contains common layout and links
            ├── index.html    # show the home page
            ├── login.html    # show the login form
            ├── profile.html  # show the profile page
            └── signup.html   # show the signup form
