# Introduction

This User Interface will let you manage the users while having the option of adding more and beingle able to order or filter them with certain attributes

# Table of Contents
- [Usage and Basic Features](#usage-and-basic-features)

- [UI Components](#ui-components)
  - [Header](#Header)
  - [Table](#table)
  - [New User Form](#new-user-form)

## Usage and Basic Features
At the beginning of the program, There will a table of users and the option to add a new user in the header. 

It will also contain a form to the right to be able to enter user informations to add a new user. The user can also be able to filter the table with certain attributes.

It will be possible to add a new user by filling out the form with the necessary information, saving the user and then adding it to the table.

Once some users are added to the table, It will be possible to sort or order the users in the table with the attributes users have.

*Below is a screenshot of the UI*

[![Downloads](https://lists.office.com/Images/969df1bb-97b6-44ef-9108-dc18a5fd96c2/298428f6-6729-4501-a9de-dcaf554877fe/T3L0G2MKUPU8GQUY8YHP00Z9RB/c2f1cb7e-5022-433a-93a2-1ac0b6ec1015)](https://lists.office.com/Images/969df1bb-97b6-44ef-9108-dc18a5fd96c2/298428f6-6729-4501-a9de-dcaf554877fe/T3L0G2MKUPU8GQUY8YHP00Z9RB/c2f1cb7e-5022-433a-93a2-1ac0b6ec1015)
## UI Components
---
User Interface consists of 3 main parts: **Header, Table, and New User Form**

## Header
---
### ****+ New User**** Button
After clicking the button, the user will be able to add a new user

### Hide Disabled User Check
When the checkbox is checked, the disabled users will be hidden from the table

### Save User Button
When the button is clicked, the user Information in the form will be saved

## Table
---
### Columns
`Column is an array of objects that contain the following properties:`
- `ID` of the user (int type)
- `User Name` of the user (string type)
- `Email` of the user (string type)
- A true or false value showing if the user is`Enabled` (boolean type)

### Column Filter and Ordering
Columns can be filtered and ordered by clicking on the column header. The upper button will order the table by ascending order and the lower button will order the table by descending order.

### The Table
---
## New User Form
- `Text Input Fields`: the form will have a text input field for each of the following properties to be filled in:
  - Username
  - Display Name
  - Phone
  - Email
- `User Roles`: the form will have a dropdown menu for the user roles which can be either `Guest User`, `Admin` or `User`
- `Enabled Checkbox`: the form will have a checkbox to enable or disable the user. It wil have a boolean value of `true` or `false`.