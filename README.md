# Automation Anywhere Assignment
## Overview
This project contains the automation scripts I created using Playwright for the assignment.
There are three use cases covered:
- Use Case 1: Creating a Task Bot and adding a message box
- Use Case 2: Creating a form and interacting with fields
- Use Case 3: Simple API testing
---
## Tools Used
- Playwright
- TypeScript
- Node.js
- VS Code
---
## Setup Instructions
1. Install Node.js  
You can download it from https://nodejs.org/
2. Install dependencies  
Run this in the project folder:
npm install
3. Install Playwright browsers  
npx playwright install
---
## How to Run
Run all test cases:
npx playwright test

Run individual files:
Use Case 1:
npx playwright test tests/usecase1.spec.ts
Use Case 2:
npx playwright test tests/usecase2.spec.ts
Use Case 3:
npx playwright test tests/usecase3.spec.ts
---
## What each test does
Use Case 1:
- Logs into the website
- Creates a Task Bot
- Adds a Message Box action
- Saves the bot
Use Case 2:
- Creates a form
- Adds fields like text box and file option
- Enters sample data
- Saves the form
Use Case 3:
- Sends an API request
- Checks the response
- Verifies basic data
---
## Notes
- Some UI elements were dynamic, so I used waits where needed
- The form builder uses an iframe, so I handled it using frameLocator
- For file upload, a valid file path is required from the local system

Example:
C:/Users/ullas/Desktop/text.pdf
- I used Playwright codegen initially to understand selectors and then simplified the code
---
## Final Status
All three use cases are completed and tested.
---

## Author
Pragna
