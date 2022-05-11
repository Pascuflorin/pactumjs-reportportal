Sample Test Case
Feature: Regression
For this project we are testing the following url:
https://qa-practice.herokuapp.com/swagger-ui.html#/employee-controller

  In order to keep Regression api stable
  As a tester
  I want to make sure that everything works as expected
  
  For this test i did the following requests:
  1:Get all employees
  2:Create employee
  3:Return employee by id and check header
  4:Update employee id
  5:Delete employee by id

  The delete method may fail because the domain is public and constantly changing

To run tests use the following command in the terminal:
npm run test

Reporter
The reports are generated automatically as a json file in the reports folder