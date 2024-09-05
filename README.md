# SSR Editor

Starter project for DV1677 JSRamverk

dbwebb/jsramverk/

1. Run npm install in ssr-editor directory to install dependencies

2. Add a default port in app.mjs (3000).

3. Run bash ./db/reset_db.bash

4. Run node app.mjs

5. Update docs.mjs:
    getOne() - Add rowid in SELECT query to use it in doc.ejs form

    Add updateOne()

6. Update app.mjs:
    Change from 'app.post("/"...)' to 'app.post("/add"...)'

    Add new route 'app.post("/update"...)'

7. Update /views:
    Update index.ejs - add form with action="/add" to create a new document.

    Update doc.ejs - update form with action="/update" to update a document.

    Update doc.ejs - add hidden input doc.id to pass variable to /update route.

We have chosen to work with React as a frontend framework for this project.
