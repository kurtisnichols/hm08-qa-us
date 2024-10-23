This project contains end-to-end tests for the Urban.Routes ride share application, focusing on the process of creating an order, interacting with modals, and selecting a vehicle type. The tests cover functionalities such as opening a phone number modal, submitting a phone number, writing a message for the driver, and verifying that car search and driver information modals appear as expected.

Description
The purpose of this project is to ensure that the ride-share app's order creation flow works correctly, from selecting pickup and drop-off addresses to confirming the driver's arrival. These automated tests validate that the user interface behaves as intended, ensuring the integrity of the order creation experience.

Technologies and Techniques
WebdriverIO: A browser automation framework used to control and interact with the ride-share app.
JavaScript (Node.js): The programming language used for writing test scripts.
Async/Await: Used to handle asynchronous operations within tests.
Selectors: Specific elements like modals, buttons, and input fields are targeted using CSS selectors for interaction and validation.

How to run the tests

Prerequisites
Node.js is installed
Npm installed
Urban.Routes is accessible

Steps
1. Clone the repository using Git Bash replacing your username git clone git@github.com:username/hm08-qa-us.git
2. npm install
3. Create tests for the following key scenarios are covered in the tests:
-Opening and verifying the phone number modal.
-Submitting a phone number and validating its display.
-Writing a message for the driver and confirming the message is set.
-Selecting a supportive plan and ordering items like blankets and ice creams.
-Verifying the car search modal appears after placing an order.
-Checking that driver information is displayed once a driver is assigned.
4. Run tests using npm run wdio