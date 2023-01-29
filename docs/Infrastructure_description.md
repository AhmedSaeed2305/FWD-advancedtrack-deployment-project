# The project starts when the end user sent a request to log in or sign

## the login request will be sent for authentication if it got authenticated the user logs in

## the sign up request will generate new token for the user to use it in further operations

## if the user is signing up his user name and password are sent from the frontend to the api to hash the password and store the hashed password and the username into the RDS postgres database

# then the frontend on the aws S3 sends a request to the API on the elastic beanstalk to fetch all the already exist photos of the user and the API get the data from the RDS postgres database

# User can upload his photos which are sent from the frontend to the API then stored in the postgres on RDS and they are sent back to the frontend to get displayed for the user.
