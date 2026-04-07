Petstore API Testing (Postman)

📌 Description

This project contains API testing for Swagger Petstore using Postman.

🔧 Tools
	•	Postman
	•	REST API
	•	JavaScript (Tests)

✅ Test Coverage

Positive scenarios:
	•	Create pet (POST)
	•	Get pet (GET)
	•	Update pet (PUT)
	•	Delete pet (DELETE)

Negative scenarios:
	•	Invalid ID (string instead of number)
	•	Non-existing pet
	•	Invalid request body
	•	Delete non-existing pet

🔄 Test Flow
	•	Full CRUD cycle
	•	Validation after each step
	•	Negative flow (update after delete)

⚙️ Features
	•	Dynamic variables (petId)
	•	Automated tests (status code, response validation)
	•	Collection Runner support
