##Simple Api server, serving the resources from db.json

## Available Scripts

In the project directory, you can run:

### `npm install`

Install all the updates.

### `npm start`

Runs the app in the development mode.<br />
Open [http://localhost:3001](http://localhost:3000) to view it in the browser.

### `get http://localhost:3001/categories` returns
```[
  {
    "name": "Testing",
    "amount": 10,
    "uid": identifier
  },
  {
    "name": "Test",
    "amount": 77,
    "uid": uidentifier
  }
]
You can find more options for configuration at: https://www.npmjs.com/package/json-server