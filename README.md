# JSON-Server

https://www.npmjs.com/package/json-server

## Installation
```
  npm install -g json-server
```
## Create Database JSON file
Make a database JSON file name <db-filename.json><br>
Ex: db.json
```
  {
    "todos": [
      {
        "task": "Task 1",
        "completed": false,
        "date": "2023-11-05T21:07:00.734Z",
        "id": 1
      },
      {
        "task": "Task 2",
        "completed": true,
        "date": "2023-11-05T21:07:02.498Z",
        "id": 2
      },
      {
        "task": "Task 3",
        "completed": false,
        "date": "2023-11-05T21:07:05.141Z",
        "id": 3
      }
    ]
  }
```

## Run to view the server
```
  json-server <db-filename> --watch
```
Ex:
```
  json-server db.json --watch
```
Copy 'Resources' to the browser
Ex:
```
  http://localhost:3000/todos
```
