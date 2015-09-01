Write an application that allows you to create a User via JSON and persist it to some sort of datastore. Return back the JSON object just created. 

The requirements for the application are as follows:

1. To start fork the repo
2. The user model must have a first_name, last_name, email, social_security_number
3. Require all fields, validate that email is in the proper format, and that social_security_number is 9 digits long.
4. All requests should respond with the user object with only the following fields: first_name, last_name, email, and id
5. There needs to be an 'index' view that responds with all of the Users in system 
6. There also needs to be a 'show' that responds with a specific
7. When finished open a pull request and assign it to the owner of this repo

Bonus:

1. Add request specs that tests both a valid and invalid call to user create,show,and index requests
2. Accept social security in either 000-00-0000 or 000000000 format
