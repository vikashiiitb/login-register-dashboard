# Login-Register-Dashboard

A basic React application that demonstrates a simple authentication flow with a Login, Register, and Dashboard page. This project uses localStorage to store user information and serves as a starter template for demos or learning purposes.

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

This project uses [react-bootstrap](https://react-bootstrap.netlify.app). 
User has to register user 

## Features

	•	User Registration: Users can register with a username and password. Registered users are stored in localStorage.
	•	User Login: Registered users can log in using their credentials. Login authentication is handled with localStorage.
	•	Dashboard: Once logged in, users are redirected to a plain dashboard page.
	•	Protected Routes: The dashboard is accessible only for authenticated users.
	•	React Bootstrap Styling: Pages are styled using React Bootstrap for a clean and responsive UI.

## How It Works

	1.	Register:
        •	Enter a unique username and password on the registration page.
        •	The user credentials are stored in localStorage.
	2.	Login:
        •	Log in with the registered username and password.
        •	If the credentials match, the user is logged in, and their session is stored in the app’s context.
	3.	Dashboard:
        •	Upon successful login, the user is redirected to the dashboard page.
        •	If the user is not logged in and attempts to access the dashboard, they are redirected to the login page.
	4.	Logout:
	    •	The user can log out to clear the session and return to the login page.

## Project Structer

src/
├── components/
│   ├── LoginForm.js       # Contains the login form logic and UI
│   ├── RegisterForm.js    # Contains the registration form logic and UI
├── context/
│   └── AuthContext.js     # Manages authentication state using React Context API
├── pages/
│   ├── LoginPage.js       # Login page that uses LoginForm
│   ├── RegisterPage.js    # Registration page that uses RegisterForm
│   ├── DashboardPage.js   # Plain dashboard page for logged-in users
├── App.js                 # Application's root component
├── index.js               # Entry point of the application
└── styles.css             # Custom styles (optional)


## Installation and Setup

	1.	Clone the repository:
        git clone https://github.com/vikashiiitb/login-register-dashboard.git
        cd login-register-dashboard


    2.	Install dependencies:
        npm install

    3.	Start the development server:
        npm start

    4.	Open your browser and navigate to:
        http://localhost:3000



## Dependencies

	•	React: Front-end library
	•	React Router DOM: For routing and navigation
	•	React Bootstrap: For styling
	•	Bootstrap: CSS framework for responsive design


## Dependencies

	•	React: Front-end library
	•	React Router DOM: For routing and navigation
	•	React Bootstrap: For styling
	•	Bootstrap: CSS framework for responsive design


## Contribution

Feel free to fork the repository, create new features, or report issues.
	1.	Fork the project.
	2.	Create a feature branch (git checkout -b feature-branch).
	3.	Commit your changes (git commit -m "Add new feature").
	4.	Push to your branch (git push origin feature-branch).
	5.	Open a pull request.


## License

This project is open source and available under the MIT License.


## Contact

If you have any questions, feel free to reach out:
	•	Author: Vikash Kumar
	•	Email: vikashiiitb@hotmail.com
	•	GitHub: vikashiiitb