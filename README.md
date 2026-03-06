# Case Study: ATM Machine
## White Belt (Beginner Level)
### Problem Statement
In this case study, we will be building a basic ATM machine that allows users to perform simple banking transactions such as withdrawing cash and checking account balance.

ATM Machine Features:
- View account balance
  
  Implement a function to display the user's account balance.
- Deposit cash  
- Withdraw cash
  
  Implement a function to deduct the requested amount from the user's account balance.  
  Implement error handling for invalid account information or insufficient funds.

### Implementation
Create a new Git repository and set up a basic file structure with index.html and main.js files (*Notes: it will be better if we create a branch for each level*).

Use HTML and CSS to create a simple user interface for the ATM machine, including input fields for the user to enter their account information and transaction details.

In main.js, write a function to handle the submission of the account information form, which should make an asynchronous network request to retrieve the user's account balance.

Display the user's account balance on the screen using ECMAScript 6+ features such as template literals.

Write a function to handle the submission of the transaction form, which should deduct the requested amount from the user's account balance and display the updated balance on the screen.

Use callbacks to ensure that the network request for the user's account balance is completed before processing the transaction request.

Implement error handling for invalid account information or insufficient funds.

Use Bash commands to test the application locally and push changes to the Git repository.


## Yellow Belt (Intermediate Level)
### Problem Statement
Continuing from the white belt level case study of building an ATM machine, in the yellow belt level case study, we will be expanding the functionality of the ATM machine and covering additional topics from the syllabus, including account login and password authentication, and uses React.js for a more dynamic user interface.

ATM Machine Features:
- View account balance

  *Implement a function to display the user's account balance.*
- Deposit cash  
- Withdraw cash
  
  *Implement a function to deduct the requested amount from the user's account balance.*
  *Implement error handling for invalid account information or insufficient funds.*
- **Authentication with a PIN**

### Implementation
Use NPM to install project dependencies such as React, Redux, Axios, and React-Router.

Use Webpack to bundle and optimize project code for production.

Use the create-react-app CLI tool to create a new React project.

Use JSX to write dynamic and reusable components for the ATM machine, including components for account login, balance display, transaction history, and password authentication.

Use React APIs to render elements on the screen and manage component state.

Use event handlers to capture user input and update the component state.

Use conditionals and lists to dynamically render elements on the screen based on the component state.

Use Redux to manage application state, including the user's account balance and transaction history.

Use Axios to make HTTP requests to retrieve and update the user's account information.

Use Redux Form or Formik to handle form submission and validation for the account login and transaction forms.

Use React-Router to manage application routing between the login and transaction screens.

Use code splitting to optimize application performance by loading only the necessary components for each screen.

Use PWA features such as service workers and offline caching to make the application more accessible and reliable.

Use Bash commands to test the application locally and push changes to the Git repository.


## Orange Belt (Advanced Beginner Level)
### Problem Statement
Continuing from the yellow belt level case study of building an ATM machine with advanced features, in the orange belt level case study, we will be expanding the functionality of the ATM machine even further and covering additional topics from the syllabus, that allows users to perform secure banking transactions with features such as JWT authentication, real-time notifications via Socket.IO, and automated testing using Jest and Cypress.

ATM Machine Features:
- View account balance
  
  *Implement a function to display the user's account balance.*
- Deposit cash  
- Withdraw cash
  
  *Implement a function to deduct the requested amount from the user's account balance.*
  *Implement error handling for invalid account information or insufficient funds.*
- **Authentication with JWT authentication**
- **Notification**

### Implementation
Implement JWT authentication to securely authenticate users during account login and transactions.

Use Socket.IO to provide real-time notifications to users during transactions, such as balance updates and transaction confirmations.

Use Jest to write unit tests for the application, including tests for the Redux store and the React components.

Use Cypress.io with Cucumber to write end-to-end tests for the application, including tests for account login and transactions.

Use NYC to track code coverage during testing and ensure that all code is tested.

Use React Transition Group or React Motion to create smooth transitions between screens, improving the user experience.

Use Bash commands to test the application locally and push changes to the Git repository.


## Green Belt (Intermediate Advanced Level)
### Problem Statement
Continuing from the orange belt level case study of building an ATM machine, in the green belt level case study, we will be further expanding the functionality of the ATM machine and covering additional topics from the syllabus, to create an ATM machine with advanced features using NextJS, and deploy it to AWS for scalability and reliability.

ATM Machine Features:
- View account balance
  
  *Implement a function to display the user's account balance.*
- Deposit cash  
- Withdraw cash
  
  *Implement a function to deduct the requested amount from the user's account balance.*
  *Implement error handling for invalid account information or insufficient funds.*
- Authentication with JWT authentication
- Notification

### Implementation
Use NextJS to build the ATM machine with improved performance, and ensure that it is fully responsive.

Use React Hooks to manage state and lifecycle methods in the application, improving code readability and maintainability.

Use AWS to deploy the application for scalability and reliability, and configure a load balancer and auto-scaling group to handle high traffic.

Use Jenkins to automate the deployment process and ensure continuous integration and deployment.

Deploy the application to Heroku for quick and easy demonstration purposes, ensuring that all features are functional and the user experience is smooth.

Implement advanced features for the ATM machine using NextJS, such as transaction history and multiple account support.

Test the application locally using Bash commands, and push changes to the Git repository.