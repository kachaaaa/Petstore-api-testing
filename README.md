Petstore API Testing (Postman)

Description

This project contains API testing for Swagger Petstore using Postman.
It covers both positive and negative test scenarios for REST API endpoints.

Tools

* Postman
* REST API
* JavaScript (Postman Tests)

Test Coverage

Positive scenarios:

* Create pet (POST)
* Get pet by ID (GET)
* Update pet (PUT)
* Delete pet (DELETE)

Negative scenarios:

* Invalid ID (string instead of number)
* Request for non-existing pet
* Invalid request body
* Delete non-existing pet

Test Flow

* Full CRUD cycle
* Validation after each step
* Negative flow (update after delete)

Features

* Dynamic variables (petId)
* Automated tests (status code, response validation)
* Collection Runner support

Goal

To demonstrate practical API testing skills using Postman for QA purposes.
