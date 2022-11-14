# Login  application

A frontend validation and login system application that takes on email and password as inputs to log in a user and uses the useReducer() hook to manage it's state

**End Result**

CLick here : https://login-system-v2-eniola.netlify.app/

# Description

**Details**

This is a frontend validation and login system application that takes on email and password as inputs to log in a user and uses the useReducer() hook to manage it's state.

The form has a validation that automatically disables the login button when the input fields contains invalid value, then enables the button once the input field value is valid on every keystroke

The disabled button due to invalid input values

![Form](https://github.com/Eniola-Codes/Login-System-App-V2/blob/main/src/assets/invalid.png?raw=true)

The enabled button due to valid input values

![Form](https://github.com/Eniola-Codes/Login-System-App-V2/blob/main/src/assets/valid.png?raw=true)

It stores the user login state in the local storage of the web browser so the user stays logged in even though the page is reloaded or the user leaves and visits the page later

When user is logged in, they user can easily log out with the logout button and the state is set to log out using the useContext() hook

![Log out](https://github.com/Eniola-Codes/Login-System-App-V2/blob/main/src/assets/logoutbutton.png?raw=true)

**Technologies**

Technologies i used to build this are React.js and css

I used React.js framework to bootstrap this project because of the below functionalities : 

- Seperation of concerns (Having leaner files and components by breaking down the code into smaller parts)
- Using useReducer hook to manage the state of the application
- Prop drilling to pass some data from component to component with ease.
- Css modules which prevent clashing of classnames around components therefore avoiding unwanted results

# Installation and Running

git clone or pull the project using your terminal, open the project folder on your local laptop in a code editor and run "npm start" in your editors terminal.

