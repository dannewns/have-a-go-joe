# have-a-go-joe

##Install Laravel

If you take some time and read over the [http://laravel.com/docs/5.1/](docs) at and look how to install Laravel as well
as setting up your environment variables.

##Tasks

1. Create a migration that will create a user table with the following fields username, password, email, created_at,
updated_at.

2. Create a seed file that will pre-populate this table with a number of users.

3. Create a user Model that you can use during registration and login.

4. Create a signup route that you can post to that allows users to sign up, important to remember validation so a user
    has to have a unique email address (this can also be added into the migration for this table).

5. Create a login route that allows the user to login with the credentials that they used during signup, again this
should handle instances where a user doesnt exists already in the database and return the validation error, if a user is
successfully logged in then simply redirect them to a dashboard route that shows the logged in users username and email.

6. Make sure all validation errors are handled and that the response is taken care of, if you are going to use a form to
post the data then make sure errors are displayed, if you are going to post the data via something like postman,
meaning there is no need to create a form make sure the responses are correct going back.

### Things to note

It would be great if you were to use controllers to handle the route instead of just using closures in the routes.php
file.

Using a repository for the authentication would also be great as it would make a smaller code footprint in the
controller you dont have to do this, but by doing so it will give you a better understanding of how service providers work.

