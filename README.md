# Backend_Test_H45

## Introduction
You are going to build a rest API server to expose a List of Drivers to a client application

### Required dependencies

- Python 3.8+
- pipenv
- Django rest framework
- Postgres 13+

### Deliverables

* Your Github repo should contain the whole project with the truck application and basic server settings. Make sure the local server can be spun up without any errors. (You don't need to commit the local database .sqlite to the repo)

* Model: Design the model to store the driver's information information in the database. Each driver has the following field or attributes:
  * name
  * mobile_number
  * email
  * city
  * district
  * language
  * an_aasigned_truck (each truch has a unique number_plate and and a unique registration_number)

* API endpoints and expected responses:
  #### http(s)://domain/driver
  - Return a list of available drivers
  - Allow filtering using a driver's email, mobile_number, langeuage and his truck's number_plate
  
  #### http(s)://domain/driver/id
  - Return a single driver

  #### http(s)://domain/driver/
  - create a single driver

* README
  * Please justify every single library you have used for this test
  * Potential improvements
  * Production consideration
  * Assumptions: For example what assumptions did you make during your schema desiign for example

* Bonus Points
  * Creating bulk drivers
  * Unit test

