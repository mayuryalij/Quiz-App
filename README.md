# Capstone Project - Quiz App

## Introduction to Quiz App:

The Quiz App is an interactive application that allows users to create and play quizzes. It provides various features to enhance the quiz creation and playing experience.

1. Create New Quiz:
   - Users can start creating a new quiz by selecting the "Create New Quiz" option. They will be prompted to choose the type of quiz they want to create and then redirected to the quiz creation page.
   - After creating the quiz, users can view a list of their quizzes on the "My Quizzes" page.

2. Play Quiz:
   - Users can proceed to the "Play Quiz" page to start taking a quiz. Before starting, they need to provide their name for authentication purposes.
   - Once the quiz is completed, the result page will be displayed.

3. Enable/Disable Quizzes:
   - Users have the option to enable or disable specific quizzes using the toggle button. This feature provides flexibility in managing the availability of quizzes.

4. Delete Quizzes:
   - Users can delete quizzes they no longer need by using the delete button. This allows them to remove unwanted quizzes from their list.

## Functionality and Components of Quiz App:

The main file of the application is `App.js`, which renders the Navbar components and sets up the react-routers.

1. Pages:
   - Home Page
   - Create Quiz Page
   - My Quizzes Page
   - Authentication Page
   - Play Quiz Page
   - Result Page

2. Routing:
   - The `react-router-dom` library is utilized for navigating between different pages within the application.

3. State Management:
   - State management operations are handled using `react-redux`.
   - React Redux is the official React UI bindings layer for Redux, enabling React components to read data from a Redux store and dispatch actions to update the state.
   - It consists of three main parts: actions, store, and reducers.

4. Framer Motion:
   - Framer Motion is an animation library that simplifies the process of creating animations.
   - It provides an easy-to-use API, abstracting the complexities of animations and enabling smooth animation creation.

## Conclusion:
- This project is developed using React.js and its dependencies.
- CSS is used for styling the application.
- `react-router-dom` is utilized for routing between pages.
- `react-redux` is employed for state management.
- `Framer Motion` is used to enhance the application with animations.

Deployment link: [https://qizz-app.netlify.app/](https://qizz-app.netlify.app/)
GitHub link: [https://github.com/EswarChandran0110/quiz-app](https://github.com/EswarChandran0110/quiz-app)

## React Redux Components:

React components are employed to read data from the Redux store and dispatch actions to update the state.

The React components are divided into three types:

1. Action.js:
   - `Action.js` contains all the necessary action types and actions required for dispatching them.

2. Reducer.js:
   - The initial state of the application is stored in the reducers.
   - The reducer contains the necessary functions to update the state.

3. Store.js:
   - `Store.js` creates the store and reducers.
   - It combines all the reducers, and the final store is used in the application.