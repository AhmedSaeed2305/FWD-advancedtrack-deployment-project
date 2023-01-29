# Pipeline description

## the pipeline for circleci starts with creating a docker image with required node.js version

1. the dependancies for the frontend are installed
2. the dependancies for the API are installed
3. run the eslint command to make sure that the code is free of errors
4. build the frontend app by running the build command
5. build the API app by runnint the build command
6. create new docker image
7. deploy the frontend to S3 bucket after installing the required dependancies and build the app
8. deploy the API to aws elastic beanstalk after installing the required dependancies and build the app and zip the build folder.
