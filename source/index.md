---
title: BooConnect API Reference

language_tabs:
- bash
- javascript

includes:
- errors

search: true

toc_footers:
- <a href="#">Some footer message comes here.</a>
---
<!-- START_INFO -->
# Info

Here's tsshe complete documentaiton of the avialable API Endpoints.
[Get Postman Collection](http://booconnect.run/docs/collection.json)

# Authentication

BooConnect uses API keys to allow access to the API.
A new api key will be granted when loed in and thereafter, the server will expect a stateless call with the api key set as an authorization bearer.

The BooConnect server expects for the API key to be included in all API requests to the server in a header that looks like the following:

Authorization: meowmeowmeow
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
---------|-------|-------|-------|-----------
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
    -d "item_id"="dolorum" \
    -d "qty"="1332598056" \

```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "http://booconnect.run/api/v1/cart",
    "method": "POST",
    "data": {
        "item_id": "dolorum",
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
---------|-------|-------|-------|-----------
    item_id | string |  required  | Maximum: `255`
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
---------|-------|-------|-------|-----------
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

#Items

Items sold in restaurants registered on BooConnect
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
            "name": "Kaden",
            "restaurant_id": 1,
            "image": "https:\/\/lorempixel.com\/150\/150\/food\/?50010",
            "description": "Non nulla facilis cumque voluptas.",
            "price": 2,
            "user_id": 1,
            "measurement": "plate",
            "quantity": 2,
            "deleted_at": null,
            "created_at": "2018-03-07 23:50:50",
            "updated_at": "2018-03-07 23:50:50",
            "formatted_price": "GHC 2.00",
            "cart": [],
            "qty": 0,
            "in_cart": false
        },
        {
            "id": 2,
            "name": "Crawford",
            "restaurant_id": 1,
            "image": "https:\/\/lorempixel.com\/150\/150\/food\/?60423",
            "description": "Magni quia dolore non et voluptas facilis.",
            "price": 1,
            "user_id": 1,
            "measurement": "bowl",
            "quantity": 2,
            "deleted_at": null,
            "created_at": "2018-03-07 23:50:50",
            "updated_at": "2018-03-07 23:50:50",
            "formatted_price": "GHC 1.00",
            "cart": [],
            "qty": 0,
            "in_cart": false
        }
    ],
    "first_page_url": "http:\/\/localhost\/api\/v1\/items?page=1",
    "from": 1,
    "last_page": 1,
    "last_page_url": "http:\/\/localhost\/api\/v1\/items?page=1",
    "next_page_url": null,
    "path": "http:\/\/localhost\/api\/v1\/items",
    "per_page": 20,
    "prev_page_url": null,
    "to": 2,
    "total": 2
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
    "name": "Kaden",
    "restaurant_id": 1,
    "image": "https:\/\/lorempixel.com\/150\/150\/food\/?50010",
    "description": "Non nulla facilis cumque voluptas.",
    "price": 2,
    "user_id": 1,
    "measurement": "plate",
    "quantity": 2,
    "deleted_at": null,
    "created_at": "2018-03-07 23:50:50",
    "updated_at": "2018-03-07 23:50:50",
    "formatted_price": "GHC 2.00",
    "cart": [],
    "qty": 0,
    "in_cart": false,
    "pictures": null,
    "rating": []
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

#Rating

Rating resource endpoints
<!-- START_29bf60e1b9af05cfceb71303c89672bf -->
## List all ratings

List ratings related to either an item or restaurant

> Example request:

```bash
curl -X GET "http://booconnect.run/api/v1/ratings" \
-H "Accept: application/json" \
    -d "rateable_type"="item" \

```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "http://booconnect.run/api/v1/ratings",
    "method": "GET",
    "data": {
        "rateable_type": "item"
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
        "rateable_type": [
            "The rateable type field is required."
        ]
    }
}
```

### HTTP Request

`GET api/v1/ratings`

`HEAD api/v1/ratings`


#### Parameters

Parameter | Type | Status | Description
---------|-------|-------|-------|-----------
    rateable_type | string |  required  | `item` or `restaurant`

<!-- END_29bf60e1b9af05cfceb71303c89672bf -->

<!-- START_23b15c7d5284e81aedd1ffed5d136477 -->
## Add Rating

Add rating to an item or restaurant

> Example request:

```bash
curl -X POST "http://booconnect.run/api/v1/ratings" \
-H "Accept: application/json" \
    -d "rating"="2" \
    -d "rateable_id"="30647" \
    -d "rateable_type"="item" \
    -d "comment"="dignissimos" \

```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "http://booconnect.run/api/v1/ratings",
    "method": "POST",
    "data": {
        "rating": 2,
        "rateable_id": 30647,
        "rateable_type": "item",
        "comment": "dignissimos"
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

`POST api/v1/ratings`


#### Parameters

Parameter | Type | Status | Description
---------|-------|-------|-------|-----------
    rating | numeric |  required  | Minimum: `1` Maximum: `5`
    rateable_id | numeric |  required  | 
    rateable_type | string |  optional  | `item` or `restaurant`
    comment | string |  optional  | 

<!-- END_23b15c7d5284e81aedd1ffed5d136477 -->

<!-- START_f8ed95373eb35795a11d4b82074ab8f2 -->
## Get Rating

Get a single rating review

> Example request:

```bash
curl -X GET "http://booconnect.run/api/v1/ratings/{rating}" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "http://booconnect.run/api/v1/ratings/{rating}",
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
    "rating": 2,
    "user_id": 2,
    "comment": "Ipsam incidunt odit facere non.",
    "rateable_id": 2,
    "rateable_type": "",
    "deleted_at": null,
    "created_at": "2018-03-07 23:50:50",
    "updated_at": "2018-03-07 23:50:50"
}
```

### HTTP Request

`GET api/v1/ratings/{rating}`

`HEAD api/v1/ratings/{rating}`


<!-- END_f8ed95373eb35795a11d4b82074ab8f2 -->

<!-- START_20925b688666ad5188db58354b8235fb -->
## Delete a rating review

Delete a rating for either an item or restaurant

> Example request:

```bash
curl -X DELETE "http://booconnect.run/api/v1/ratings/{rating}" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "http://booconnect.run/api/v1/ratings/{rating}",
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

`DELETE api/v1/ratings/{rating}`


<!-- END_20925b688666ad5188db58354b8235fb -->

#Restaurant

Lists restaurants registered on booconnect
<!-- START_d4047c448c5be09c76c8b41d01754863 -->
## Query Restaurants.

Get a paginated result of all restaurants

> Example request:

```bash
curl -X GET "http://booconnect.run/api/v1/restaurants" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "http://booconnect.run/api/v1/restaurants",
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
            "name": "Klein Ltd",
            "phone": "(681) 872-3523",
            "registration_no": "28939",
            "first_name": "Eleonore",
            "last_name": "Kunde",
            "user_id": "1",
            "image": "https:\/\/lorempixel.com\/150\/150\/nightlife\/?12938",
            "cover": "https:\/\/lorempixel.com\/500\/150\/technics\/?50408",
            "place": "Bednarfort",
            "city": "New Donato",
            "state": "Michigan",
            "country": "Saint Kitts and Nevis",
            "address": "19260 Rippin Pine",
            "website": "lakin.com",
            "description": "Exercitationem enim voluptatem non dolorem.",
            "phone_verified": 0,
            "email_verified": 1,
            "deleted_at": null,
            "created_at": "2018-03-07 23:50:50",
            "updated_at": "2018-03-07 23:50:50"
        },
        {
            "id": 2,
            "name": "Funk, Green and Ondricka",
            "phone": "642.964.6438",
            "registration_no": "41307",
            "first_name": "Ricardo",
            "last_name": "Cummerata",
            "user_id": "2",
            "image": "https:\/\/lorempixel.com\/150\/150\/nightlife\/?94190",
            "cover": "https:\/\/lorempixel.com\/500\/150\/technics\/?58087",
            "place": "Kadinborough",
            "city": "Dannieberg",
            "state": "West Virginia",
            "country": "Oman",
            "address": "26064 Nova Place Apt. 562",
            "website": "schowalter.com",
            "description": "Voluptate expedita sed quo ut illum ipsa.",
            "phone_verified": 1,
            "email_verified": 1,
            "deleted_at": null,
            "created_at": "2018-03-07 23:50:50",
            "updated_at": "2018-03-07 23:50:50"
        }
    ],
    "first_page_url": "http:\/\/localhost\/api\/v1\/restaurants?page=1",
    "from": 1,
    "last_page": 1,
    "last_page_url": "http:\/\/localhost\/api\/v1\/restaurants?page=1",
    "next_page_url": null,
    "path": "http:\/\/localhost\/api\/v1\/restaurants",
    "per_page": 20,
    "prev_page_url": null,
    "to": 2,
    "total": 2
}
```

### HTTP Request

`GET api/v1/restaurants`

`HEAD api/v1/restaurants`


<!-- END_d4047c448c5be09c76c8b41d01754863 -->

<!-- START_e0300b8b707c1db9b160b9d5a851ae0a -->
## Get Restaurant
A restaurant resource with pagination of it&#039;s items

> Example request:

```bash
curl -X GET "http://booconnect.run/api/v1/restaurants/{restaurant}" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "http://booconnect.run/api/v1/restaurants/{restaurant}",
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
    "name": "Klein Ltd",
    "phone": "(681) 872-3523",
    "registration_no": "28939",
    "first_name": "Eleonore",
    "last_name": "Kunde",
    "user_id": "1",
    "image": "https:\/\/lorempixel.com\/150\/150\/nightlife\/?12938",
    "cover": "https:\/\/lorempixel.com\/500\/150\/technics\/?50408",
    "place": "Bednarfort",
    "city": "New Donato",
    "state": "Michigan",
    "country": "Saint Kitts and Nevis",
    "address": "19260 Rippin Pine",
    "website": "lakin.com",
    "description": "Exercitationem enim voluptatem non dolorem.",
    "phone_verified": 0,
    "email_verified": 1,
    "deleted_at": null,
    "created_at": "2018-03-07 23:50:50",
    "updated_at": "2018-03-07 23:50:50",
    "items": {
        "current_page": 1,
        "data": [
            {
                "id": 1,
                "name": "Kaden",
                "restaurant_id": 1,
                "image": "https:\/\/lorempixel.com\/150\/150\/food\/?50010",
                "description": "Non nulla facilis cumque voluptas.",
                "price": 2,
                "user_id": 1,
                "measurement": "plate",
                "quantity": 2,
                "deleted_at": null,
                "created_at": "2018-03-07 23:50:50",
                "updated_at": "2018-03-07 23:50:50",
                "formatted_price": "GHC 2.00",
                "cart": [],
                "qty": 0,
                "in_cart": false
            },
            {
                "id": 2,
                "name": "Crawford",
                "restaurant_id": 1,
                "image": "https:\/\/lorempixel.com\/150\/150\/food\/?60423",
                "description": "Magni quia dolore non et voluptas facilis.",
                "price": 1,
                "user_id": 1,
                "measurement": "bowl",
                "quantity": 2,
                "deleted_at": null,
                "created_at": "2018-03-07 23:50:50",
                "updated_at": "2018-03-07 23:50:50",
                "formatted_price": "GHC 1.00",
                "cart": [],
                "qty": 0,
                "in_cart": false
            }
        ],
        "first_page_url": "http:\/\/localhost\/api\/v1\/restaurants\/1?page=1",
        "from": 1,
        "last_page": 1,
        "last_page_url": "http:\/\/localhost\/api\/v1\/restaurants\/1?page=1",
        "next_page_url": null,
        "path": "http:\/\/localhost\/api\/v1\/restaurants\/1",
        "per_page": 20,
        "prev_page_url": null,
        "to": 2,
        "total": 2
    }
}
```

### HTTP Request

`GET api/v1/restaurants/{restaurant}`

`HEAD api/v1/restaurants/{restaurant}`


<!-- END_e0300b8b707c1db9b160b9d5a851ae0a -->

#Search

Search for either Restaurants or Items
<!-- START_e19c9e19f1f1208528a69cd2ef4c01dd -->
## Search

This will allow the clients to seach for items, restaurants
or a combination of both.

> Example request:

```bash
curl -X GET "http://booconnect.run/api/v1/search" \
-H "Accept: application/json" \
    -d "query"="aut" \
    -d "type"="items" \

```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "http://booconnect.run/api/v1/search",
    "method": "GET",
    "data": {
        "query": "aut",
        "type": "items"
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
---------|-------|-------|-------|-----------
    query | string |  required  | Maximum: `255`
    type | string |  optional  | `items` or `resturants`

<!-- END_e19c9e19f1f1208528a69cd2ef4c01dd -->

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
---------|-------|-------|-------|-----------
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
---------|-------|-------|-------|-----------
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
---------|-------|-------|-------|-----------
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

#zZ TODO: -- Pending Endpoints

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

