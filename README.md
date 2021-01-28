# Hopin QA Challenge
# Table of Contents
1. [Task 1 - Clone Repo](https://github.com/DaleSDET/Hopin-QA-Challenge/blob/main/README.md#task-1---clone-repo)
2. [Task 2 - Create a test plan and run it manually](https://github.com/DaleSDET/Hopin-QA-Challenge/blob/main/README.md#task-2---create-a-test-plan-and-run-it-manually)
3. [Task 3 - Create an automated API level test scenario](#third-example)
4. [Task 4 - Create an automated UI level test scenario](#fourth-examplehttpwwwfourthexamplecom)

## Task 1 - Clone Repo

[Test Env Screenshot](https://github.com/DaleSDET/Hopin-QA-Challenge/blob/main/Screenshot%202021-01-27%20125703.jpg)

## Task 2 - Create a test plan and run it manually

NB: I have taken note of the requirement for a "test plan that will **minimally** contain the steps that have to be taken" in respect to this, the documented tests below are not as extensively detailed as they may have been.

### In Scope

| Module   | Description |
| ------------- | ------------- |
| Welcome Screen  | The Welcome Screen presents the user to a form where he/she can be identified. The form consists of, Instructions text: "Please provide your name:", A text field where the user will input his/her name, and A Submit button.|
| Customer List Screen | This screen presents the list of all registered customers. For each customer, the following info is shown: <BR>1. Name <BR><BR> 2. Number of Employees <BR><BR> 3. Size: if number of Employees is less than or equal 100, size is Small; if greater than 10 and less than or equal to 1000, Medium; otherwise, Large <BR><BR> When the user clicks on a customer name, the Contacts Detail Screen is shown.  |
| Contact Details Screen | This screen shows the customers detailed info (Name, # of Employees, and Size) and also the name and e-mail of the person in the company to be contacted. |
| API | Content Cell  |

### Out of Scope

### Test Cases
#### 1 Welcome Screen

| ID#  | Description | BDD | Notes |
| ------------- | ------------- |------------- | ------------- |
| 1    | Submit a valid name | Given I am on the welcome screen 
When I provide my name
And I submit my name
Then I can see the Customer List Screen |
| 2    | hfghgfhfghf |     |       |

#### 2 Customer List Screen
#### 3 Contact Details Screen
#### 4 API
