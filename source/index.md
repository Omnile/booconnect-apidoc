---
title: API Reference

language_tabs:
- bash
- javascript

includes:

search: true

toc_footers:
- <a href='http://github.com/mpociot/documentarian'>Documentation Powered by Documentarian</a>
---
<!-- START_INFO -->
# Info

Welcome to the generated API reference.
[Get Postman Collection](http://booconnect.run/docs/collection.json)
<!-- END_INFO -->

#Account

Account Endpoints
<!-- START_4d7af81b146f8d07806e50e6833db15c -->
## Get Account.

Get the data of the authenticated user

> Example request:

```bash
curl -X GET "http://booconnect.run/api/v1/account" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "http://booconnect.run/api/v1/account",
    "method": "GET",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

> Example response:

```json
{
    "message": "Unauthenticated."
}
```

### HTTP Request
`GET api/v1/account`

`HEAD api/v1/account`


<!-- END_4d7af81b146f8d07806e50e6833db15c -->

<!-- START_700b6083aece5829c3fc1304c926b8c6 -->
## Update Account

Update account information

> Example request:

```bash
curl -X POST "http://booconnect.run/api/v1/account" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "http://booconnect.run/api/v1/account",
    "method": "POST",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```


### HTTP Request
`POST api/v1/account`


<!-- END_700b6083aece5829c3fc1304c926b8c6 -->

<!-- START_ab7447183d9e96e2392237f06ba821fc -->
## Update Account

Update the authenticated user account

> Example request:

```bash
curl -X PUT "http://booconnect.run/api/v1/account/{account}" \
-H "Accept: application/json" \
    -d "firstname"="aut" \
    -d "lastname"="aut" \
    -d "password"="aut" \
    -d "username"="aut" \
    -d "gender"="aut" \
    -d "phone"="aut" \

```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "http://booconnect.run/api/v1/account/{account}",
    "method": "PUT",
    "data": {
        "firstname": "aut",
        "lastname": "aut",
        "password": "aut",
        "username": "aut",
        "gender": "aut",
        "phone": "aut"
},
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```


### HTTP Request
`PUT api/v1/account/{account}`

`PATCH api/v1/account/{account}`

#### Parameters

Parameter | Type | Status | Description
--------- | ------- | ------- | ------- | -----------
    firstname | string |  required  | Maximum: `255`
    lastname | string |  required  | Maximum: `255`
    password | string |  required  | Minimum: `6`
    username | string |  required  | Minimum: `4`
    gender | string |  required  | Minimum: `4`
    phone | string |  required  | Minimum: `4`

<!-- END_ab7447183d9e96e2392237f06ba821fc -->

#Cart

Shopping cart endpoints
<!-- START_2e395b6f96faf612c0f5b034491ff221 -->
## Get Cart Items
List items in the shopping cart

> Example request:

```bash
curl -X GET "http://booconnect.run/api/v1/cart" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "http://booconnect.run/api/v1/cart",
    "method": "GET",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

> Example response:

```json
[]
```

### HTTP Request
`GET api/v1/cart`

`HEAD api/v1/cart`


<!-- END_2e395b6f96faf612c0f5b034491ff221 -->

<!-- START_b14a883b0d266dd902554e7afed0a2df -->
## Add Cart Item.

Add and item to the shopping cart

> Example request:

```bash
curl -X POST "http://booconnect.run/api/v1/cart" \
-H "Accept: application/json" \
    -d "row_id"="dolorum" \
    -d "qty"="1332598056" \

```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "http://booconnect.run/api/v1/cart",
    "method": "POST",
    "data": {
        "row_id": "dolorum",
        "qty": 1332598056
},
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```


### HTTP Request
`POST api/v1/cart`

#### Parameters

Parameter | Type | Status | Description
--------- | ------- | ------- | ------- | -----------
    row_id | string |  required  | Maximum: `255`
    qty | numeric |  required  | Minimum: `1`

<!-- END_b14a883b0d266dd902554e7afed0a2df -->

<!-- START_41412ed4b414717d56b418f4f9d05420 -->
## Update Cart Item Quantity
Update a specific cart Item.

> Example request:

```bash
curl -X PUT "http://booconnect.run/api/v1/cart/{cart}" \
-H "Accept: application/json" \
    -d "row_id"="error" \
    -d "qty"="1213516256" \

```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "http://booconnect.run/api/v1/cart/{cart}",
    "method": "PUT",
    "data": {
        "row_id": "error",
        "qty": 1213516256
},
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```


### HTTP Request
`PUT api/v1/cart/{cart}`

`PATCH api/v1/cart/{cart}`

#### Parameters

Parameter | Type | Status | Description
--------- | ------- | ------- | ------- | -----------
    row_id | string |  required  | 
    qty | numeric |  required  | Minimum: `1`

<!-- END_41412ed4b414717d56b418f4f9d05420 -->

<!-- START_a94e71cd52c25987988db15effc17eb8 -->
## Remove Cart Item
Remove an item from the shopping cart.

> Example request:

```bash
curl -X DELETE "http://booconnect.run/api/v1/cart/{cart}" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "http://booconnect.run/api/v1/cart/{cart}",
    "method": "DELETE",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```


### HTTP Request
`DELETE api/v1/cart/{cart}`


<!-- END_a94e71cd52c25987988db15effc17eb8 -->

#Checkout

Checkout resource endpoints
<!-- START_8832fc54ab8ccc4eebefe95893d5a8a0 -->
## Display a listing of the resource.

> Example request:

```bash
curl -X GET "http://booconnect.run/api/v1/checkout" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "http://booconnect.run/api/v1/checkout",
    "method": "GET",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

> Example response:

```json
{
    "message": "Unauthenticated."
}
```

### HTTP Request
`GET api/v1/checkout`

`HEAD api/v1/checkout`


<!-- END_8832fc54ab8ccc4eebefe95893d5a8a0 -->

<!-- START_333e99589c93fdc957a565172dec51f4 -->
## Show the form for creating a new resource.

> Example request:

```bash
curl -X GET "http://booconnect.run/api/v1/checkout/create" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "http://booconnect.run/api/v1/checkout/create",
    "method": "GET",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

> Example response:

```json
{
    "message": "Unauthenticated."
}
```

### HTTP Request
`GET api/v1/checkout/create`

`HEAD api/v1/checkout/create`


<!-- END_333e99589c93fdc957a565172dec51f4 -->

<!-- START_9bbc443150b7a418c39d54182d4019de -->
## Store a newly created resource in storage.

> Example request:

```bash
curl -X POST "http://booconnect.run/api/v1/checkout" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "http://booconnect.run/api/v1/checkout",
    "method": "POST",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```


### HTTP Request
`POST api/v1/checkout`


<!-- END_9bbc443150b7a418c39d54182d4019de -->

<!-- START_03e43aecc4f2b57f8ab1bf777dceef67 -->
## Display the specified resource.

> Example request:

```bash
curl -X GET "http://booconnect.run/api/v1/checkout/{checkout}" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "http://booconnect.run/api/v1/checkout/{checkout}",
    "method": "GET",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

> Example response:

```json
{
    "message": "Unauthenticated."
}
```

### HTTP Request
`GET api/v1/checkout/{checkout}`

`HEAD api/v1/checkout/{checkout}`


<!-- END_03e43aecc4f2b57f8ab1bf777dceef67 -->

<!-- START_706fd6209553a6543e0cacaae9de3cf6 -->
## Show the form for editing the specified resource.

> Example request:

```bash
curl -X GET "http://booconnect.run/api/v1/checkout/{checkout}/edit" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "http://booconnect.run/api/v1/checkout/{checkout}/edit",
    "method": "GET",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

> Example response:

```json
{
    "message": "Unauthenticated."
}
```

### HTTP Request
`GET api/v1/checkout/{checkout}/edit`

`HEAD api/v1/checkout/{checkout}/edit`


<!-- END_706fd6209553a6543e0cacaae9de3cf6 -->

<!-- START_f095fce42bce15acbb7df1f4d0cb8404 -->
## Update the specified resource in storage.

> Example request:

```bash
curl -X PUT "http://booconnect.run/api/v1/checkout/{checkout}" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "http://booconnect.run/api/v1/checkout/{checkout}",
    "method": "PUT",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```


### HTTP Request
`PUT api/v1/checkout/{checkout}`

`PATCH api/v1/checkout/{checkout}`


<!-- END_f095fce42bce15acbb7df1f4d0cb8404 -->

<!-- START_0b2ac70127b23deb237a44393c06fa66 -->
## Remove the specified resource from storage.

> Example request:

```bash
curl -X DELETE "http://booconnect.run/api/v1/checkout/{checkout}" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "http://booconnect.run/api/v1/checkout/{checkout}",
    "method": "DELETE",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```


### HTTP Request
`DELETE api/v1/checkout/{checkout}`


<!-- END_0b2ac70127b23deb237a44393c06fa66 -->

#Items

Items sold in resturants registered on BooConnect
<!-- START_6cb5fef850c2ae6d0de134a3409a8f1a -->
## Query All Items
Get a list of paginated items.

> Example request:

```bash
curl -X GET "http://booconnect.run/api/v1/items" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "http://booconnect.run/api/v1/items",
    "method": "GET",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

> Example response:

```json
{
    "current_page": 1,
    "data": [
        {
            "id": 1,
            "name": "Robb",
            "resturant_id": 30,
            "image": "https:\/\/lorempixel.com\/150\/150\/food\/?56430",
            "description": "Eligendi dolorem rem autem et nulla consequatur ipsam.",
            "price": 34,
            "user_id": 1,
            "measurement": "bowl",
            "quantity": 34,
            "deleted_at": null,
            "created_at": "2018-02-25 20:27:58",
            "updated_at": "2018-02-25 20:27:58",
            "formatted_price": "GHC 34.00"
        },
        {
            "id": 2,
            "name": "Bulah",
            "resturant_id": 23,
            "image": "https:\/\/lorempixel.com\/150\/150\/food\/?40389",
            "description": "Architecto aut incidunt consequatur necessitatibus.",
            "price": 3,
            "user_id": 1,
            "measurement": "plate",
            "quantity": 42,
            "deleted_at": null,
            "created_at": "2018-02-25 20:27:58",
            "updated_at": "2018-02-25 20:27:58",
            "formatted_price": "GHC 3.00"
        },
        {
            "id": 3,
            "name": "Perry",
            "resturant_id": 11,
            "image": "https:\/\/lorempixel.com\/150\/150\/food\/?68381",
            "description": "Et nostrum eligendi vero placeat minus.",
            "price": 32,
            "user_id": 1,
            "measurement": "bowl",
            "quantity": 22,
            "deleted_at": null,
            "created_at": "2018-02-25 20:27:58",
            "updated_at": "2018-02-25 20:27:58",
            "formatted_price": "GHC 32.00"
        },
        {
            "id": 4,
            "name": "Concepcion",
            "resturant_id": 64,
            "image": "https:\/\/lorempixel.com\/150\/150\/food\/?31334",
            "description": "Quis a aliquid in architecto officia iure.",
            "price": 55,
            "user_id": 1,
            "measurement": "plate",
            "quantity": 63,
            "deleted_at": null,
            "created_at": "2018-02-25 20:27:58",
            "updated_at": "2018-02-25 20:27:58",
            "formatted_price": "GHC 55.00"
        },
        {
            "id": 5,
            "name": "Astrid",
            "resturant_id": 39,
            "image": "https:\/\/lorempixel.com\/150\/150\/food\/?98180",
            "description": "Quibusdam qui soluta et rerum aut quisquam.",
            "price": 31,
            "user_id": 1,
            "measurement": "plate",
            "quantity": 8,
            "deleted_at": null,
            "created_at": "2018-02-25 20:27:58",
            "updated_at": "2018-02-25 20:27:58",
            "formatted_price": "GHC 31.00"
        },
        {
            "id": 6,
            "name": "Andreanne",
            "resturant_id": 66,
            "image": "https:\/\/lorempixel.com\/150\/150\/food\/?15712",
            "description": "Incidunt voluptates ea ab odio qui quisquam.",
            "price": 34,
            "user_id": 1,
            "measurement": "plate",
            "quantity": 4,
            "deleted_at": null,
            "created_at": "2018-02-25 20:27:58",
            "updated_at": "2018-02-25 20:27:58",
            "formatted_price": "GHC 34.00"
        },
        {
            "id": 7,
            "name": "Conor",
            "resturant_id": 53,
            "image": "https:\/\/lorempixel.com\/150\/150\/food\/?50284",
            "description": "Voluptas totam voluptatem non est ab pariatur quibusdam.",
            "price": 92,
            "user_id": 1,
            "measurement": "plate",
            "quantity": 37,
            "deleted_at": null,
            "created_at": "2018-02-25 20:27:58",
            "updated_at": "2018-02-25 20:27:58",
            "formatted_price": "GHC 92.00"
        },
        {
            "id": 8,
            "name": "Serenity",
            "resturant_id": 94,
            "image": "https:\/\/lorempixel.com\/150\/150\/food\/?76809",
            "description": "Ipsum repudiandae facilis est.",
            "price": 84,
            "user_id": 1,
            "measurement": "bowl",
            "quantity": 92,
            "deleted_at": null,
            "created_at": "2018-02-25 20:27:58",
            "updated_at": "2018-02-25 20:27:58",
            "formatted_price": "GHC 84.00"
        },
        {
            "id": 9,
            "name": "Delfina",
            "resturant_id": 3,
            "image": "https:\/\/lorempixel.com\/150\/150\/food\/?27094",
            "description": "Sit aut et repudiandae et praesentium.",
            "price": 72,
            "user_id": 1,
            "measurement": "bowl",
            "quantity": 23,
            "deleted_at": null,
            "created_at": "2018-02-25 20:27:58",
            "updated_at": "2018-02-25 20:27:58",
            "formatted_price": "GHC 72.00"
        },
        {
            "id": 10,
            "name": "Alvis",
            "resturant_id": 31,
            "image": "https:\/\/lorempixel.com\/150\/150\/food\/?83908",
            "description": "Temporibus porro facere recusandae sint iusto iusto optio perspiciatis.",
            "price": 9,
            "user_id": 1,
            "measurement": "plate",
            "quantity": 18,
            "deleted_at": null,
            "created_at": "2018-02-25 20:27:58",
            "updated_at": "2018-02-25 20:27:58",
            "formatted_price": "GHC 9.00"
        },
        {
            "id": 11,
            "name": "Jean",
            "resturant_id": 64,
            "image": "https:\/\/lorempixel.com\/150\/150\/food\/?36896",
            "description": "Aspernatur asperiores quo consequuntur sit nihil aut culpa.",
            "price": 27,
            "user_id": 1,
            "measurement": "plate",
            "quantity": 47,
            "deleted_at": null,
            "created_at": "2018-02-25 20:27:58",
            "updated_at": "2018-02-25 20:27:58",
            "formatted_price": "GHC 27.00"
        },
        {
            "id": 12,
            "name": "Favian",
            "resturant_id": 4,
            "image": "https:\/\/lorempixel.com\/150\/150\/food\/?44856",
            "description": "Temporibus sint consectetur aspernatur et at corrupti et.",
            "price": 48,
            "user_id": 1,
            "measurement": "plate",
            "quantity": 98,
            "deleted_at": null,
            "created_at": "2018-02-25 20:27:58",
            "updated_at": "2018-02-25 20:27:58",
            "formatted_price": "GHC 48.00"
        },
        {
            "id": 13,
            "name": "Rosamond",
            "resturant_id": 100,
            "image": "https:\/\/lorempixel.com\/150\/150\/food\/?23636",
            "description": "Quis molestias eligendi dicta quisquam eum.",
            "price": 14,
            "user_id": 1,
            "measurement": "plate",
            "quantity": 15,
            "deleted_at": null,
            "created_at": "2018-02-25 20:27:58",
            "updated_at": "2018-02-25 20:27:58",
            "formatted_price": "GHC 14.00"
        },
        {
            "id": 14,
            "name": "Effie",
            "resturant_id": 100,
            "image": "https:\/\/lorempixel.com\/150\/150\/food\/?70469",
            "description": "Et et tenetur vel ex officiis.",
            "price": 97,
            "user_id": 1,
            "measurement": "bowl",
            "quantity": 44,
            "deleted_at": null,
            "created_at": "2018-02-25 20:27:58",
            "updated_at": "2018-02-25 20:27:58",
            "formatted_price": "GHC 97.00"
        },
        {
            "id": 15,
            "name": "Roxanne",
            "resturant_id": 47,
            "image": "https:\/\/lorempixel.com\/150\/150\/food\/?50883",
            "description": "Officia in aut et et.",
            "price": 48,
            "user_id": 1,
            "measurement": "plate",
            "quantity": 55,
            "deleted_at": null,
            "created_at": "2018-02-25 20:27:58",
            "updated_at": "2018-02-25 20:27:58",
            "formatted_price": "GHC 48.00"
        },
        {
            "id": 16,
            "name": "Esmeralda",
            "resturant_id": 33,
            "image": "https:\/\/lorempixel.com\/150\/150\/food\/?97877",
            "description": "In distinctio ullam quis ipsum porro et exercitationem.",
            "price": 100,
            "user_id": 1,
            "measurement": "bowl",
            "quantity": 94,
            "deleted_at": null,
            "created_at": "2018-02-25 20:27:58",
            "updated_at": "2018-02-25 20:27:58",
            "formatted_price": "GHC 100.00"
        },
        {
            "id": 17,
            "name": "Raegan",
            "resturant_id": 93,
            "image": "https:\/\/lorempixel.com\/150\/150\/food\/?16070",
            "description": "Qui quasi dicta vero eum aspernatur.",
            "price": 4,
            "user_id": 1,
            "measurement": "plate",
            "quantity": 45,
            "deleted_at": null,
            "created_at": "2018-02-25 20:27:58",
            "updated_at": "2018-02-25 20:27:58",
            "formatted_price": "GHC 4.00"
        },
        {
            "id": 18,
            "name": "Jaime",
            "resturant_id": 68,
            "image": "https:\/\/lorempixel.com\/150\/150\/food\/?71194",
            "description": "Cupiditate omnis et quis consequatur in.",
            "price": 5,
            "user_id": 1,
            "measurement": "bowl",
            "quantity": 37,
            "deleted_at": null,
            "created_at": "2018-02-25 20:27:58",
            "updated_at": "2018-02-25 20:27:58",
            "formatted_price": "GHC 5.00"
        },
        {
            "id": 19,
            "name": "Demarco",
            "resturant_id": 54,
            "image": "https:\/\/lorempixel.com\/150\/150\/food\/?14682",
            "description": "Maxime eos ad neque sed aperiam sint aliquid.",
            "price": 3,
            "user_id": 1,
            "measurement": "bowl",
            "quantity": 90,
            "deleted_at": null,
            "created_at": "2018-02-25 20:27:58",
            "updated_at": "2018-02-25 20:27:58",
            "formatted_price": "GHC 3.00"
        },
        {
            "id": 20,
            "name": "Harrison",
            "resturant_id": 28,
            "image": "https:\/\/lorempixel.com\/150\/150\/food\/?83161",
            "description": "Consequatur non et officiis eius maxime exercitationem officiis sint.",
            "price": 21,
            "user_id": 1,
            "measurement": "bowl",
            "quantity": 47,
            "deleted_at": null,
            "created_at": "2018-02-25 20:27:58",
            "updated_at": "2018-02-25 20:27:58",
            "formatted_price": "GHC 21.00"
        }
    ],
    "first_page_url": "http:\/\/localhost\/api\/v1\/items?page=1",
    "from": 1,
    "last_page": 10,
    "last_page_url": "http:\/\/localhost\/api\/v1\/items?page=10",
    "next_page_url": "http:\/\/localhost\/api\/v1\/items?page=2",
    "path": "http:\/\/localhost\/api\/v1\/items",
    "per_page": 20,
    "prev_page_url": null,
    "to": 20,
    "total": 200
}
```

### HTTP Request
`GET api/v1/items`

`HEAD api/v1/items`


<!-- END_6cb5fef850c2ae6d0de134a3409a8f1a -->

<!-- START_c82686db284c3bd830a93127392241c8 -->
## Get Single Item

This will return a single item with it's
attributes and set of pictures.

> Example request:

```bash
curl -X GET "http://booconnect.run/api/v1/items/{item}" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "http://booconnect.run/api/v1/items/{item}",
    "method": "GET",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

> Example response:

```json
{
    "id": 1,
    "name": "Robb",
    "resturant_id": 30,
    "image": "https:\/\/lorempixel.com\/150\/150\/food\/?56430",
    "description": "Eligendi dolorem rem autem et nulla consequatur ipsam.",
    "price": 34,
    "user_id": 1,
    "measurement": "bowl",
    "quantity": 34,
    "deleted_at": null,
    "created_at": "2018-02-25 20:27:58",
    "updated_at": "2018-02-25 20:27:58",
    "formatted_price": "GHC 34.00",
    "pictures": null
}
```

### HTTP Request
`GET api/v1/items/{item}`

`HEAD api/v1/items/{item}`


<!-- END_c82686db284c3bd830a93127392241c8 -->

#Orders

Orders resource endpoints
<!-- START_985d87fa04a157f2d8b59ef306bf6f06 -->
## List all orders

Display a paginated list of all orders.

> Example request:

```bash
curl -X GET "http://booconnect.run/api/v1/orders" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "http://booconnect.run/api/v1/orders",
    "method": "GET",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

> Example response:

```json
{
    "message": "Unauthenticated."
}
```

### HTTP Request
`GET api/v1/orders`

`HEAD api/v1/orders`


<!-- END_985d87fa04a157f2d8b59ef306bf6f06 -->

<!-- START_325fd503850f4ce548c33deec4f9ddce -->
## Show the form for creating a new resource.

> Example request:

```bash
curl -X GET "http://booconnect.run/api/v1/orders/create" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "http://booconnect.run/api/v1/orders/create",
    "method": "GET",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

> Example response:

```json
{
    "message": "Unauthenticated."
}
```

### HTTP Request
`GET api/v1/orders/create`

`HEAD api/v1/orders/create`


<!-- END_325fd503850f4ce548c33deec4f9ddce -->

<!-- START_f34ad9d71f18dd67576cc6db60268192 -->
## Cancel an order

A user can cancel an order within the first NUMBER minuites after
making the order.

> Example request:

```bash
curl -X DELETE "http://booconnect.run/api/v1/orders/{order}" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "http://booconnect.run/api/v1/orders/{order}",
    "method": "DELETE",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```


### HTTP Request
`DELETE api/v1/orders/{order}`


<!-- END_f34ad9d71f18dd67576cc6db60268192 -->

#Resturant

Lists resturants registered on booconnect
<!-- START_e7cf6c6948344237400bf6ec99c2ee20 -->
## Query Resturants.

Get a paginated result of all resturants

> Example request:

```bash
curl -X GET "http://booconnect.run/api/v1/resturants" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "http://booconnect.run/api/v1/resturants",
    "method": "GET",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

> Example response:

```json
{
    "current_page": 1,
    "data": [
        {
            "id": 1,
            "name": "Roob, Schiller and Barrows",
            "phone": "+1-932-342-2954",
            "registration_no": "8923",
            "first_name": "Lucy",
            "last_name": "Bahringer",
            "user_id": "97",
            "image": "https:\/\/lorempixel.com\/150\/150\/nightlife\/?22931",
            "cover": "https:\/\/lorempixel.com\/500\/150\/technics\/?90873",
            "place": "Evangelinetown",
            "city": "Klingville",
            "state": "Kentucky",
            "country": "Luxembourg",
            "address": "50310 Pierre Key",
            "website": "kerluke.com",
            "description": "Deserunt qui tenetur voluptatem.",
            "phone_verified": 0,
            "email_verified": 0,
            "deleted_at": null,
            "created_at": "2018-02-25 20:27:58",
            "updated_at": "2018-02-25 20:27:58"
        },
        {
            "id": 2,
            "name": "Wilkinson-Sawayn",
            "phone": "1-393-425-3414 x3153",
            "registration_no": "30123",
            "first_name": "Adele",
            "last_name": "Yost",
            "user_id": "16",
            "image": "https:\/\/lorempixel.com\/150\/150\/nightlife\/?25149",
            "cover": "https:\/\/lorempixel.com\/500\/150\/technics\/?28349",
            "place": "Hilllbury",
            "city": "Lake Robin",
            "state": "New Hampshire",
            "country": "Sierra Leone",
            "address": "79948 Elwin Alley",
            "website": "cronin.com",
            "description": "Tempore quisquam adipisci ut quisquam incidunt.",
            "phone_verified": 0,
            "email_verified": 0,
            "deleted_at": null,
            "created_at": "2018-02-25 20:27:58",
            "updated_at": "2018-02-25 20:27:58"
        },
        {
            "id": 3,
            "name": "Medhurst, Torp and Keebler",
            "phone": "(607) 586-4017",
            "registration_no": "20551",
            "first_name": "Glennie",
            "last_name": "Ruecker",
            "user_id": "83",
            "image": "https:\/\/lorempixel.com\/150\/150\/nightlife\/?61688",
            "cover": "https:\/\/lorempixel.com\/500\/150\/technics\/?26405",
            "place": "West Helenside",
            "city": "Lake Emmaleemouth",
            "state": "Pennsylvania",
            "country": "Brunei Darussalam",
            "address": "9918 Spencer Meadow",
            "website": "cummings.biz",
            "description": "Et reprehenderit quia quis accusantium ut quis ullam.",
            "phone_verified": 0,
            "email_verified": 1,
            "deleted_at": null,
            "created_at": "2018-02-25 20:27:58",
            "updated_at": "2018-02-25 20:27:58"
        },
        {
            "id": 4,
            "name": "Deckow, Fahey and Aufderhar",
            "phone": "(947) 317-2547 x3685",
            "registration_no": "67336",
            "first_name": "Toy",
            "last_name": "Wyman",
            "user_id": "47",
            "image": "https:\/\/lorempixel.com\/150\/150\/nightlife\/?16477",
            "cover": "https:\/\/lorempixel.com\/500\/150\/technics\/?93671",
            "place": "Schusterport",
            "city": "Port Ellieton",
            "state": "Florida",
            "country": "India",
            "address": "2056 Gustave Via Suite 914",
            "website": "ortiz.org",
            "description": "Exercitationem quia reprehenderit voluptas.",
            "phone_verified": 0,
            "email_verified": 1,
            "deleted_at": null,
            "created_at": "2018-02-25 20:27:58",
            "updated_at": "2018-02-25 20:27:58"
        },
        {
            "id": 5,
            "name": "Flatley, Huels and Ledner",
            "phone": "413.202.0973 x2756",
            "registration_no": "1153",
            "first_name": "Isabell",
            "last_name": "Borer",
            "user_id": "34",
            "image": "https:\/\/lorempixel.com\/150\/150\/nightlife\/?93159",
            "cover": "https:\/\/lorempixel.com\/500\/150\/technics\/?70618",
            "place": "Port Amieview",
            "city": "Clemmiechester",
            "state": "Missouri",
            "country": "Reunion",
            "address": "8385 Kemmer Crescent Suite 522",
            "website": "kassulke.com",
            "description": "Quas nesciunt repellendus corporis aspernatur soluta velit odit enim.",
            "phone_verified": 1,
            "email_verified": 1,
            "deleted_at": null,
            "created_at": "2018-02-25 20:27:58",
            "updated_at": "2018-02-25 20:27:58"
        },
        {
            "id": 6,
            "name": "Hartmann, Bashirian and Cummerata",
            "phone": "386-478-8144",
            "registration_no": "24267",
            "first_name": "Kavon",
            "last_name": "Stiedemann",
            "user_id": "24",
            "image": "https:\/\/lorempixel.com\/150\/150\/nightlife\/?68402",
            "cover": "https:\/\/lorempixel.com\/500\/150\/technics\/?81717",
            "place": "Jakubowskiside",
            "city": "Turcotteland",
            "state": "Alabama",
            "country": "Poland",
            "address": "162 McDermott Branch",
            "website": "watsica.biz",
            "description": "Voluptatem necessitatibus delectus voluptate.",
            "phone_verified": 1,
            "email_verified": 0,
            "deleted_at": null,
            "created_at": "2018-02-25 20:27:58",
            "updated_at": "2018-02-25 20:27:58"
        },
        {
            "id": 7,
            "name": "Jacobs, Dooley and Okuneva",
            "phone": "1-490-679-8921 x962",
            "registration_no": "13094",
            "first_name": "Edward",
            "last_name": "Schiller",
            "user_id": "95",
            "image": "https:\/\/lorempixel.com\/150\/150\/nightlife\/?31243",
            "cover": "https:\/\/lorempixel.com\/500\/150\/technics\/?94369",
            "place": "East Cleveland",
            "city": "West Allanland",
            "state": "West Virginia",
            "country": "Belarus",
            "address": "3856 Bartell Avenue",
            "website": "barton.com",
            "description": "Fugiat repellat nisi dolorem sit deleniti.",
            "phone_verified": 1,
            "email_verified": 1,
            "deleted_at": null,
            "created_at": "2018-02-25 20:27:58",
            "updated_at": "2018-02-25 20:27:58"
        },
        {
            "id": 8,
            "name": "Kunze-Tromp",
            "phone": "498.933.2026",
            "registration_no": "14532",
            "first_name": "Stone",
            "last_name": "Gutmann",
            "user_id": "13",
            "image": "https:\/\/lorempixel.com\/150\/150\/nightlife\/?77766",
            "cover": "https:\/\/lorempixel.com\/500\/150\/technics\/?14580",
            "place": "Andreville",
            "city": "O'Konville",
            "state": "New Mexico",
            "country": "Hungary",
            "address": "2290 Jarrod Lights Suite 707",
            "website": "monahan.com",
            "description": "Neque eum perferendis doloribus ipsam unde et tempora.",
            "phone_verified": 0,
            "email_verified": 1,
            "deleted_at": null,
            "created_at": "2018-02-25 20:27:58",
            "updated_at": "2018-02-25 20:27:58"
        },
        {
            "id": 9,
            "name": "Swift, Gutkowski and VonRueden",
            "phone": "1-704-324-0902 x88248",
            "registration_no": "53275",
            "first_name": "Letha",
            "last_name": "Hagenes",
            "user_id": "87",
            "image": "https:\/\/lorempixel.com\/150\/150\/nightlife\/?24530",
            "cover": "https:\/\/lorempixel.com\/500\/150\/technics\/?19238",
            "place": "North Amelie",
            "city": "Asashire",
            "state": "Minnesota",
            "country": "Canada",
            "address": "580 Sally Villages Apt. 633",
            "website": "bosco.org",
            "description": "Non molestias unde reiciendis facilis ducimus itaque.",
            "phone_verified": 1,
            "email_verified": 0,
            "deleted_at": null,
            "created_at": "2018-02-25 20:27:58",
            "updated_at": "2018-02-25 20:27:58"
        },
        {
            "id": 10,
            "name": "Gulgowski, Schamberger and Jaskolski",
            "phone": "821-469-8691",
            "registration_no": "3410",
            "first_name": "Jailyn",
            "last_name": "Barrows",
            "user_id": "56",
            "image": "https:\/\/lorempixel.com\/150\/150\/nightlife\/?79982",
            "cover": "https:\/\/lorempixel.com\/500\/150\/technics\/?66151",
            "place": "North Brenden",
            "city": "Sofiashire",
            "state": "Washington",
            "country": "Venezuela",
            "address": "7528 Ramiro Shores",
            "website": "klocko.org",
            "description": "Amet laboriosam dolorum dicta architecto ut eum.",
            "phone_verified": 0,
            "email_verified": 0,
            "deleted_at": null,
            "created_at": "2018-02-25 20:27:58",
            "updated_at": "2018-02-25 20:27:58"
        },
        {
            "id": 11,
            "name": "Lynch Inc",
            "phone": "+1.497.796.6061",
            "registration_no": "76960",
            "first_name": "Jettie",
            "last_name": "Larkin",
            "user_id": "83",
            "image": "https:\/\/lorempixel.com\/150\/150\/nightlife\/?29903",
            "cover": "https:\/\/lorempixel.com\/500\/150\/technics\/?57780",
            "place": "Vaughntown",
            "city": "Brennonmouth",
            "state": "Wisconsin",
            "country": "Guinea-Bissau",
            "address": "8190 Katelin Gardens Apt. 633",
            "website": "spencer.com",
            "description": "In quas voluptatem architecto neque ea.",
            "phone_verified": 1,
            "email_verified": 0,
            "deleted_at": null,
            "created_at": "2018-02-25 20:27:58",
            "updated_at": "2018-02-25 20:27:58"
        },
        {
            "id": 12,
            "name": "Miller LLC",
            "phone": "(374) 746-3975",
            "registration_no": "47677",
            "first_name": "Juliana",
            "last_name": "Schulist",
            "user_id": "95",
            "image": "https:\/\/lorempixel.com\/150\/150\/nightlife\/?41888",
            "cover": "https:\/\/lorempixel.com\/500\/150\/technics\/?35624",
            "place": "South Neomatown",
            "city": "Gerholdberg",
            "state": "Virginia",
            "country": "Jamaica",
            "address": "98756 Myriam Circles Apt. 286",
            "website": "crooks.com",
            "description": "Animi voluptas dolorum dolore.",
            "phone_verified": 1,
            "email_verified": 1,
            "deleted_at": null,
            "created_at": "2018-02-25 20:27:58",
            "updated_at": "2018-02-25 20:27:58"
        },
        {
            "id": 13,
            "name": "Renner-Franecki",
            "phone": "(510) 994-0322 x38091",
            "registration_no": "73995",
            "first_name": "Kasandra",
            "last_name": "Brekke",
            "user_id": "99",
            "image": "https:\/\/lorempixel.com\/150\/150\/nightlife\/?40331",
            "cover": "https:\/\/lorempixel.com\/500\/150\/technics\/?10584",
            "place": "West Twila",
            "city": "Farrellberg",
            "state": "South Dakota",
            "country": "Antarctica (the territory South of 60 deg S)",
            "address": "209 Gaylord Road Apt. 471",
            "website": "farrell.com",
            "description": "Qui aut consequatur cumque recusandae error repellendus.",
            "phone_verified": 0,
            "email_verified": 0,
            "deleted_at": null,
            "created_at": "2018-02-25 20:27:58",
            "updated_at": "2018-02-25 20:27:58"
        },
        {
            "id": 14,
            "name": "Mertz-Wuckert",
            "phone": "+1.780.988.9573",
            "registration_no": "54158",
            "first_name": "Alexys",
            "last_name": "O'Hara",
            "user_id": "11",
            "image": "https:\/\/lorempixel.com\/150\/150\/nightlife\/?45634",
            "cover": "https:\/\/lorempixel.com\/500\/150\/technics\/?82792",
            "place": "Homenickport",
            "city": "New Quinten",
            "state": "Oklahoma",
            "country": "France",
            "address": "87731 Lilian Route Apt. 688",
            "website": "ziemann.com",
            "description": "Possimus sit quaerat rerum ut.",
            "phone_verified": 0,
            "email_verified": 0,
            "deleted_at": null,
            "created_at": "2018-02-25 20:27:58",
            "updated_at": "2018-02-25 20:27:58"
        },
        {
            "id": 15,
            "name": "Ankunding, Fahey and Stanton",
            "phone": "1-998-765-1147 x5234",
            "registration_no": "13547",
            "first_name": "Lila",
            "last_name": "Murray",
            "user_id": "44",
            "image": "https:\/\/lorempixel.com\/150\/150\/nightlife\/?39581",
            "cover": "https:\/\/lorempixel.com\/500\/150\/technics\/?24819",
            "place": "Port Candicestad",
            "city": "Hayesland",
            "state": "South Carolina",
            "country": "South Africa",
            "address": "228 Yolanda Manors Suite 315",
            "website": "auer.biz",
            "description": "Consectetur odio autem quia autem voluptas.",
            "phone_verified": 1,
            "email_verified": 1,
            "deleted_at": null,
            "created_at": "2018-02-25 20:27:58",
            "updated_at": "2018-02-25 20:27:58"
        },
        {
            "id": 16,
            "name": "Homenick Ltd",
            "phone": "+1-550-320-8752",
            "registration_no": "73115",
            "first_name": "Miracle",
            "last_name": "Langworth",
            "user_id": "46",
            "image": "https:\/\/lorempixel.com\/150\/150\/nightlife\/?73012",
            "cover": "https:\/\/lorempixel.com\/500\/150\/technics\/?14693",
            "place": "Fritschside",
            "city": "New Kyleview",
            "state": "Connecticut",
            "country": "Venezuela",
            "address": "919 Farrell Unions Apt. 852",
            "website": "muller.com",
            "description": "Voluptatibus culpa voluptatem perspiciatis quod impedit accusantium.",
            "phone_verified": 0,
            "email_verified": 1,
            "deleted_at": null,
            "created_at": "2018-02-25 20:27:58",
            "updated_at": "2018-02-25 20:27:58"
        },
        {
            "id": 17,
            "name": "Zboncak, Abbott and Schuppe",
            "phone": "1-682-497-6097",
            "registration_no": "15448",
            "first_name": "Otilia",
            "last_name": "Koelpin",
            "user_id": "21",
            "image": "https:\/\/lorempixel.com\/150\/150\/nightlife\/?39251",
            "cover": "https:\/\/lorempixel.com\/500\/150\/technics\/?66926",
            "place": "East Garnett",
            "city": "Trevorland",
            "state": "Arkansas",
            "country": "Portugal",
            "address": "80853 Grant Extensions Apt. 281",
            "website": "streich.org",
            "description": "Quis itaque iusto dolores est.",
            "phone_verified": 0,
            "email_verified": 1,
            "deleted_at": null,
            "created_at": "2018-02-25 20:27:58",
            "updated_at": "2018-02-25 20:27:58"
        },
        {
            "id": 18,
            "name": "Block, Waelchi and Marvin",
            "phone": "(494) 479-7663 x7692",
            "registration_no": "28181",
            "first_name": "Torrey",
            "last_name": "Harber",
            "user_id": "43",
            "image": "https:\/\/lorempixel.com\/150\/150\/nightlife\/?53091",
            "cover": "https:\/\/lorempixel.com\/500\/150\/technics\/?15306",
            "place": "Gulgowskishire",
            "city": "South Pietro",
            "state": "South Carolina",
            "country": "Oman",
            "address": "239 Webster Squares Apt. 574",
            "website": "nicolas.com",
            "description": "Consequuntur velit nulla eum et consequatur illum esse.",
            "phone_verified": 1,
            "email_verified": 0,
            "deleted_at": null,
            "created_at": "2018-02-25 20:27:58",
            "updated_at": "2018-02-25 20:27:58"
        },
        {
            "id": 19,
            "name": "Kris, Armstrong and Collins",
            "phone": "+1.418.700.1010",
            "registration_no": "96628",
            "first_name": "Kathleen",
            "last_name": "Vandervort",
            "user_id": "80",
            "image": "https:\/\/lorempixel.com\/150\/150\/nightlife\/?31747",
            "cover": "https:\/\/lorempixel.com\/500\/150\/technics\/?46227",
            "place": "East Davonmouth",
            "city": "Tressiemouth",
            "state": "Indiana",
            "country": "Peru",
            "address": "604 Jerad Port",
            "website": "runolfsson.com",
            "description": "Ea sed et debitis voluptate soluta.",
            "phone_verified": 1,
            "email_verified": 0,
            "deleted_at": null,
            "created_at": "2018-02-25 20:27:58",
            "updated_at": "2018-02-25 20:27:58"
        },
        {
            "id": 20,
            "name": "Mitchell-Barton",
            "phone": "542-268-2673 x71019",
            "registration_no": "3338",
            "first_name": "Helena",
            "last_name": "Thiel",
            "user_id": "58",
            "image": "https:\/\/lorempixel.com\/150\/150\/nightlife\/?22484",
            "cover": "https:\/\/lorempixel.com\/500\/150\/technics\/?69756",
            "place": "Buckridgehaven",
            "city": "Janessaton",
            "state": "Washington",
            "country": "Honduras",
            "address": "36754 Sporer View Apt. 668",
            "website": "walsh.info",
            "description": "Eum aperiam totam molestiae veritatis.",
            "phone_verified": 0,
            "email_verified": 1,
            "deleted_at": null,
            "created_at": "2018-02-25 20:27:58",
            "updated_at": "2018-02-25 20:27:58"
        }
    ],
    "first_page_url": "http:\/\/localhost\/api\/v1\/resturants?page=1",
    "from": 1,
    "last_page": 5,
    "last_page_url": "http:\/\/localhost\/api\/v1\/resturants?page=5",
    "next_page_url": "http:\/\/localhost\/api\/v1\/resturants?page=2",
    "path": "http:\/\/localhost\/api\/v1\/resturants",
    "per_page": 20,
    "prev_page_url": null,
    "to": 20,
    "total": 100
}
```

### HTTP Request
`GET api/v1/resturants`

`HEAD api/v1/resturants`


<!-- END_e7cf6c6948344237400bf6ec99c2ee20 -->

<!-- START_5c475d198dde109f40d350154d38700d -->
## Get Resturant
A resturant resource with pagination of it&#039;s items

> Example request:

```bash
curl -X GET "http://booconnect.run/api/v1/resturants/{resturant}" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "http://booconnect.run/api/v1/resturants/{resturant}",
    "method": "GET",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

> Example response:

```json
{
    "id": 1,
    "name": "Roob, Schiller and Barrows",
    "phone": "+1-932-342-2954",
    "registration_no": "8923",
    "first_name": "Lucy",
    "last_name": "Bahringer",
    "user_id": "97",
    "image": "https:\/\/lorempixel.com\/150\/150\/nightlife\/?22931",
    "cover": "https:\/\/lorempixel.com\/500\/150\/technics\/?90873",
    "place": "Evangelinetown",
    "city": "Klingville",
    "state": "Kentucky",
    "country": "Luxembourg",
    "address": "50310 Pierre Key",
    "website": "kerluke.com",
    "description": "Deserunt qui tenetur voluptatem.",
    "phone_verified": 0,
    "email_verified": 0,
    "deleted_at": null,
    "created_at": "2018-02-25 20:27:58",
    "updated_at": "2018-02-25 20:27:58",
    "items": {
        "current_page": 1,
        "data": [
            {
                "id": 107,
                "name": "Annamae",
                "resturant_id": 1,
                "image": "https:\/\/lorempixel.com\/150\/150\/food\/?72231",
                "description": "Sit praesentium quod doloribus.",
                "price": 46,
                "user_id": 1,
                "measurement": "bowl",
                "quantity": 6,
                "deleted_at": null,
                "created_at": "2018-02-25 20:27:58",
                "updated_at": "2018-02-25 20:27:58",
                "formatted_price": "GHC 46.00"
            }
        ],
        "first_page_url": "http:\/\/localhost\/api\/v1\/resturants\/1?page=1",
        "from": 1,
        "last_page": 1,
        "last_page_url": "http:\/\/localhost\/api\/v1\/resturants\/1?page=1",
        "next_page_url": null,
        "path": "http:\/\/localhost\/api\/v1\/resturants\/1",
        "per_page": 20,
        "prev_page_url": null,
        "to": 1,
        "total": 1
    }
}
```

### HTTP Request
`GET api/v1/resturants/{resturant}`

`HEAD api/v1/resturants/{resturant}`


<!-- END_5c475d198dde109f40d350154d38700d -->

#Verify

phone verification endpoints
<!-- START_aa558d00f323830cf03c0cdf62bf4f4f -->
## Get Status

Get verification status on authenticated user

> Example request:

```bash
curl -X GET "http://booconnect.run/api/v1/verify" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "http://booconnect.run/api/v1/verify",
    "method": "GET",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

> Example response:

```json
{
    "message": "Unauthenticated."
}
```

### HTTP Request
`GET api/v1/verify`

`HEAD api/v1/verify`


<!-- END_aa558d00f323830cf03c0cdf62bf4f4f -->

<!-- START_2986fe2644729ef9fa55818efeeda18c -->
## Verify OTP Code

Verify the OTP code that was sent to the authenticated user.

> Example request:

```bash
curl -X POST "http://booconnect.run/api/v1/verify" \
-H "Accept: application/json" \
    -d "phone"="938" \
    -d "token"="938" \

```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "http://booconnect.run/api/v1/verify",
    "method": "POST",
    "data": {
        "phone": 938,
        "token": 938
},
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```


### HTTP Request
`POST api/v1/verify`

#### Parameters

Parameter | Type | Status | Description
--------- | ------- | ------- | ------- | -----------
    phone | numeric |  required  | 
    token | numeric |  required  | Valid user token

<!-- END_2986fe2644729ef9fa55818efeeda18c -->

<!-- START_9a40a2f77477a7bb1ab9f8b37216fcec -->
## Show the form for editing the specified resource.

> Example request:

```bash
curl -X GET "http://booconnect.run/api/v1/verify/{verify}/edit" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "http://booconnect.run/api/v1/verify/{verify}/edit",
    "method": "GET",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

> Example response:

```json
{
    "message": "Unauthenticated."
}
```

### HTTP Request
`GET api/v1/verify/{verify}/edit`

`HEAD api/v1/verify/{verify}/edit`


<!-- END_9a40a2f77477a7bb1ab9f8b37216fcec -->

<!-- START_3b30ae7fc7fb9e3fea044b298668df82 -->
## Send Verification Code

A temporary verification code will be sent to the user.
This code will expire after 5 minuites.

> Example request:

```bash
curl -X PUT "http://booconnect.run/api/v1/verify/{verify}" \
-H "Accept: application/json" \
    -d "phone"="4903" \

```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "http://booconnect.run/api/v1/verify/{verify}",
    "method": "PUT",
    "data": {
        "phone": 4903
},
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```


### HTTP Request
`PUT api/v1/verify/{verify}`

`PATCH api/v1/verify/{verify}`

#### Parameters

Parameter | Type | Status | Description
--------- | ------- | ------- | ------- | -----------
    phone | numeric |  required  | 

<!-- END_3b30ae7fc7fb9e3fea044b298668df82 -->

#Wishlist

Item-Wishlist resource endpoints
<!-- START_3f8d78a807f16aa9a1195e047bf25b96 -->
## Get Items

Get paginated list of items on wishlist

> Example request:

```bash
curl -X GET "http://booconnect.run/api/v1/wishlist" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "http://booconnect.run/api/v1/wishlist",
    "method": "GET",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

> Example response:

```json
{
    "message": "Unauthenticated."
}
```

### HTTP Request
`GET api/v1/wishlist`

`HEAD api/v1/wishlist`


<!-- END_3f8d78a807f16aa9a1195e047bf25b96 -->

<!-- START_3e7cbd9fc15711ca2f1ba22883c3187f -->
## Add Wishlist item

Add an item to wishlist

> Example request:

```bash
curl -X POST "http://booconnect.run/api/v1/wishlist" \
-H "Accept: application/json" \
    -d "item_id"="1715927" \

```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "http://booconnect.run/api/v1/wishlist",
    "method": "POST",
    "data": {
        "item_id": 1715927
},
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```


### HTTP Request
`POST api/v1/wishlist`

#### Parameters

Parameter | Type | Status | Description
--------- | ------- | ------- | ------- | -----------
    item_id | numeric |  required  | Valid item id

<!-- END_3e7cbd9fc15711ca2f1ba22883c3187f -->

<!-- START_a5f004f583dea1e2c1062ef16977de92 -->
## Remove Item

Remove an item from the set of items on tieh wishlist.

> Example request:

```bash
curl -X DELETE "http://booconnect.run/api/v1/wishlist/{wishlist}" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "http://booconnect.run/api/v1/wishlist/{wishlist}",
    "method": "DELETE",
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```


### HTTP Request
`DELETE api/v1/wishlist/{wishlist}`


<!-- END_a5f004f583dea1e2c1062ef16977de92 -->

#general
<!-- START_e19c9e19f1f1208528a69cd2ef4c01dd -->
## Search

This will allow the clients to seach for items, resturants
or a combination of both.

> Example request:

```bash
curl -X GET "http://booconnect.run/api/v1/search" \
-H "Accept: application/json" \
    -d "query"="aut" \
    -d "type"="aut" \

```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "http://booconnect.run/api/v1/search",
    "method": "GET",
    "data": {
        "query": "aut",
        "type": "aut"
},
    "headers": {
        "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
    console.log(response);
});
```

> Example response:

```json
{
    "message": "The given data was invalid.",
    "errors": {
        "query": [
            "The query field is required."
        ]
    }
}
```

### HTTP Request
`GET api/v1/search`

`HEAD api/v1/search`

#### Parameters

Parameter | Type | Status | Description
--------- | ------- | ------- | ------- | -----------
    query | string |  required  | Maximum: `255`
    type | string |  optional  | 

<!-- END_e19c9e19f1f1208528a69cd2ef4c01dd -->

