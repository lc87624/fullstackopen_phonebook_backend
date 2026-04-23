# Phonebook Backend

Express.js REST API for a phonebook (Fullstack Open course exercise).

## Stack
- Node.js + Express 5
- Morgan logging, CORS enabled
- In-memory data (no database)

## Running
- Workflow `Start application` runs `npm start` on port 5000 (host `0.0.0.0`).
- Server entry: `index.js`. Port is `process.env.PORT || 5000`.

## Endpoints
- `GET /` — landing page with links
- `GET /info` — entry count + timestamp
- `GET /api/persons` — list all
- `GET /api/persons/:id` — get one
- `POST /api/persons` — create (`name`, `number`)
- `DELETE /api/persons/:id` — delete

## Deployment
Configured as `autoscale` running `npm start`.
