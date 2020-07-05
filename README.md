# EDA Backend Dependencies

To apply these dependencies:

    npm install eda-backend-deps

Available commands

* `seed-backend-db`
* `migrate-backend-db`
* `rollback-backend-db`
* `start-backend-dev-server`

In your `package.json`, add

```js
"scripts": {
  "db:seed": "seed-backend-db",
  "db:migrate": "migrate-backend-db",
  "db:rollback": "rollback-backend-db",
  "dev-server": "start-backend-dev-server"
},
```

Requirements

Your `knexfile.js` must be in your `/server/db` folder.
