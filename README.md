# EDA Backend Dependencies

To apply these dependencies:

    npm install eda-backend-deps

Available commands

* `backend-db`
* `backend-dev-server`

In your `package.json`, add

```js
"scripts": {
  "db": "backend-db",
  "dev-server": "backend-dev-server"
},
```

Requirements

Your `knexfile.js` must be in your `/server/db` folder.
