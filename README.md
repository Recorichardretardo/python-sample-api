# Python sample api using Flask



## Flask Install

```
pip install Flask

pip install flask-restful
```

## Service Endpoints

### get All
```
http://localhost:8080/students/
```

### post

```
http://localhost:8080/students/

body :
====== 

{
    "name": "Rolf",
    "age": 20,
    "spec": "biology"
}

```

###  get by id

```
http://localhost:8080/students/2
```

### put

```
http://localhost:8080/students/3

body:
=====

{
    "name": "Paul",
    "age": 26,
    "spec": "programming"
}

```

### delete

```
http://localhost:8080/students/3
```
