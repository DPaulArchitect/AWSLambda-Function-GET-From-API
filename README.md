# AWSLambda-Function-GET-From-API
GET-Data from API and Enter into DynamoDB, you will need an iam role for the execution of this code
Please create iam role to allow access to DynamoDb
Do not forget to create the environment variables and name the required Database.
you will need to package the requests library for python within the function either as a layer or uploaded as zip with the python code file. since AWS lambda does not automatically hav the requests library installed. you may need to use runtime 3.12 of python.unless you use version 3.9 requests library.
