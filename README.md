# Internshala Clone

## Description
A clone of the Internshala web application built using the MERN stack (MongoDB, Express, React, Node.js). This project aims to replicate the core functionalities of Internshala, including internship listings, user authentication, and application management.

## Features
- User Registration and Authentication
- Internship Listings
- Internship Application Management
- Admin Dashboard for Internship Posting
- Responsive Design

## Technologies Used
- MongoDB
- Express.js
- React.js
- Node.js
- Bootstrap (for styling)

## Installation

### Prerequisites
- Node.js
- npm (Node Package Manager)
- MongoDB

### Steps
1. **Clone the repository**
    ```bash
    git clonehttps://github.com/dm-mishra1578/Internshala-Clone.git
    cd internshala-clone
    ```

2. **Set up the backend**
    - Navigate to the `backend` directory.
    - Install dependencies:
    ```bash
    cd backend
    npm install
    ```
    - Create a `.env` file and add your MongoDB URI and other environment variables:
    ```env
    MONGO_URI=your_mongodb_uri
    JWT_SECRET=your_jwt_secret
    ```

3. **Set up the frontend**
    - Navigate to the `frontend` directory.
    - Install dependencies:
    ```bash
    cd ../frontend
    npm install
    ```

4. **Run the application**
    - Start the backend server:
    ```bash
    cd ../backend
    npm start
    ```
    - Start the frontend development server:
    ```bash
    cd ../frontend
    npm start
    ```

5. **Open the app**
    - Navigate to `http://localhost:3000` in your web browser to see the app in action.

## Usage
- **User**: Register and log in to browse and apply for internships.
- **Admin**: Log in to the admin dashboard to post and manage internships.

## Screenshots
!Home Page
!Internship Listings

## Contributing
1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add some feature'`).
5. Push to the branch (`git push origin feature-branch`).
6. Open a pull request.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Contact
- **Your Name**  Devanand
- **GitHub** - dm-mishra1578
