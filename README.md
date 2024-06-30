Claro, aquí tienes un archivo `README.md` mejor formateado:


<img src = "https://i.pinimg.com/originals/ff/f3/e3/fff3e3d05b0961ceb9d23c3dfd2a7c21.gif" width = auto> </h1>
<p align='center'>
</p>

# Doctor Management Web Application

This is a web application for managing doctors. Users can sign up, log in, view a list of doctors, add new doctors, and edit doctor details.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
  - [Sign Up](#sign-up)
  - [Log In](#log-in)
  - [View Doctors](#view-doctors)
  - [Add Doctor](#add-doctor)
  - [Edit Doctor](#edit-doctor)
- [Project Structure](#project-structure)
- [API Documentation](#api-documentation)
  - [API Endpoints](#api-endpoints)
- [Technologies Used](#technologies-used)
- [Contact](#contact)

## Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/your-username/doctor-management.git
   cd doctor-management
   ```

2. **Install dependencies:**

   ```bash
   npm install
   ```

3. **Start the development server:**

   ```bash
   npm start
   ```

   The application will be available at `http://localhost:3000`.

## Usage

### Sign Up

1. Go to the sign-up page by clicking on "Crear cuenta nueva" on the login page.
2. Fill in your username and password.
3. Click "Registrarme" to create a new account.

### Log In

1. Go to the login page.
2. Enter your username and password.
3. Click "Iniciar sesión" to log in.

### View Doctors

Once logged in, you will be redirected to the list of doctors. Here you can:

- View a list of all doctors.
- Search for doctors using the search bar.

### Add Doctor

1. Click on "Agregar Doctor" in the navigation menu.
2. Fill in the doctor’s details (name, email, phone number).
3. Click "Guardar" to add the new doctor.

### Edit Doctor

1. Click the edit icon next to a doctor's name in the list of doctors.
2. Update the doctor’s details.
3. Click "Guardar" to save the changes.

## Project Structure

The project structure is organized as follows:

```
src/
├── AddPage/
│   ├── AddDoctor.js
│   └── AddDoctorPage.js
├── ListPage/
│   ├── DoctorList.js
│   └── DoctorListPage.js
├── User/
│   ├── Login.js
│   └── SignUp.js
├── App.css
├── App.js
├── index.css
├── index.js
└── reportWebVitals.js
```

- **AddPage/**: Contains components related to adding a doctor.
- **ListPage/**: Contains components related to listing and viewing doctors.
- **User/**: Contains components for user authentication (login and sign-up).
- **App.js**: The main component that sets up routing.
- **index.js**: The entry point of the application.

## API Documentation

The backend API is documented using Swagger. To view the API documentation, start the backend server and open `http://137.184.5.176:3034/api-docs` in your browser.

### API Endpoints

- **POST /signup**: Register a new user.
- **POST /login**: Log in a user.
- **GET /visitantes**: Retrieve a list of all visitors (doctors).
- **POST /visitantes**: Add a new visitor (doctor).
- **PUT /visitantes/:id**: Update an existing visitor (doctor).
- **DELETE /visitantes/:id**: Delete a visitor (doctor).

## Technologies Used

- **Frontend**: React, Material-UI
- **Backend**: Node.js, Express, MongoDB
- **Documentation**: Swagger

## Tecnologies
<div size='20px'>
	<h3>The Technologies that you need are: </h3> 
	<p align="center">
	  <a href="https://skillicons.dev">
	    <img src="https://skillicons.dev/icons?i=git,github,nodejs,mongo,docker,typescript,react" />
	  </a>
	</p>
</div>

For any questions or feedback
```

