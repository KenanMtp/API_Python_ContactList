# API Python BDD framework test case
# Standalone thinking-tester-contact-list.herokuapp executable Python API test case
AddNewUser is meant to be executable Python BDD test case, used by QA engineers to succesfully execute this test.
This page will be tested: https://thinking-tester-contact-list.herokuapp.com/

Add contact to contact list tests:
- AddNewUser

AddNewUser test is used to test functionality of adding new user and create new contact in contact list

## Usage
1. Install Visual Studio Code
2. Install Python 3.11.0, add to PATH env variable: C:\Users\{username}\AppData\Local\Programs\Python\Python311\
3. Add following extensions: Behave, BDD - Feature-Editor, Cucumber (Gherkin) Full Support, Cucumber TsFlow for VS Code
4.  To run the test select .feature file "AddNewUser.feature", on the left pane click to "Run and debug", from drop down lis select
    "Python: Behave current file", and click "Play" button ( this will run in debugging mode)
    To run without debugging click on Run -> Run Wihout Debugging or press Ctrl + F5
