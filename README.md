# JavaScript Functions Basics

This project contains solutions to three basic JavaScript tasks focused on
working with functions and calculations.

## Project Structure

    ├── js/
    │ ├── task-1.js
    │ ├── task-2.js
    │ └── task-3.js
    ├── index.html
    ├── .gitignore
    ├── .prettierrc
    └── README.md

## Tasks

### Task 1: Droid Order

**File:** [js/task-1.js](./js/task-1.js)

Function makeTransaction(quantity, pricePerDroid):

- Calculates total price of ordered droids
- Returns a formatted message

Example:

`makeTransaction(5, 3000) // "You ordered 5 droids worth 15000 credits!"`

---

### Task 2: Shipping Message

**File:** [js/task-2.js](./js/task-2.js)

Function getShippingMessage(country, price, deliveryFee):

- Calculates total cost including delivery
- Returns a shipping message

Example:
`getShippingMessage("Germany", 80, 20) // "Shipping to Germany will cost
100 credits"`

---

### Task 3: Element Width

**File:** [js/task-3.js](./js/task-3.js)

Function getElementWidth(content, padding, border):

- Accepts values in "Npx" format
- Calculates total element width (including padding and border)
- Returns a number

Example:
`getElementWidth("50px", "8px", "4px") // 74`
