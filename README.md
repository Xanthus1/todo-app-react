# TodoApp React Frontend

This project is the React frontend for a todo list application, and will need to connect to a compatible backend API to interact with the "Todo" data: https://github.com/Xanthus1/todo-app-backend

This project was initially created following this tutorial, with some changes and new features: https://codingthesmartway.com/the-mern-stack-tutorial-building-a-react-crud-application-from-start-to-finish-part-1/. Bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Demo

https://xanthus-todo-react.herokuapp.com/

## Installation / Configuration

Clone this repository:

`$ git clone https://github.com/Xanthus/todo-react`

Create a file with the name ".env" in the root directory, and use the example below to define the backend API URL. If this isn't defined, the app will use "http://localhost:4000" by default.

`REACT_APP_TODO_API_URL="http://example.com"`

Install dependencies (execute in root directory)

`$ npm install`

## Deployment

To run in development mode:

`$ npm run start`

To build for production:

`$ npm run build`

See https://create-react-app.dev/docs/deployment/ for deployment
