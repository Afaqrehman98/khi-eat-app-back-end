**KHI-EAT-APP-BACK-END**
Welcome to KHI-EAT-APP-BACK-END! This project is a Node.js backend application designed to manage a database of restaurants, providing features such as searching, filtering, and pagination.

**Table of Contents**
Introduction
Features
Technologies
Installation
Usage
API Endpoints
Project Structure
Contributing
License
Introduction
KHI-EAT-APP-BACK-END is a RESTful API built with Node.js and Express. It allows users to search for restaurants based on city, cuisine, and other parameters. The project aims to demonstrate a clean and maintainable codebase using modern JavaScript practices.

**Features**

1. Search Restaurants: Search restaurants by city, cuisine, and search queries.
2. Pagination: Efficiently handle large datasets with pagination.
3. Sort Options: Sort search results based on different criteria.
4. Error Handling: Comprehensive error handling for robust API responses.

**Technologies**

1. Node.js
2. Express
3. MongoDB
4. Mongoose
5. TypeScript
6. JWT Authentication
7. Stripe
8. Cloudinary

**Installation**
To get a local copy up and running, follow these simple steps:

Clone the repository:

git clone https://github.com/Afaqrehman98/khi-eat-app-back-end.git
Navigate to the project directory:

cd MyNodeProject
Install dependencies:

npm install
Set up environment variables:
Create a .env file in the root directory and add the following variables:

## Mongodb Credentials

MONGODB_CONNECTON_STRING =

## Auth0 Credentials

AUTH0_AUDIENCE =
AUTH0_ISSUER_BASE_URL =

## Cloudinary Credentials

CLOUDINARY_CLOUD_NAME =
CLOUDINARY_API_KEY =
CLOUDINARY_API_SECRET =

## Stripe Details

FRONTEND_URL =
STRIPE_API_KEY =
STRIPE_WEBHOOK_SECRET =

npm start
Start the Server
To start the server, run:
npm run dev

**Project Structure**
Here's an overview of the project structure:

bash
Copy code
MyNodeProject/
├── controllers/ # Route handlers
│ └── MyUserController.ts
├── middleware/ # Custom middleware
│ └── jwtCheck.ts
├── models/ # Mongoose models
│ └── User.ts
├── routes/ # Express routes
│ └── myUserRoute.ts
├── index.ts # Entry point of the application
├── package.json
├── README.md
└── .env

**Contributing**
Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are greatly appreciated.

Fork the Project
Create your Feature Branch (git checkout -b feature/AmazingFeature)
Commit your Changes (git commit -m 'Add some AmazingFeature')
Push to the Branch (git push origin feature/AmazingFeature)
Open a Pull Request

**License**
Distributed under the MIT License. See LICENSE for more information.
