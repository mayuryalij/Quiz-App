# Capstone Project- Quiz app

    Intro about Quizz App :

    1.  The App basically allows the user to make an interactive quiz. The Create New Quiz is used to start creating the new quiz where they will be given a choice to select the type of quiz. Then they will be redirected to the quiz creation. After creating the quiz, users can check the list of quizzes  in the My Quizzes page.

    2. Then the user can go on to the Play quiz page to start the quiz, before starting the quiz it requires the Name for the authentication. After playing the quiz, the result page will be shown at the end.

    3. The user can enable and disable particular quizzes by using the toggle button.

    4. The user can delete the quizzes if they dont want it by using the delete button.

    Functionality and Components of Quizz App :

    The App.js is the initial and main file where the Navbar components and the react-routers are being rendered.

    1. This Quiz Platform app contains mainly 6 pages :
       Home Page,
       Create Quiz Page,
       My Quizzes Page,
       Authentication Page,
       Play Quiz Page and
       Result Page.

    2. Routings :
        The React-router-dom is used for navigating the routes between the different pages.

    3. State management :
         React-redux is used for state management operations
          * React Redux is the official React UI bindings layer for Redux.
          * It lets your React components read data from a Redux store, and dispatch actions to the store to update state.
          * It mainly consists of three parts, namely
             actions
             store
             Reducers

    4. Framer-motion :
      Framer Motion is an animation library that makes creating animations easy.
      Its simplified API helps us abstract the complexities behind animations and allows us to create animations with ease.

    5.conclusion :
     * This project is created with React.js and its dependencies.
     * css is used for stylings.
     * The React-router-dom is used for Routings.
     * React-redux is used for state management .
     * Framer Motion is used for animation.

Deployment link : https://qizz-app.netlify.app/
Github link : https://github.com/EswarChandran0110/quiz-app

React-redux Component :

React components are used to read data from a Redux store, and dispatch actions to the store to update state.

React components are divided into 3 types, namely
Action.js
Reducer.js
Store.js

Action.js

The Action.js contains the all action types which are required and the necessary actions in order to dispatch them.

Reducer.js

The initial state of the application is stored in reducers.
The reducer contains the necessary functions to update the state.

Store.js

It creates the store and reducers.
The store combines all the reducers and the final store will be used in our app.
