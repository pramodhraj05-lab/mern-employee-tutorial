# MERN Stack Tutorial — Employee Records

Completed the official MongoDB MERN Stack Tutorial as part of the B9IS130 Web Development module.

Tutorial reference: https://www.mongodb.com/resources/languages/mern-stack-tutorial

## Stack

- **M**ongoDB Atlas (cloud database)
- **E**xpress.js (REST API)
- **R**eact.js with Vite (frontend)
- **N**ode.js (runtime)

Styling with Tailwind CSS, routing with React Router DOM.

## Project Structure

```
mern-employee-tutorial/
├── server/           Express backend (port 5050)
│   ├── db/
│   │   └── connection.js
│   ├── routes/
│   │   └── record.js
│   ├── config.env    (not in git)
│   ├── package.json
│   └── server.js
└── client/           React frontend (port 5173)
    ├── src/
    │   ├── components/
    │   │   ├── Navbar.jsx
    │   │   ├── Record.jsx
    │   │   └── RecordList.jsx
    │   ├── App.jsx
    │   ├── main.jsx
    │   └── index.css
    └── package.json
```

## Setup

### Backend

```bash
cd server
npm install
```

Create `config.env`:
```
ATLAS_URI=mongodb+srv://<user>:<pass>@<cluster>.mongodb.net/employees?retryWrites=true&w=majority
PORT=5050
```

Run:
```bash
npm start
```

### Frontend

```bash
cd client
npm install
npm run dev
```

Open http://localhost:5173

## Features

- Create, read, update, delete employee records
- MongoDB Atlas as cloud database
- Three position levels: Intern, Junior, Senior
- Clean Tailwind-styled UI

## Author

Pramodh Selvaraj — Dublin Business School, B9IS130 Web Development
