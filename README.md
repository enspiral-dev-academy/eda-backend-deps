# EDA Backend Dependencies

To apply these dependencies:

    npm install eda-backend-deps

Available commands

* `lint-backend`
* `test-backend`
* `watch-backend-tests`
* `seed-backend-db`
* `migrate-backend-db`
* `rollback-backend-db`
* `start-backend-dev-server`

In your `package.json`, add

```js
"scripts": {
  "lint": "lint-backend",
  "test": "test-backend",
  "watch:tests": "watch-backend-tests",
  "db:seed": "seed-backend-db",
  "db:migrate": "migrate-backend-db",
  "db:rollback": "rollback-backend-db",
  "dev-server": "start-backend-dev-server"
},
```

The linter runs on `/server`.

Requirements

Your `knexfile.js` must be in your `/server/db` folder.
