# Spring-REST-API-Using-MySQL
Product Api Created Using Spring Boot, Hibernate, JPA, MySQL

## API Endpoints
✔️ `/products` returns all products

✔️ `/product/{name}` searches the DB by name and returns the product details

✔️ `/productById/{id}` returns product details of the product with id

✔️ `/addProduct` takes JSON object and adds it to product table

✔️ `/addProducts` takes multiple JSON objects to add to product table

✔️ `/update` updates product and returns the same product

✔️ `/delete` deletes and returns success message as string

### Example Input for `/addProduct`

```
{
    "name":"light bulb",
    "description":"light up your life",
    "price":9.94
}
```

### Example Output for `/products`

```
[
    {
        "id": 1,
        "name": "book",
        "description": "a book for you to read",
        "price": 11.99
    },
    {
        "id": 2,
        "name": "chair",
        "description": "chair for you to sit",
        "price": 25.99
    },
    {
        "id": 3,
        "name": "earphone",
        "description": "for amazing music",
        "price": 19.99
    },
    {
        "id": 4,
        "name": "light bulb",
        "description": "light up your life",
        "price": 9.94
    }
]
```
