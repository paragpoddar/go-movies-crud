# go-movies-crud

Sample crud operation using Golang

## Quick run project:

```
git clone https://github.com/paragpoddar/go-movies-crud.git
cd go-movies-crud
go get
go run main.go
```

## Server API endpoints:

### Get all movies:

- Method: GET
- URL: http://localhost:8080/movies

### Get movie by id:

- Method: GET
- URL: http://localhost:8080/movies/{id}

### Create new movie:

- Method: POST
- URL: http://localhost:8080/movies
- JSON body:

```
{
    "id": "3",
    "isbn": "438229",
    "title": "Movie 3",
    "director": {
        "firstname": "Steve3",
        "lastname": "Smith3"
    }
}
```

### Update a movie:

- Method: PUT
- URL: http://localhost:8080/movies/{id}
- JSON body:

```
{
        "isbn": "438229",
        "title": "Movie 3",
        "director": {
            "firstname": "Steve33",
            "lastname": "Smith33"
        }
    }
```

### Delete a movie:

- Method: DELETE
- URL: http://localhost:8090/movies/{id}
