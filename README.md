# mockapi
MockApi - DB and API information

[https://mockapi.io/](https://mockapi.io/)

## API Endpoint

https://5f9422429ecf720016bfc338.mockapi.io/api/v1/:endpoint

## Sample Data - JSON

```json
[
  {
    "id": "1",
    "createdAt": "Thu Dec 10 2020 20:57:15 GMT+0530 (India Standard Time)",
    "name": "Britney Nader",
    "status": false
  },
  {
    "id": "2",
    "createdAt": "Thu Dec 10 2020 01:09:03 GMT+0530 (India Standard Time)",
    "name": "Sibyl Gorczany",
    "status": true
  }
]  

```

## API's 

| HTTP METHOD | POST            | GET       | PUT         | DELETE |
| ----------- | --------------- | --------- | ----------- | ------ |
| CRUD OPR    | CREATE          | READ      | UPDATE      | DELETE |
| /todo_data       | Create new ToDo | List 1 or more ToDos | Update 1 Todo | Delete 1 ToDo |

```
GET /todo_data

GET /todo_data/:id

POST /todo_data

PUT /todo_data/:id

DELETE /todo_data/:id
```


# PostMan Automate Testing

## MyToDo App

[![Run in Postman](https://run.pstmn.io/button.svg)](https://app.getpostman.com/run-collection/75acbec7d75cdf59bf04)

> I would suggest use the Desktop Tool to run the collection

[Download the Collection and View in your Desktop Postman Tool](https://www.getpostman.com/collections/a18cc63176e2c2a3628e)
