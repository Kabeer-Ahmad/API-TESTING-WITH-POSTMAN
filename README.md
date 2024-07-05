# Assignment1 Module 3 & 4 (POSTMAN)

This repository contains a Postman collection that demonstrates the usage of various API methods and Postman features for testing purposes.

## Overview

This collection uses the [Restful API](https://api.restful-api.dev) to cover the following points:
- Set Base URL as a variable and use it for all API methods
- Generate Random data to be used in API request body
- Parse the JSON response body and log the value of any property in Postman Console
- Use Postman Chai Assertion Library to verify values in response data
- Write a Postman assertion to deliberately fail a test case
- Set the values for variables in Pre-request script, run the API, and reset the values in Tests section
- Use a response from the result of one API and set it as a variable, then use the variable as a parameter in the next API and run the two APIs as a collection

## Collection Structure

- **GET REQUEST**: A GET request to fetch objects, parse JSON response, and log a property.
- **POST REQUEST**: A POST request to create an object, parse JSON response, log and set a variable.
- **PUT REQUEST**: A PUT request to update an object using a variable.
- **PATCH REQUEST**: A PATCH request to partially update an object using a variable.
- **DELETE REQUEST**: A DELETE request to remove an object using a variable.
- **Fail A Test**: An example to deliberately fail a test case.
- **Variables in Pre Request**: An example to set variables in the pre-request script.

## Getting Started

### Prerequisites
- Postman installed on your machine

### Importing the Collection
1. Download the collection file `Assignment1_Module3&4.postman_collection.json`.
2. Open Postman.
3. Click on the `Import` button.
4. Select the downloaded file and import it.

### Running the Collection
1. Ensure the base URL variable `{{URL}}` is set correctly (default is `https://api.restful-api.dev`).
2. Select the collection and click on `Run` to open the Collection Runner.
3. Click on `Start Run`.

## Features

### Setting Base URL as a Variable
The base URL is set as a variable `{{URL}}` and is used in all requests for consistency and easy updates.

### Generating Random Data
Random data is generated in the request body to simulate dynamic inputs.

### Parsing JSON Response
The JSON response body is parsed, and properties are logged in the Postman console for verification.

### Chai Assertion Library
Postman Chai Assertion Library is used to validate response data, ensuring the correctness of API responses.

### Deliberately Failing a Test
An assertion is written to deliberately fail a test case, demonstrating the handling of failed tests.

### Pre-request and Test Scripts
Values for variables are set in the Pre-request script, and APIs are run with these values, which are then reset in the Tests section.

### Chained Requests
The response from one API is used as a variable in the next API, demonstrating the chaining of requests within a collection.


