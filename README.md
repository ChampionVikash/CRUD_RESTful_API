# CRUD RESTful API with MVC Architecture

A simple CRUD (Create, Read, Update, Delete) RESTful API for managing user data, built using the Model-View-Controller (MVC) architecture. The project utilizes Node.js, Express, and MongoDB.

## Features

- Create new users
- Retrieve a list of all users
- Retrieve a specific user by ID
- Update user information
- Delete a user

## MVC Architecture
The project follows the Model-View-Controller (MVC) architectural pattern:

- Models: Defined in the models folder, responsible for interacting with the database (e.g., MongoDB).
- Views: No traditional views in this API as it primarily deals with data. Views are often handled by the client consuming the API.
- Controllers: Defined in the controllers folder, handle the application logic and interact with models based on the incoming requests.


## Getting Started

### Prerequisites

Make sure you have the following installed:

- [Node.js](https://nodejs.org/)
- [MongoDB](https://www.mongodb.com/try/download/community)


## API Endpoints
- GET /user: Retrieve all users.
- POST /user: Create a new user.
- GET /user/:id: Retrieve a specific user by ID.
- PATCH /user/:id: Update a user by ID.
- DELETE /user/:id: Delete a user by ID.


### Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/your-username/CRUD_RESTful_API.git
   cd CRUD_RESTful_API

 2. **Install dependencies:**
    `npm install`

 3. **Configure MongoDB::**
    Make sure MongoDB is running, and update the connection string in connections.js if needed.

 4. **Start the server::**
     `npm start`

