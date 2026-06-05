# Linkit — Frontend

The React frontend for Linkly, a full-stack URL shortener with authentication, link management, and click analytics.

**Backend repo:** [linkit](https://github.com/ArjavTripathi/linkit)

---

## Tech Stack

![React](https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat&logo=vite&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![CSS](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)

---

## Features

- User registration and login with JWT-based auth
- Dashboard to create, view, and manage short links
- Per-link analytics display (click counts)
- Protected routes for authenticated users
- Communicates with the Linkly Spring Boot backend

---

## Running Locally

**Prerequisites:** Node.js 18+, npm

```bash
git clone https://github.com/ArjavTripathi/Linkly-frontend
cd Linkly-frontend
npm install
```

Configure the backend URL in `.env`:

```env
VITE_API_BASE_URL=http://localhost:8080
```

Then run:

```bash
npm run dev
```

App starts at `http://localhost:5173`

---

## Related

- [Linkly Backend](https://github.com/ArjavTripathi/linkly) — Spring Boot + PostgreSQL + JWT backend
