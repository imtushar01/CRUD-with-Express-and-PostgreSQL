## Node + Express + PostgreSQL CRUD API

This project is a basic REST API built using:

- Node.js
- Express.js
- PostgreSQL (with `pg` client)

### Features
- Create new records (`POST /postData`)
- Read all records (`GET /fetchData`)
- Read record by ID (`GET /fetchbyId/:id`)
- Update record by ID (`PUT /update/:id`)
- Delete record by ID (`DELETE /delete/:id`)

### Setup
1. Ensure PostgreSQL is running.
2. Create a DB named `demopost` and a table `demotable (id INT PRIMARY KEY, name TEXT)`
3. Run the server: `node index.js`

Default port: `3000`
