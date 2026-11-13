# MERN Taskflow

## Backend
`cd backend && cp .env.example .env && npm install && npm start`
Set `MONGODB_URI` and `CLIENT_ORIGIN` in `.env`.

## Frontend
`cd frontend && npm install && npm run dev`
Set `VITE_API_URL` to the deployed API URL when deploying.

API: `GET/POST /api/tasks`, `PATCH/DELETE /api/tasks/:id`, `GET /health`. Keep `.env` out of Git. Deploy frontend and backend, configure CORS, MongoDB network access and environment variables, then test CRUD end-to-end.
