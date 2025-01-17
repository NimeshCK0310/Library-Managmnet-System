## Technologies Used

- **Vite:** A fast, opinionated web development build tool that serves as the frontend framework for this application.
- **React:** A widely-used JavaScript library for building user interfaces.
- **Express:** A web application framework for Node.js, used to create the backend server.
- **Node.js:** A JavaScript runtime that enables server-side development.
- **MongoDB:** A NoSQL database used to store and manage the library's data efficiently.

For development purpose run these commands in bash.
`To run without docker you should have local instance or mongodb cloud url for connecting`

1. To install all dependancies and run the backend server

```bash
npm install
PORT=3001 npm start
```

2. To install all dependancies and run the frontend

```bash
npm install
PORT=8080 VITE_PORT=http://localhost:3001 npm start
```

- The frontend will be accessible at http://localhost:8080
- The backend will be accessible at http://localhost:3001

---

Login Creadinitals for the frontend

- Admin section / Staff Signin
  - email: admin@email.com
  - password: `admin`
- User Section
  - email: asd1@asd.com
  - password: `asdasd`
