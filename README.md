# Instagram

Instagram using java Spring boot
## Framework

 - Java Spring Boot 
 - JPA
 - MySQL
 - Hibernate
 - lombok


## API Reference

#### Get all items

```http
  GET /user
```

```http
  GET /post
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
|  `userId`   | `Int` |  Post to get|
|  `postId`   | `Int` |  Post to get|



#### Post User

```http
  Post /User

```

##Sample JSON

{

    "age":20,
    "userId": 2,
    "firstName": "Yogesh",
    "lastName": "V",
    "email": "Yogesh@gmail.com",
    "phoneNumber":" 1832456789"
    
}

#### Update User

```http
  Put /User

```
| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
|  `userId`   | `Int` |  Post to get|

##Sample JSON

{

    "age":20,
    "firstName": "Yogesh",
    "lastName": "V",
    "email": "Yogesh@gmail.com",
    "phoneNumber":" 1832456789"
    
}
#### Add Posts

```http
  Post /post

```

##Sample JSON

{

    "postId":1,
    "userId": 2,
    "postData":"Hello",
    "user":
    
    {
    
    "age":20,
    
    "firstName": "Yogesh",
    "lastName": "V",
    "email": "Yogesh@gmail.com",
    "phoneNumber":" 1832456789"
    
}

    
}




## Authors

- [@Yogesh](https://github.com/Yogesh-VasanthaKumar/)


