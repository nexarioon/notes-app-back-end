# Notes app back end

REST API for a notes application, written for the Dicoding back-end class.

## Structure

```
src/
├── server.js     # server bootstrap
├── routes.js     # endpoint definitions
├── handler.js    # request and response logic
└── notes.js      # notes data
```

## Run

```bash
npm install
npm run start
```

## Lint

```bash
npm run lint
```

Data is kept in memory, so there is no database yet.
