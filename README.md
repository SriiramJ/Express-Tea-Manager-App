# Tea Manager Application 🍵

A simple Node.js application for managing tea data using RESTful APIs. This application supports CRUD operations, utilizes Postman for testing, and is deployed as a production-ready site on [Render](https://render.com/).

---

## Features

- Add new tea entries.
- Retrieve all teas or specific tea details.
- Update tea details by ID.
- Delete tea entries by ID.
- Built with simplicity and scalability in mind.

---

## Technologies Used

- **Node.js**: Server-side JavaScript runtime.
- **Express.js**: Framework for building RESTful APIs.
- **Postman**: API testing and development.
- **Render**: Hosting for the production-ready application.

---

## API Endpoints

| Method | Endpoint         | Description              |
|--------|-------------------|--------------------------|
| POST   | `/teas`           | Add a new tea.           |
| GET    | `/teas`           | Get all teas.            |
| GET    | `/teas/:id`       | Get a tea by ID.         |
| PUT    | `/teas/:id`       | Update a tea by ID.      |
| DELETE | `/teas/:id`       | Delete a tea by ID.      |

---

## Installation

1. **Clone the Repository**  
   ```bash
   git clone https://github.com/SriiramJ/Express-Tea-Manager-App.git
   cd Express-Tea-Manager-App
   
2. **Install Dependencies**  
   ```bash
   npm install

   ## Testing with Postman

1. Import the API endpoints into Postman.
2. Use the following structure for the POST and PUT body:
   ```json
   {
     "name": "Green Tea",
     "price": 5
   }
