# E-Laboratory Mobile Project

The **E-Laboratory Mobile Project** is a mobile application designed for doctors and patients to track, analyze, and manage medical test results. This application leverages Firebase as the backend to offer features like user authentication, guide management, test result evaluation, and user profiles.

## Features

### Doctor Panel
- View and evaluate patient test results.
- Create new guides for analysis.
- Analyze test results based on existing guides.
- Add new test results for patients.

### User Panel
- View medical test results.
- Update user profile information.

### Registration and Login
- Secure user registration and login using Firebase Authentication.
- Automatically register new users in the `Users` collection with a unique UID.

### Guide Management
- Manage guides dynamically using Firebase Firestore.
- Doctors can add new guides or edit existing ones.
- Evaluate test results based on selected guides.

## Technologies Used

- **Frontend**: React Native  
- **Backend**: Firebase (Authentication and Firestore)  
- **UI Libraries**:
  - React Native Picker
  - React Navigation
  - Expo

## Installation

### Prerequisites
- Node.js (v14 or later)
- Expo CLI
- A configured Firebase project

### Steps to Install

1. Clone the repository:
   ```bash
   git clone https://github.com/username/e-laboratory-mobile-project.git
   cd e-laboratory-mobile-project
