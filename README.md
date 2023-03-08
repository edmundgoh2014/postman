# postman
Postman Collection and Environment JSON Files

This repo contains the collection and environment JSON files that I have done using Postman. The collection is tested using the Contact List Documentation found on Postman website https://documenter.getpostman.com/view/401288/SWLceUSf. You will find 2 folders in the collection which are Basic Endpoint Tests and Negative Tests. For Basic Endpoint Tests I have created a GET request, POST request, PUT request and DELETE request. As for the Negative Tests, I have come out with some scenarios where the user might generate invalid requests such as invalid IDs, company name too long and etc.

Besides that, I have also created an environment variable whereby it will pass this variable value to the body of the request so that I do not have to change the value of every single request if I were to made any changes. I have also created some assertions to assert the response of the JSON request, the response status code and also the response time.
