![Screenshot](/screenshot.png)
## Project Overview
This project is a Kanban Board back-end implementation. Implement it according to the front-end project (https://github.com/terra-project/screening-test-frontend) spec.

## The Task
All of the features in the `required features` must be implemented. Choose items you want to add from `advanced features` and implement as many as possible. Focus on implementing the function rather than making it beautiful.

## Required features
* API Server
* TypeScript
* Any kind of persistent database

### Model: Column
* Fields: ID, Name, Order

### Model: Card
* Fields: ID, Column ID, Name, Description, Created date, Updated date, Labels, Order

### User(front-end) Stories
* User can add column with name
* User can modify column name
* User can delete column
* User can change column ordering
* User can add card to column with name and description
* User can modify card details
* User can identify / switch status of card
* User can change card ordering
* User can archive card

## Advanced features

* Test codes
* Graceful error handling
* Dockerizing
