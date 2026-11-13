# Book Collection REST API

```bash
npm install
npm start
```
Base URL: `http://localhost:3000`

| Method | Endpoint | Action |
|---|---|---|
| GET | `/books` | List books |
| GET | `/books/:id` | Read one book |
| POST | `/books` | Create book (`{ "title": "...", "author": "..." }`) |
| PUT | `/books/:id` | Update book |
| DELETE | `/books/:id` | Delete book |
