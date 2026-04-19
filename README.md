Petstore API Testing (Postman)

Description

This project contains API testing for Swagger Petstore using Postman.
It includes both positive and negative test scenarios for REST API endpoints.

Tools

* Postman
* REST API
* JavaScript (Postman Tests)

Test Coverage

Positive Scenarios:

* Create pet (POST)
* Get pet by ID (GET)
* Update pet (PUT)
* Delete pet (DELETE)

Negative Scenarios:

* Invalid ID (string instead of number)
* Request for non-existing pet
* Invalid request body
* Delete non-existing pet

Test Flow

* Full CRUD cycle (Create → Read → Update → Delete)
* Validation after each step
* Negative flow (update after delete)

Features

* Dynamic variables (petId)
* Automated tests (status code, response validation)
* Collection Runner execution

Example Checks

Get pet by ID

* Status code is 200
* Response contains pet ID
* Response contains pet name

Negative test (invalid ID)

* Status code is 400 or 404
* Error response is returned

Execution

Tests were executed using Postman Collection Runner.

Goal

To demonstrate practical API testing skills using Postman for QA purposes.
