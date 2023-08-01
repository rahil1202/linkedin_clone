# LinkedIn Clone

Welcome to the GitHub repository of my LinkedIn clone built using ReactJS, HTML, CSS, Redux, and Firebase. This project is a web application that replicates some of the key features and functionalities of the popular professional networking platform, LinkedIn.

# Live Demo

Check out the live demo of the LinkedIn Clone: : [Live Demo](http://linkedin-clone-rahil1202.netlify.app)

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)


## Introduction

The LinkedIn Clone is a personal project that demonstrates my proficiency in web development technologies such as ReactJS, HTML, CSS, Redux, and Firebase. It aims to provide users with a similar experience to LinkedIn, allowing them to create profiles, post updates, connect with other users, and interact with posts through comments and likes.

## Features

- **User Authentication**: Users can sign up, log in, and reset passwords securely using Firebase Authentication.

- **Dynamic User Profiles**: Users can create and customize their profiles with personal and professional details, including profile pictures and work experiences.

- **Social Networking**: Users can create, edit, and delete posts, and interact with posts from other users through comments and likes.

- **Real-Time Updates**: The application leverages Firebase Firestore for real-time database management, ensuring instant updates and seamless interactions.

## Technologies Used

- **ReactJS**: For building the user interface and managing components efficiently.
- **HTML**: For the project's structure and content.
- **CSS**: To handle the website's styling and layout.
- **Redux**: For state management and handling data flow between components.
- **Firebase**: For user authentication and real-time database management.
- **Styled Components**: For creating dynamic and responsive styles.

## Installation

1. Clone the repository:
   ```
   git clone https://github.com/your-username/linkedin-clone.git
   ```

2. Navigate to the project directory:
   ```
   cd linkedin-clone
   ```

3. Install the dependencies:
   ```
   npm install
   ```

4. Set up Firebase:
   - Create a new Firebase project and set up the Firestore database.
   - Enable Firebase Authentication and configure the sign-in methods (email/password, Google, etc.).

5. Create a `.env` file in the root directory and add your Firebase config variables:
   ```
   REACT_APP_API_KEY=your_firebase_api_key
   REACT_APP_AUTH_DOMAIN=your_firebase_auth_domain
   REACT_APP_PROJECT_ID=your_firebase_project_id
   REACT_APP_STORAGE_BUCKET=your_firebase_storage_bucket
   REACT_APP_MESSAGING_SENDER_ID=your_firebase_messaging_sender_id
   REACT_APP_APP_ID=your_firebase_app_id
   ```

6. Start the development server:
   ```
   npm start
   ```

7. Open your web browser and navigate to `http://localhost:3000` to see the application running.


Thank you for checking out my LinkedIn clone project! I hope you find it informative and enjoyable to explore.
