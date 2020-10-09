# Brain Project

## Getting Started

This application uses the Clarifai machine learning API to identify faces in photo URLs. Users can register, login, and keep track of how many submissions they have made. This app securely stores user information in a PostgreSQL database through strong encryptions and secure sessions.

## Screenshots
### Log-in page: 
<img src="https://github.com/QinyiZhu/BrainProject/blob/master/Frontend/screenshots/signin.png" width="600">

### Searching page: 
<img src="https://github.com/QinyiZhu/BrainProject/blob/master/Frontend/screenshots/search.png" width="600">

### User Profile Modal:
<img src="https://github.com/QinyiZhu/BrainProject/blob/master/Frontend/screenshots/profile.png" width="600">

## Details
1. [ReactJS](https://reactjs.org/) is used for this Single-page web framework. 
2. React Portal is used to create a modal for user profile.
3. React-router is used for dynamically routing between pages.
4. Uses JSON Web Tokens as well as server session for user authentication to create efficient communication between server and browser. 
5. In-memory database Redis is used for user info storage in sessions. 
6. Bcrypt is used to hash users' passwords for database sercurity.
7. Reactstrap is used for responsive webpage design.
