# Advice App
Overview
The Advice App is a simple React application that fetches and displays random advice from the Advice Slip API. The application demonstrates the use of React class components, state management, and making HTTP requests using Axios.

# Features
Fetches random advice from the Advice Slip API.
Displays the fetched advice on the screen.
Includes a button to fetch and display a new piece of advice.
# Skills Demonstrated
React.js: Utilizing class components and lifecycle methods.
State Management: Managing state within a class component.
Axios: Making HTTP requests to fetch data from an API.
CSS: Styling components using an external stylesheet.
# Installation
1.Clone the repository:

git clone https://github.com/your-username/advice-app.git

2.Navigate to the project directory:

cd advice-app

3. Install the dependencies:

npm install

# Usage
1.Start the development server:

npm start

2.Open your browser and navigate to http://localhost:3000.

# Code Overview
App.js: This file contains the main App component which is a class component. It manages the state and handles fetching advice from the API.

componentDidMount(): This lifecycle method calls fetchAdvice() when the component mounts.
fetchAdvice(): This method makes an HTTP GET request to the Advice Slip API and updates the state with the fetched advice.
render(): This method renders the advice and a button to fetch new advice.
App.css: This file contains the styles for the application.
