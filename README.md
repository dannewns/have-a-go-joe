# have-a-go-joe

##Install Laravel

If you take some time and read over the [http://laravel.com/docs/5.1/](docs) at

##Tasks

1. Create a migration that will create a user table with the following fields username, password, email, created_at,
updated_at.
2. Create a seed file that will pre-populate this table with a number of users.
3. Create a signup route that you can post to that allows users to sign up, important to remember validation so a user
    has to have a unique email address (this can also be added into the migration for this table).
4. Create a login route that allows the user to login with the credentials that they used during signup.
5. Make sure all validation errors are handled and that the response is taken care of, if you are going to use a form to
post the data then make sure errors are displayed, if you are going to post the data via something like postman,
meaning there is no need to create a form make sure the responses are correct going back.

### Things to note

It would be great if you were to use controllers to handle the route instead of just using closures in the routes.php
file.

