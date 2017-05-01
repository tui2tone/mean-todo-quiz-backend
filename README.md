# Simple Todo Backend Quiz

- Implement a simple "Todo" API Backend for Webapp
- Can use every Node.js framework (Express, Hapi ...)
- Can use every DB (Mongodb, Nedb ....)

## MUST

- Must be implement API with RESTful Standard

## Cannot

- ** CANNOT you any boilerplate

## Plus

- Valid Node Standard or AirBNB Standard


## Spec

### Model

```
Todo
- text: String
- is_done Boolean
```

### API Spec


#### [GET] /todos

Response
```
{
	statusCode: "200",
	todos: [
		{
			id: "",
			title: "",
			isDone: false
		}
	]
}
```

#### [GET] /todo/:id

Response
```
{
	statusCode: "200",
	todo: {
		id: "",
		title: "",
		isDone: false
	}
}
```

#### [POST] /todos

Request Body
```
{
	todo: {
		title: "",
		isDone: false
	}
}
```

Response
```
{
	statusCode: "200",
	todo: {
		id: "",
		title: "",
		isDone: false
	}
}
```

#### [PUT] /todo/:id

Request Body
```
{
	todo: {
		title: "",
		isDone: false
	}
}
```

Response
```
{
	statusCode: "200",
	todo: {
		id: "",
		title: "",
		isDone: false
	}
}
```

#### [DEL] /todo/:id

Response (Success)
```
{
	statusCode: "200"
}
```

Response (Failed)
```
{
	statusCode: "500"
}
```