📚 Project Overview
This repository contains a set of Postman API tests for the Trello API. The tests are designed to verify the functionality and integrity of the Trello application, ensuring that common operations such as creating, updating, and deleting boards, lists, and cards work as expected.

The collection includes test scenarios for several Trello API endpoints, including:

GET operations (retrieving boards, lists, cards, etc.)

POST operations (creating new boards, cards, etc.)

PUT/PATCH operations (updating boards, lists, and cards)

DELETE operations (removing boards, lists, and cards)
The tests also incorporate environment variables to facilitate dynamic execution in different environments (e.g., production, development, etc.). These variables make the tests adaptable and reusable.

📋 Test Scenarios
The Postman collection includes tests for the following:

Creating and Updating Boards:
Test cases to ensure that a board can be created with the correct parameters and updated with new information.

Creating and Updating Cards:
Test cases to validate card creation and updating, including title, description, and due dates.

Managing Lists:
Tests for adding, retrieving, and deleting lists within a board.

Deleting Cards/Boards:
Ensures the system can successfully delete boards and cards.

Error Handling:
Verifying appropriate error messages for invalid requests (e.g., missing required fields, incorrect parameters).
