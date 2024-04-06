# react-expensetracker

Step 1: npx create-react-app expensetracker <<Project_Name>>
npx is a package runner tool that comes with npm 5.2+ and can be used to create a new React app. The create-react-app command is commonly used with NPX, and it doesn't require installation.
Step 2: cd expensetracker
Step 3: npm i styled-components
styled-components is a package on npm that uses tagged template literals and CSS to write CSS code for styling components.
Step 4: Create a folder called components in src directory and create the following files inside it AddTransaction.js, OverviewComponent.js, Tracker.js, TransactionItem.js, TransactionsContainer.js and inside src directory create file globalStyles.js
App.js: This component is responsible, for rendering the layout of the application.
AddTransaction.js: This component allows users to add transactions.
OverviewComponent.js: This component displays the balance along with an “Add” button.
Tracker.js: The component that brings together parts of the application such as overview transaction list and addition of transactions.
TransactionItem.js: This component is responsible, for displaying transaction details including description, amount and a button to remove it from the list.
TransactionsContainer.js: This component. Filters the list of transactions. It offers a search input field and displays only filtered transaction items.
Step 5: npm start
Step 6: run http://localhost:3000/ in browser
