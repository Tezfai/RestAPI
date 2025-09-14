**🌐 REST API (Scrimba Node.js Course)**

A RESTful API built with Node.js as part of the Scrimba backend development course. This project demonstrates how to design and implement structured endpoints for data exchange.

**🚀 Features**

RESTful routes with support for GET, POST, PUT, and DELETE operations

JSON-based request and response handling

Modularized server logic for scalability and maintainability

Structured error handling with proper HTTP status codes

Example database + data utilities included

**🛠 Tech Stack**

Runtime: Node.js

Modules: HTTP, CORS

Data Format: JSON

rest-api/

│── data/            # Example dataset

│── database/        # Database handling logic

│── utils/           # Helper functions

│── server.js        # Entry point, sets up routes

│── package.json     # Project dependencies

│── README.md        # Documentation

**⚙️ Setup & Installation**

_Clone the repository_:

git clone https://github.com/Tezfai/rest-api.git

cd rest-api


_Install dependencies:_

npm install


_Run the server:_

node server.js


_The API will be available at:_

http://localhost:3000

**📸 Demo Request (example)**

GET request to fetch all items:

curl http://localhost:3000/items


Response:

[
  { "id": 1, "name": "Item 1" },
  { "id": 2, "name": "Item 2" }
]

**🎯 Purpose**

This project was created to practice backend development with Node.js. It demonstrates how to set up routes, manage JSON data, and structure a small but scalable API.

**🔮 Future Improvements**

Upgrade the server to Express.js for easier routing and middleware support

Integrate a real database (MongoDB or PostgreSQL) instead of local JSON files

Add authentication & authorization for secure endpoints

Write unit tests for routes and data handling

Deploy to a cloud provider (Heroku, Vercel, or Render) for live access
