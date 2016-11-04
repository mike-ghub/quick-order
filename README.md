Quick Order
===========

Quick Order is an application in its startup phase.  Because of its urgency to hit the market first, it will need an API to support other platforms to query and save data.  The first iteration of the app will be released as a web app.

The app simply logs a user in, choose a food item to order, and places the order.  The user can access the list of orders and mark an order as "received" at any time.


Your Task
---
  - Create an API that can `GET` and `POST` data
  - Create a login page (just username is fine)
  - Create a menu page to choose a menu item to order
  - Create a page to show current orders with the ability to mark an order as "received"

Requirements
------------

- Use EntityFramework as data access
- Seed menu data
- The API used for the web app should also be available for other apps to use

### Menu Data

| Item Name | Price |
| --------- | ----- |
| Burger    | $4.99 |
| Hot Dog   | $2.99 |
| Fries     | $1.99 |
| Soda      | $0.49 |

Given
---

- Login page
  - Entering username should be enough to "register" the user.  Password is not needed.
- Duplicate usernames are OK
- One item per order is acceptable

Bonus
---

These aren't required but bonus points will be awarded if completed.

- Use of IoC
- Unit Testing
