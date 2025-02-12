# challenge18-Social-Network-API

## Description

A robust backend API for a social network application built using Express.js and MongoDB. This application provides a complete backend infrastructure that allows users to share thoughts, react to friends' thoughts, and create a friend list. The API uses MongoDB for its database and Mongoose ODM for data modeling.

## Features

- RESTful API endpoints for:
  - Users (GET, POST, PUT, DELETE)
  - Thoughts (GET, POST, PUT, DELETE)
  - Reactions (POST, DELETE)
  - Friends (POST, DELETE)
- Database relationships and associations
- Data validation and error handling
- Mongoose ODM for database management

## Installation

1. Clone the repository:
   ```bash
   git clone git@github.com:JoseGuache/challenge18-Social-Network-API.git
   ```
2. Navigate to the project directory
3. Install dependencies:
   ```bash
   npm install
   ```
4. Ensure MongoDB is installed and running on your system

## Usage

1. Start the server:
   ```bash
   npm start
   ```
2. Use Insomnia or Postman to test the API endpoints:
   - Users: `http://localhost:3001/api/users`
     - GET all users
     - GET a single user by ID
     - POST a new user
     - PUT to update a user
     - DELETE a user
   - Thoughts: `http://localhost:3001/api/thoughts`
     - GET all thoughts
     - GET a single thought by ID
     - POST a new thought
     - PUT to update a thought
     - DELETE a thought
   - Friends: `http://localhost:3001/api/users/:userId/friends/:friendId`
     - POST to add a friend
     - DELETE to remove a friend
   - Reactions: `http://localhost:3001/api/thoughts/:thoughtId/reactions`
     - POST to create a reaction
     - DELETE to remove a reaction

## Technologies Used

- Node.js
- Express.js
- MongoDB
- Mongoose ODM
- JavaScript Date object for timestamps

## Repository

[View on GitHub](https://github.com/JoseGuache/challenge18-Social-Network-API)

## Video Walkthrough

[Link to Video Demonstration](<https://drive.google.com/file/d/1Eg2gxhE5gynqMHNTSYhoSWjif1p_efKz/view?usp=sharing>)

I had a slight hiccup while recording the video, specifically when I was trying to delete a reaction. But i fixed the issue mid recording. Please watch all the way through.

## Credits

- Starter code provided by Professor Phil.
- [Professional README Guide](https://coding-boot-camp.github.io/full-stack/github/professional-readme-guide)

## License

This project is licensed under the MIT License - see the [LICENSE](https://opensource.org/licenses/MIT) for details.

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)