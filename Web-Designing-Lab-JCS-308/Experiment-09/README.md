# Express + MongoDB + JWT Authentication

1. Copy `.env.example` to `.env` and set a strong random `JWT_SECRET` and MongoDB URI.
2. `npm install && npm start`
3. Routes: `POST /register`, `POST /login`, `GET /profile` (Bearer token), `POST /logout`.

Never commit `.env`, real passwords, or JWTs. Use HTTPS and secure token handling in production. Logout removes the client token; stateless JWTs are not automatically revoked.
