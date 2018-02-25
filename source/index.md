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
## Display a listing of the resource.

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

<!-- START_7d7e72d015e952a72534beb17042ca82 -->
## Show the form for creating a new resource.

> Example request:

```bash
curl -X GET "http://booconnect.run/api/v1/account/create" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "http://booconnect.run/api/v1/account/create",
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
`GET api/v1/account/create`

`HEAD api/v1/account/create`


<!-- END_7d7e72d015e952a72534beb17042ca82 -->

<!-- START_700b6083aece5829c3fc1304c926b8c6 -->
## Store a newly created resource in storage.

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

<!-- START_2c28f7c2f15ed5fc23ee33650e3df3cb -->
## Display the specified resource.

> Example request:

```bash
curl -X GET "http://booconnect.run/api/v1/account/{account}" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "http://booconnect.run/api/v1/account/{account}",
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
`GET api/v1/account/{account}`

`HEAD api/v1/account/{account}`


<!-- END_2c28f7c2f15ed5fc23ee33650e3df3cb -->

<!-- START_7ee1dbded1602489e3a18cdde20d1e1f -->
## Show the form for editing the specified resource.

> Example request:

```bash
curl -X GET "http://booconnect.run/api/v1/account/{account}/edit" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "http://booconnect.run/api/v1/account/{account}/edit",
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
`GET api/v1/account/{account}/edit`

`HEAD api/v1/account/{account}/edit`


<!-- END_7ee1dbded1602489e3a18cdde20d1e1f -->

<!-- START_ab7447183d9e96e2392237f06ba821fc -->
## Update the specified resource in storage.

> Example request:

```bash
curl -X PUT "http://booconnect.run/api/v1/account/{account}" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "http://booconnect.run/api/v1/account/{account}",
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
`PUT api/v1/account/{account}`

`PATCH api/v1/account/{account}`


<!-- END_ab7447183d9e96e2392237f06ba821fc -->

<!-- START_da44348855fd7a7a313be400d2504f40 -->
## Remove the specified resource from storage.

> Example request:

```bash
curl -X DELETE "http://booconnect.run/api/v1/account/{account}" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "http://booconnect.run/api/v1/account/{account}",
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
`DELETE api/v1/account/{account}`


<!-- END_da44348855fd7a7a313be400d2504f40 -->

#Cart

Shopping cart endpoints
<!-- START_2e395b6f96faf612c0f5b034491ff221 -->
## Display a listing of the resource.

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
{
    "message": "Call to undefined method Illuminate\\Database\\Query\\Builder::content()",
    "exception": "BadMethodCallException",
    "file": "\/Users\/ovac\/codes\/omnile\/booconnect\/vendor\/laravel\/framework\/src\/Illuminate\/Database\/Query\/Builder.php",
    "line": 2512,
    "trace": [
        {
            "file": "\/Users\/ovac\/codes\/omnile\/booconnect\/vendor\/laravel\/framework\/src\/Illuminate\/Database\/Eloquent\/Builder.php",
            "line": 1284,
            "function": "__call",
            "class": "Illuminate\\Database\\Query\\Builder",
            "type": "->"
        },
        {
            "file": "\/Users\/ovac\/codes\/omnile\/booconnect\/vendor\/laravel\/framework\/src\/Illuminate\/Database\/Eloquent\/Model.php",
            "line": 1503,
            "function": "__call",
            "class": "Illuminate\\Database\\Eloquent\\Builder",
            "type": "->"
        },
        {
            "file": "\/Users\/ovac\/codes\/omnile\/booconnect\/vendor\/laravel\/framework\/src\/Illuminate\/Database\/Eloquent\/Model.php",
            "line": 1515,
            "function": "__call",
            "class": "Illuminate\\Database\\Eloquent\\Model",
            "type": "->"
        },
        {
            "file": "\/Users\/ovac\/codes\/omnile\/booconnect\/app\/Http\/Controllers\/CartController.php",
            "line": 22,
            "function": "__callStatic",
            "class": "Illuminate\\Database\\Eloquent\\Model",
            "type": "::"
        },
        {
            "function": "index",
            "class": "App\\Http\\Controllers\\CartController",
            "type": "->"
        },
        {
            "file": "\/Users\/ovac\/codes\/omnile\/booconnect\/vendor\/laravel\/framework\/src\/Illuminate\/Routing\/Controller.php",
            "line": 54,
            "function": "call_user_func_array"
        },
        {
            "file": "\/Users\/ovac\/codes\/omnile\/booconnect\/vendor\/laravel\/framework\/src\/Illuminate\/Routing\/ControllerDispatcher.php",
            "line": 45,
            "function": "callAction",
            "class": "Illuminate\\Routing\\Controller",
            "type": "->"
        },
        {
            "file": "\/Users\/ovac\/codes\/omnile\/booconnect\/vendor\/laravel\/framework\/src\/Illuminate\/Routing\/Route.php",
            "line": 212,
            "function": "dispatch",
            "class": "Illuminate\\Routing\\ControllerDispatcher",
            "type": "->"
        },
        {
            "file": "\/Users\/ovac\/codes\/omnile\/booconnect\/vendor\/laravel\/framework\/src\/Illuminate\/Routing\/Route.php",
            "line": 169,
            "function": "runController",
            "class": "Illuminate\\Routing\\Route",
            "type": "->"
        },
        {
            "file": "\/Users\/ovac\/codes\/omnile\/booconnect\/vendor\/laravel\/framework\/src\/Illuminate\/Routing\/Router.php",
            "line": 659,
            "function": "run",
            "class": "Illuminate\\Routing\\Route",
            "type": "->"
        },
        {
            "file": "\/Users\/ovac\/codes\/omnile\/booconnect\/vendor\/laravel\/framework\/src\/Illuminate\/Routing\/Pipeline.php",
            "line": 30,
            "function": "Illuminate\\Routing\\{closure}",
            "class": "Illuminate\\Routing\\Router",
            "type": "->"
        },
        {
            "file": "\/Users\/ovac\/codes\/omnile\/booconnect\/vendor\/laravel\/framework\/src\/Illuminate\/Routing\/Middleware\/SubstituteBindings.php",
            "line": 41,
            "function": "Illuminate\\Routing\\{closure}",
            "class": "Illuminate\\Routing\\Pipeline",
            "type": "->"
        },
        {
            "file": "\/Users\/ovac\/codes\/omnile\/booconnect\/vendor\/laravel\/framework\/src\/Illuminate\/Pipeline\/Pipeline.php",
            "line": 149,
            "function": "handle",
            "class": "Illuminate\\Routing\\Middleware\\SubstituteBindings",
            "type": "->"
        },
        {
            "file": "\/Users\/ovac\/codes\/omnile\/booconnect\/vendor\/laravel\/framework\/src\/Illuminate\/Routing\/Pipeline.php",
            "line": 53,
            "function": "Illuminate\\Pipeline\\{closure}",
            "class": "Illuminate\\Pipeline\\Pipeline",
            "type": "->"
        },
        {
            "file": "\/Users\/ovac\/codes\/omnile\/booconnect\/vendor\/laravel\/framework\/src\/Illuminate\/Routing\/Middleware\/ThrottleRequests.php",
            "line": 57,
            "function": "Illuminate\\Routing\\{closure}",
            "class": "Illuminate\\Routing\\Pipeline",
            "type": "->"
        },
        {
            "file": "\/Users\/ovac\/codes\/omnile\/booconnect\/vendor\/laravel\/framework\/src\/Illuminate\/Pipeline\/Pipeline.php",
            "line": 149,
            "function": "handle",
            "class": "Illuminate\\Routing\\Middleware\\ThrottleRequests",
            "type": "->"
        },
        {
            "file": "\/Users\/ovac\/codes\/omnile\/booconnect\/vendor\/laravel\/framework\/src\/Illuminate\/Routing\/Pipeline.php",
            "line": 53,
            "function": "Illuminate\\Pipeline\\{closure}",
            "class": "Illuminate\\Pipeline\\Pipeline",
            "type": "->"
        },
        {
            "file": "\/Users\/ovac\/codes\/omnile\/booconnect\/vendor\/laravel\/framework\/src\/Illuminate\/Pipeline\/Pipeline.php",
            "line": 102,
            "function": "Illuminate\\Routing\\{closure}",
            "class": "Illuminate\\Routing\\Pipeline",
            "type": "->"
        },
        {
            "file": "\/Users\/ovac\/codes\/omnile\/booconnect\/vendor\/laravel\/framework\/src\/Illuminate\/Routing\/Router.php",
            "line": 661,
            "function": "then",
            "class": "Illuminate\\Pipeline\\Pipeline",
            "type": "->"
        },
        {
            "file": "\/Users\/ovac\/codes\/omnile\/booconnect\/vendor\/laravel\/framework\/src\/Illuminate\/Routing\/Router.php",
            "line": 636,
            "function": "runRouteWithinStack",
            "class": "Illuminate\\Routing\\Router",
            "type": "->"
        },
        {
            "file": "\/Users\/ovac\/codes\/omnile\/booconnect\/vendor\/laravel\/framework\/src\/Illuminate\/Routing\/Router.php",
            "line": 602,
            "function": "runRoute",
            "class": "Illuminate\\Routing\\Router",
            "type": "->"
        },
        {
            "file": "\/Users\/ovac\/codes\/omnile\/booconnect\/vendor\/laravel\/framework\/src\/Illuminate\/Routing\/Router.php",
            "line": 591,
            "function": "dispatchToRoute",
            "class": "Illuminate\\Routing\\Router",
            "type": "->"
        },
        {
            "file": "\/Users\/ovac\/codes\/omnile\/booconnect\/vendor\/laravel\/framework\/src\/Illuminate\/Foundation\/Http\/Kernel.php",
            "line": 176,
            "function": "dispatch",
            "class": "Illuminate\\Routing\\Router",
            "type": "->"
        },
        {
            "file": "\/Users\/ovac\/codes\/omnile\/booconnect\/vendor\/laravel\/framework\/src\/Illuminate\/Routing\/Pipeline.php",
            "line": 30,
            "function": "Illuminate\\Foundation\\Http\\{closure}",
            "class": "Illuminate\\Foundation\\Http\\Kernel",
            "type": "->"
        },
        {
            "file": "\/Users\/ovac\/codes\/omnile\/booconnect\/vendor\/fideloper\/proxy\/src\/TrustProxies.php",
            "line": 57,
            "function": "Illuminate\\Routing\\{closure}",
            "class": "Illuminate\\Routing\\Pipeline",
            "type": "->"
        },
        {
            "file": "\/Users\/ovac\/codes\/omnile\/booconnect\/vendor\/laravel\/framework\/src\/Illuminate\/Pipeline\/Pipeline.php",
            "line": 149,
            "function": "handle",
            "class": "Fideloper\\Proxy\\TrustProxies",
            "type": "->"
        },
        {
            "file": "\/Users\/ovac\/codes\/omnile\/booconnect\/vendor\/laravel\/framework\/src\/Illuminate\/Routing\/Pipeline.php",
            "line": 53,
            "function": "Illuminate\\Pipeline\\{closure}",
            "class": "Illuminate\\Pipeline\\Pipeline",
            "type": "->"
        },
        {
            "file": "\/Users\/ovac\/codes\/omnile\/booconnect\/vendor\/laravel\/framework\/src\/Illuminate\/Foundation\/Http\/Middleware\/TransformsRequest.php",
            "line": 30,
            "function": "Illuminate\\Routing\\{closure}",
            "class": "Illuminate\\Routing\\Pipeline",
            "type": "->"
        },
        {
            "file": "\/Users\/ovac\/codes\/omnile\/booconnect\/vendor\/laravel\/framework\/src\/Illuminate\/Pipeline\/Pipeline.php",
            "line": 149,
            "function": "handle",
            "class": "Illuminate\\Foundation\\Http\\Middleware\\TransformsRequest",
            "type": "->"
        },
        {
            "file": "\/Users\/ovac\/codes\/omnile\/booconnect\/vendor\/laravel\/framework\/src\/Illuminate\/Routing\/Pipeline.php",
            "line": 53,
            "function": "Illuminate\\Pipeline\\{closure}",
            "class": "Illuminate\\Pipeline\\Pipeline",
            "type": "->"
        },
        {
            "file": "\/Users\/ovac\/codes\/omnile\/booconnect\/vendor\/laravel\/framework\/src\/Illuminate\/Foundation\/Http\/Middleware\/TransformsRequest.php",
            "line": 30,
            "function": "Illuminate\\Routing\\{closure}",
            "class": "Illuminate\\Routing\\Pipeline",
            "type": "->"
        },
        {
            "file": "\/Users\/ovac\/codes\/omnile\/booconnect\/vendor\/laravel\/framework\/src\/Illuminate\/Pipeline\/Pipeline.php",
            "line": 149,
            "function": "handle",
            "class": "Illuminate\\Foundation\\Http\\Middleware\\TransformsRequest",
            "type": "->"
        },
        {
            "file": "\/Users\/ovac\/codes\/omnile\/booconnect\/vendor\/laravel\/framework\/src\/Illuminate\/Routing\/Pipeline.php",
            "line": 53,
            "function": "Illuminate\\Pipeline\\{closure}",
            "class": "Illuminate\\Pipeline\\Pipeline",
            "type": "->"
        },
        {
            "file": "\/Users\/ovac\/codes\/omnile\/booconnect\/vendor\/laravel\/framework\/src\/Illuminate\/Foundation\/Http\/Middleware\/ValidatePostSize.php",
            "line": 27,
            "function": "Illuminate\\Routing\\{closure}",
            "class": "Illuminate\\Routing\\Pipeline",
            "type": "->"
        },
        {
            "file": "\/Users\/ovac\/codes\/omnile\/booconnect\/vendor\/laravel\/framework\/src\/Illuminate\/Pipeline\/Pipeline.php",
            "line": 149,
            "function": "handle",
            "class": "Illuminate\\Foundation\\Http\\Middleware\\ValidatePostSize",
            "type": "->"
        },
        {
            "file": "\/Users\/ovac\/codes\/omnile\/booconnect\/vendor\/laravel\/framework\/src\/Illuminate\/Routing\/Pipeline.php",
            "line": 53,
            "function": "Illuminate\\Pipeline\\{closure}",
            "class": "Illuminate\\Pipeline\\Pipeline",
            "type": "->"
        },
        {
            "file": "\/Users\/ovac\/codes\/omnile\/booconnect\/vendor\/laravel\/framework\/src\/Illuminate\/Foundation\/Http\/Middleware\/CheckForMaintenanceMode.php",
            "line": 46,
            "function": "Illuminate\\Routing\\{closure}",
            "class": "Illuminate\\Routing\\Pipeline",
            "type": "->"
        },
        {
            "file": "\/Users\/ovac\/codes\/omnile\/booconnect\/vendor\/laravel\/framework\/src\/Illuminate\/Pipeline\/Pipeline.php",
            "line": 149,
            "function": "handle",
            "class": "Illuminate\\Foundation\\Http\\Middleware\\CheckForMaintenanceMode",
            "type": "->"
        },
        {
            "file": "\/Users\/ovac\/codes\/omnile\/booconnect\/vendor\/laravel\/framework\/src\/Illuminate\/Routing\/Pipeline.php",
            "line": 53,
            "function": "Illuminate\\Pipeline\\{closure}",
            "class": "Illuminate\\Pipeline\\Pipeline",
            "type": "->"
        },
        {
            "file": "\/Users\/ovac\/codes\/omnile\/booconnect\/vendor\/laravel\/framework\/src\/Illuminate\/Pipeline\/Pipeline.php",
            "line": 102,
            "function": "Illuminate\\Routing\\{closure}",
            "class": "Illuminate\\Routing\\Pipeline",
            "type": "->"
        },
        {
            "file": "\/Users\/ovac\/codes\/omnile\/booconnect\/vendor\/laravel\/framework\/src\/Illuminate\/Foundation\/Http\/Kernel.php",
            "line": 151,
            "function": "then",
            "class": "Illuminate\\Pipeline\\Pipeline",
            "type": "->"
        },
        {
            "file": "\/Users\/ovac\/codes\/omnile\/booconnect\/vendor\/laravel\/framework\/src\/Illuminate\/Foundation\/Http\/Kernel.php",
            "line": 116,
            "function": "sendRequestThroughRouter",
            "class": "Illuminate\\Foundation\\Http\\Kernel",
            "type": "->"
        },
        {
            "file": "\/Users\/ovac\/codes\/omnile\/booconnect\/vendor\/mpociot\/laravel-apidoc-generator\/src\/Mpociot\/ApiDoc\/Generators\/LaravelGenerator.php",
            "line": 139,
            "function": "handle",
            "class": "Illuminate\\Foundation\\Http\\Kernel",
            "type": "->"
        },
        {
            "file": "\/Users\/ovac\/codes\/omnile\/booconnect\/vendor\/mpociot\/laravel-apidoc-generator\/src\/Mpociot\/ApiDoc\/Generators\/AbstractGenerator.php",
            "line": 125,
            "function": "callRoute",
            "class": "Mpociot\\ApiDoc\\Generators\\LaravelGenerator",
            "type": "->"
        },
        {
            "file": "\/Users\/ovac\/codes\/omnile\/booconnect\/vendor\/mpociot\/laravel-apidoc-generator\/src\/Mpociot\/ApiDoc\/Generators\/LaravelGenerator.php",
            "line": 79,
            "function": "getRouteResponse",
            "class": "Mpociot\\ApiDoc\\Generators\\AbstractGenerator",
            "type": "->"
        },
        {
            "file": "\/Users\/ovac\/codes\/omnile\/booconnect\/vendor\/mpociot\/laravel-apidoc-generator\/src\/Mpociot\/ApiDoc\/Commands\/GenerateDocumentation.php",
            "line": 264,
            "function": "processRoute",
            "class": "Mpociot\\ApiDoc\\Generators\\LaravelGenerator",
            "type": "->"
        },
        {
            "file": "\/Users\/ovac\/codes\/omnile\/booconnect\/vendor\/mpociot\/laravel-apidoc-generator\/src\/Mpociot\/ApiDoc\/Commands\/GenerateDocumentation.php",
            "line": 85,
            "function": "processLaravelRoutes",
            "class": "Mpociot\\ApiDoc\\Commands\\GenerateDocumentation",
            "type": "->"
        },
        {
            "function": "handle",
            "class": "Mpociot\\ApiDoc\\Commands\\GenerateDocumentation",
            "type": "->"
        },
        {
            "file": "\/Users\/ovac\/codes\/omnile\/booconnect\/vendor\/laravel\/framework\/src\/Illuminate\/Container\/BoundMethod.php",
            "line": 29,
            "function": "call_user_func_array"
        },
        {
            "file": "\/Users\/ovac\/codes\/omnile\/booconnect\/vendor\/laravel\/framework\/src\/Illuminate\/Container\/BoundMethod.php",
            "line": 87,
            "function": "Illuminate\\Container\\{closure}",
            "class": "Illuminate\\Container\\BoundMethod",
            "type": "::"
        },
        {
            "file": "\/Users\/ovac\/codes\/omnile\/booconnect\/vendor\/laravel\/framework\/src\/Illuminate\/Container\/BoundMethod.php",
            "line": 31,
            "function": "callBoundMethod",
            "class": "Illuminate\\Container\\BoundMethod",
            "type": "::"
        },
        {
            "file": "\/Users\/ovac\/codes\/omnile\/booconnect\/vendor\/laravel\/framework\/src\/Illuminate\/Container\/Container.php",
            "line": 564,
            "function": "call",
            "class": "Illuminate\\Container\\BoundMethod",
            "type": "::"
        },
        {
            "file": "\/Users\/ovac\/codes\/omnile\/booconnect\/vendor\/laravel\/framework\/src\/Illuminate\/Console\/Command.php",
            "line": 183,
            "function": "call",
            "class": "Illuminate\\Container\\Container",
            "type": "->"
        },
        {
            "file": "\/Users\/ovac\/codes\/omnile\/booconnect\/vendor\/symfony\/console\/Command\/Command.php",
            "line": 252,
            "function": "execute",
            "class": "Illuminate\\Console\\Command",
            "type": "->"
        },
        {
            "file": "\/Users\/ovac\/codes\/omnile\/booconnect\/vendor\/laravel\/framework\/src\/Illuminate\/Console\/Command.php",
            "line": 170,
            "function": "run",
            "class": "Symfony\\Component\\Console\\Command\\Command",
            "type": "->"
        },
        {
            "file": "\/Users\/ovac\/codes\/omnile\/booconnect\/vendor\/symfony\/console\/Application.php",
            "line": 865,
            "function": "run",
            "class": "Illuminate\\Console\\Command",
            "type": "->"
        },
        {
            "file": "\/Users\/ovac\/codes\/omnile\/booconnect\/vendor\/symfony\/console\/Application.php",
            "line": 241,
            "function": "doRunCommand",
            "class": "Symfony\\Component\\Console\\Application",
            "type": "->"
        },
        {
            "file": "\/Users\/ovac\/codes\/omnile\/booconnect\/vendor\/symfony\/console\/Application.php",
            "line": 143,
            "function": "doRun",
            "class": "Symfony\\Component\\Console\\Application",
            "type": "->"
        },
        {
            "file": "\/Users\/ovac\/codes\/omnile\/booconnect\/vendor\/laravel\/framework\/src\/Illuminate\/Console\/Application.php",
            "line": 88,
            "function": "run",
            "class": "Symfony\\Component\\Console\\Application",
            "type": "->"
        },
        {
            "file": "\/Users\/ovac\/codes\/omnile\/booconnect\/vendor\/laravel\/framework\/src\/Illuminate\/Foundation\/Console\/Kernel.php",
            "line": 121,
            "function": "run",
            "class": "Illuminate\\Console\\Application",
            "type": "->"
        },
        {
            "file": "\/Users\/ovac\/codes\/omnile\/booconnect\/artisan",
            "line": 37,
            "function": "handle",
            "class": "Illuminate\\Foundation\\Console\\Kernel",
            "type": "->"
        }
    ]
}
```

### HTTP Request
`GET api/v1/cart`

`HEAD api/v1/cart`


<!-- END_2e395b6f96faf612c0f5b034491ff221 -->

<!-- START_eae9a79b3a19eaa85e8a2ca288575b0b -->
## Show the form for creating a new resource.

> Example request:

```bash
curl -X GET "http://booconnect.run/api/v1/cart/create" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "http://booconnect.run/api/v1/cart/create",
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
null
```

### HTTP Request
`GET api/v1/cart/create`

`HEAD api/v1/cart/create`


<!-- END_eae9a79b3a19eaa85e8a2ca288575b0b -->

<!-- START_b14a883b0d266dd902554e7afed0a2df -->
## Store a newly created resource in storage.

> Example request:

```bash
curl -X POST "http://booconnect.run/api/v1/cart" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "http://booconnect.run/api/v1/cart",
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
`POST api/v1/cart`


<!-- END_b14a883b0d266dd902554e7afed0a2df -->

<!-- START_4812443347d7d406383a6fff4bfc24e4 -->
## Display the specified resource.

> Example request:

```bash
curl -X GET "http://booconnect.run/api/v1/cart/{cart}" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "http://booconnect.run/api/v1/cart/{cart}",
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
    "message": "SQLSTATE[42S02]: Base table or view not found: 1146 Table 'booconnect.carts' doesn't exist (SQL: select * from `carts` where `id` = 1 limit 1)",
    "exception": "Illuminate\\Database\\QueryException",
    "file": "\/Users\/ovac\/codes\/omnile\/booconnect\/vendor\/laravel\/framework\/src\/Illuminate\/Database\/Connection.php",
    "line": 664,
    "trace": [
        {
            "file": "\/Users\/ovac\/codes\/omnile\/booconnect\/vendor\/laravel\/framework\/src\/Illuminate\/Database\/Connection.php",
            "line": 624,
            "function": "runQueryCallback",
            "class": "Illuminate\\Database\\Connection",
            "type": "->"
        },
        {
            "file": "\/Users\/ovac\/codes\/omnile\/booconnect\/vendor\/laravel\/framework\/src\/Illuminate\/Database\/Connection.php",
            "line": 333,
            "function": "run",
            "class": "Illuminate\\Database\\Connection",
            "type": "->"
        },
        {
            "file": "\/Users\/ovac\/codes\/omnile\/booconnect\/vendor\/laravel\/framework\/src\/Illuminate\/Database\/Query\/Builder.php",
            "line": 1748,
            "function": "select",
            "class": "Illuminate\\Database\\Connection",
            "type": "->"
        },
        {
            "file": "\/Users\/ovac\/codes\/omnile\/booconnect\/vendor\/laravel\/framework\/src\/Illuminate\/Database\/Query\/Builder.php",
            "line": 1733,
            "function": "runSelect",
            "class": "Illuminate\\Database\\Query\\Builder",
            "type": "->"
        },
        {
            "file": "\/Users\/ovac\/codes\/omnile\/booconnect\/vendor\/laravel\/framework\/src\/Illuminate\/Database\/Eloquent\/Builder.php",
            "line": 479,
            "function": "get",
            "class": "Illuminate\\Database\\Query\\Builder",
            "type": "->"
        },
        {
            "file": "\/Users\/ovac\/codes\/omnile\/booconnect\/vendor\/laravel\/framework\/src\/Illuminate\/Database\/Eloquent\/Builder.php",
            "line": 463,
            "function": "getModels",
            "class": "Illuminate\\Database\\Eloquent\\Builder",
            "type": "->"
        },
        {
            "file": "\/Users\/ovac\/codes\/omnile\/booconnect\/vendor\/laravel\/framework\/src\/Illuminate\/Database\/Concerns\/BuildsQueries.php",
            "line": 77,
            "function": "get",
            "class": "Illuminate\\Database\\Eloquent\\Builder",
            "type": "->"
        },
        {
            "file": "\/Users\/ovac\/codes\/omnile\/booconnect\/vendor\/laravel\/framework\/src\/Illuminate\/Database\/Eloquent\/Model.php",
            "line": 1364,
            "function": "first",
            "class": "Illuminate\\Database\\Eloquent\\Builder",
            "type": "->"
        },
        {
            "file": "\/Users\/ovac\/codes\/omnile\/booconnect\/vendor\/laravel\/framework\/src\/Illuminate\/Routing\/ImplicitRouteBinding.php",
            "line": 35,
            "function": "resolveRouteBinding",
            "class": "Illuminate\\Database\\Eloquent\\Model",
            "type": "->"
        },
        {
            "file": "\/Users\/ovac\/codes\/omnile\/booconnect\/vendor\/laravel\/framework\/src\/Illuminate\/Routing\/Router.php",
            "line": 762,
            "function": "resolveForRoute",
            "class": "Illuminate\\Routing\\ImplicitRouteBinding",
            "type": "::"
        },
        {
            "file": "\/Users\/ovac\/codes\/omnile\/booconnect\/vendor\/laravel\/framework\/src\/Illuminate\/Routing\/Middleware\/SubstituteBindings.php",
            "line": 39,
            "function": "substituteImplicitBindings",
            "class": "Illuminate\\Routing\\Router",
            "type": "->"
        },
        {
            "file": "\/Users\/ovac\/codes\/omnile\/booconnect\/vendor\/laravel\/framework\/src\/Illuminate\/Pipeline\/Pipeline.php",
            "line": 149,
            "function": "handle",
            "class": "Illuminate\\Routing\\Middleware\\SubstituteBindings",
            "type": "->"
        },
        {
            "file": "\/Users\/ovac\/codes\/omnile\/booconnect\/vendor\/laravel\/framework\/src\/Illuminate\/Routing\/Pipeline.php",
            "line": 53,
            "function": "Illuminate\\Pipeline\\{closure}",
            "class": "Illuminate\\Pipeline\\Pipeline",
            "type": "->"
        },
        {
            "file": "\/Users\/ovac\/codes\/omnile\/booconnect\/vendor\/laravel\/framework\/src\/Illuminate\/Routing\/Middleware\/ThrottleRequests.php",
            "line": 57,
            "function": "Illuminate\\Routing\\{closure}",
            "class": "Illuminate\\Routing\\Pipeline",
            "type": "->"
        },
        {
            "file": "\/Users\/ovac\/codes\/omnile\/booconnect\/vendor\/laravel\/framework\/src\/Illuminate\/Pipeline\/Pipeline.php",
            "line": 149,
            "function": "handle",
            "class": "Illuminate\\Routing\\Middleware\\ThrottleRequests",
            "type": "->"
        },
        {
            "file": "\/Users\/ovac\/codes\/omnile\/booconnect\/vendor\/laravel\/framework\/src\/Illuminate\/Routing\/Pipeline.php",
            "line": 53,
            "function": "Illuminate\\Pipeline\\{closure}",
            "class": "Illuminate\\Pipeline\\Pipeline",
            "type": "->"
        },
        {
            "file": "\/Users\/ovac\/codes\/omnile\/booconnect\/vendor\/laravel\/framework\/src\/Illuminate\/Pipeline\/Pipeline.php",
            "line": 102,
            "function": "Illuminate\\Routing\\{closure}",
            "class": "Illuminate\\Routing\\Pipeline",
            "type": "->"
        },
        {
            "file": "\/Users\/ovac\/codes\/omnile\/booconnect\/vendor\/laravel\/framework\/src\/Illuminate\/Routing\/Router.php",
            "line": 661,
            "function": "then",
            "class": "Illuminate\\Pipeline\\Pipeline",
            "type": "->"
        },
        {
            "file": "\/Users\/ovac\/codes\/omnile\/booconnect\/vendor\/laravel\/framework\/src\/Illuminate\/Routing\/Router.php",
            "line": 636,
            "function": "runRouteWithinStack",
            "class": "Illuminate\\Routing\\Router",
            "type": "->"
        },
        {
            "file": "\/Users\/ovac\/codes\/omnile\/booconnect\/vendor\/laravel\/framework\/src\/Illuminate\/Routing\/Router.php",
            "line": 602,
            "function": "runRoute",
            "class": "Illuminate\\Routing\\Router",
            "type": "->"
        },
        {
            "file": "\/Users\/ovac\/codes\/omnile\/booconnect\/vendor\/laravel\/framework\/src\/Illuminate\/Routing\/Router.php",
            "line": 591,
            "function": "dispatchToRoute",
            "class": "Illuminate\\Routing\\Router",
            "type": "->"
        },
        {
            "file": "\/Users\/ovac\/codes\/omnile\/booconnect\/vendor\/laravel\/framework\/src\/Illuminate\/Foundation\/Http\/Kernel.php",
            "line": 176,
            "function": "dispatch",
            "class": "Illuminate\\Routing\\Router",
            "type": "->"
        },
        {
            "file": "\/Users\/ovac\/codes\/omnile\/booconnect\/vendor\/laravel\/framework\/src\/Illuminate\/Routing\/Pipeline.php",
            "line": 30,
            "function": "Illuminate\\Foundation\\Http\\{closure}",
            "class": "Illuminate\\Foundation\\Http\\Kernel",
            "type": "->"
        },
        {
            "file": "\/Users\/ovac\/codes\/omnile\/booconnect\/vendor\/fideloper\/proxy\/src\/TrustProxies.php",
            "line": 57,
            "function": "Illuminate\\Routing\\{closure}",
            "class": "Illuminate\\Routing\\Pipeline",
            "type": "->"
        },
        {
            "file": "\/Users\/ovac\/codes\/omnile\/booconnect\/vendor\/laravel\/framework\/src\/Illuminate\/Pipeline\/Pipeline.php",
            "line": 149,
            "function": "handle",
            "class": "Fideloper\\Proxy\\TrustProxies",
            "type": "->"
        },
        {
            "file": "\/Users\/ovac\/codes\/omnile\/booconnect\/vendor\/laravel\/framework\/src\/Illuminate\/Routing\/Pipeline.php",
            "line": 53,
            "function": "Illuminate\\Pipeline\\{closure}",
            "class": "Illuminate\\Pipeline\\Pipeline",
            "type": "->"
        },
        {
            "file": "\/Users\/ovac\/codes\/omnile\/booconnect\/vendor\/laravel\/framework\/src\/Illuminate\/Foundation\/Http\/Middleware\/TransformsRequest.php",
            "line": 30,
            "function": "Illuminate\\Routing\\{closure}",
            "class": "Illuminate\\Routing\\Pipeline",
            "type": "->"
        },
        {
            "file": "\/Users\/ovac\/codes\/omnile\/booconnect\/vendor\/laravel\/framework\/src\/Illuminate\/Pipeline\/Pipeline.php",
            "line": 149,
            "function": "handle",
            "class": "Illuminate\\Foundation\\Http\\Middleware\\TransformsRequest",
            "type": "->"
        },
        {
            "file": "\/Users\/ovac\/codes\/omnile\/booconnect\/vendor\/laravel\/framework\/src\/Illuminate\/Routing\/Pipeline.php",
            "line": 53,
            "function": "Illuminate\\Pipeline\\{closure}",
            "class": "Illuminate\\Pipeline\\Pipeline",
            "type": "->"
        },
        {
            "file": "\/Users\/ovac\/codes\/omnile\/booconnect\/vendor\/laravel\/framework\/src\/Illuminate\/Foundation\/Http\/Middleware\/TransformsRequest.php",
            "line": 30,
            "function": "Illuminate\\Routing\\{closure}",
            "class": "Illuminate\\Routing\\Pipeline",
            "type": "->"
        },
        {
            "file": "\/Users\/ovac\/codes\/omnile\/booconnect\/vendor\/laravel\/framework\/src\/Illuminate\/Pipeline\/Pipeline.php",
            "line": 149,
            "function": "handle",
            "class": "Illuminate\\Foundation\\Http\\Middleware\\TransformsRequest",
            "type": "->"
        },
        {
            "file": "\/Users\/ovac\/codes\/omnile\/booconnect\/vendor\/laravel\/framework\/src\/Illuminate\/Routing\/Pipeline.php",
            "line": 53,
            "function": "Illuminate\\Pipeline\\{closure}",
            "class": "Illuminate\\Pipeline\\Pipeline",
            "type": "->"
        },
        {
            "file": "\/Users\/ovac\/codes\/omnile\/booconnect\/vendor\/laravel\/framework\/src\/Illuminate\/Foundation\/Http\/Middleware\/ValidatePostSize.php",
            "line": 27,
            "function": "Illuminate\\Routing\\{closure}",
            "class": "Illuminate\\Routing\\Pipeline",
            "type": "->"
        },
        {
            "file": "\/Users\/ovac\/codes\/omnile\/booconnect\/vendor\/laravel\/framework\/src\/Illuminate\/Pipeline\/Pipeline.php",
            "line": 149,
            "function": "handle",
            "class": "Illuminate\\Foundation\\Http\\Middleware\\ValidatePostSize",
            "type": "->"
        },
        {
            "file": "\/Users\/ovac\/codes\/omnile\/booconnect\/vendor\/laravel\/framework\/src\/Illuminate\/Routing\/Pipeline.php",
            "line": 53,
            "function": "Illuminate\\Pipeline\\{closure}",
            "class": "Illuminate\\Pipeline\\Pipeline",
            "type": "->"
        },
        {
            "file": "\/Users\/ovac\/codes\/omnile\/booconnect\/vendor\/laravel\/framework\/src\/Illuminate\/Foundation\/Http\/Middleware\/CheckForMaintenanceMode.php",
            "line": 46,
            "function": "Illuminate\\Routing\\{closure}",
            "class": "Illuminate\\Routing\\Pipeline",
            "type": "->"
        },
        {
            "file": "\/Users\/ovac\/codes\/omnile\/booconnect\/vendor\/laravel\/framework\/src\/Illuminate\/Pipeline\/Pipeline.php",
            "line": 149,
            "function": "handle",
            "class": "Illuminate\\Foundation\\Http\\Middleware\\CheckForMaintenanceMode",
            "type": "->"
        },
        {
            "file": "\/Users\/ovac\/codes\/omnile\/booconnect\/vendor\/laravel\/framework\/src\/Illuminate\/Routing\/Pipeline.php",
            "line": 53,
            "function": "Illuminate\\Pipeline\\{closure}",
            "class": "Illuminate\\Pipeline\\Pipeline",
            "type": "->"
        },
        {
            "file": "\/Users\/ovac\/codes\/omnile\/booconnect\/vendor\/laravel\/framework\/src\/Illuminate\/Pipeline\/Pipeline.php",
            "line": 102,
            "function": "Illuminate\\Routing\\{closure}",
            "class": "Illuminate\\Routing\\Pipeline",
            "type": "->"
        },
        {
            "file": "\/Users\/ovac\/codes\/omnile\/booconnect\/vendor\/laravel\/framework\/src\/Illuminate\/Foundation\/Http\/Kernel.php",
            "line": 151,
            "function": "then",
            "class": "Illuminate\\Pipeline\\Pipeline",
            "type": "->"
        },
        {
            "file": "\/Users\/ovac\/codes\/omnile\/booconnect\/vendor\/laravel\/framework\/src\/Illuminate\/Foundation\/Http\/Kernel.php",
            "line": 116,
            "function": "sendRequestThroughRouter",
            "class": "Illuminate\\Foundation\\Http\\Kernel",
            "type": "->"
        },
        {
            "file": "\/Users\/ovac\/codes\/omnile\/booconnect\/vendor\/mpociot\/laravel-apidoc-generator\/src\/Mpociot\/ApiDoc\/Generators\/LaravelGenerator.php",
            "line": 139,
            "function": "handle",
            "class": "Illuminate\\Foundation\\Http\\Kernel",
            "type": "->"
        },
        {
            "file": "\/Users\/ovac\/codes\/omnile\/booconnect\/vendor\/mpociot\/laravel-apidoc-generator\/src\/Mpociot\/ApiDoc\/Generators\/AbstractGenerator.php",
            "line": 125,
            "function": "callRoute",
            "class": "Mpociot\\ApiDoc\\Generators\\LaravelGenerator",
            "type": "->"
        },
        {
            "file": "\/Users\/ovac\/codes\/omnile\/booconnect\/vendor\/mpociot\/laravel-apidoc-generator\/src\/Mpociot\/ApiDoc\/Generators\/LaravelGenerator.php",
            "line": 79,
            "function": "getRouteResponse",
            "class": "Mpociot\\ApiDoc\\Generators\\AbstractGenerator",
            "type": "->"
        },
        {
            "file": "\/Users\/ovac\/codes\/omnile\/booconnect\/vendor\/mpociot\/laravel-apidoc-generator\/src\/Mpociot\/ApiDoc\/Commands\/GenerateDocumentation.php",
            "line": 264,
            "function": "processRoute",
            "class": "Mpociot\\ApiDoc\\Generators\\LaravelGenerator",
            "type": "->"
        },
        {
            "file": "\/Users\/ovac\/codes\/omnile\/booconnect\/vendor\/mpociot\/laravel-apidoc-generator\/src\/Mpociot\/ApiDoc\/Commands\/GenerateDocumentation.php",
            "line": 85,
            "function": "processLaravelRoutes",
            "class": "Mpociot\\ApiDoc\\Commands\\GenerateDocumentation",
            "type": "->"
        },
        {
            "function": "handle",
            "class": "Mpociot\\ApiDoc\\Commands\\GenerateDocumentation",
            "type": "->"
        },
        {
            "file": "\/Users\/ovac\/codes\/omnile\/booconnect\/vendor\/laravel\/framework\/src\/Illuminate\/Container\/BoundMethod.php",
            "line": 29,
            "function": "call_user_func_array"
        },
        {
            "file": "\/Users\/ovac\/codes\/omnile\/booconnect\/vendor\/laravel\/framework\/src\/Illuminate\/Container\/BoundMethod.php",
            "line": 87,
            "function": "Illuminate\\Container\\{closure}",
            "class": "Illuminate\\Container\\BoundMethod",
            "type": "::"
        },
        {
            "file": "\/Users\/ovac\/codes\/omnile\/booconnect\/vendor\/laravel\/framework\/src\/Illuminate\/Container\/BoundMethod.php",
            "line": 31,
            "function": "callBoundMethod",
            "class": "Illuminate\\Container\\BoundMethod",
            "type": "::"
        },
        {
            "file": "\/Users\/ovac\/codes\/omnile\/booconnect\/vendor\/laravel\/framework\/src\/Illuminate\/Container\/Container.php",
            "line": 564,
            "function": "call",
            "class": "Illuminate\\Container\\BoundMethod",
            "type": "::"
        },
        {
            "file": "\/Users\/ovac\/codes\/omnile\/booconnect\/vendor\/laravel\/framework\/src\/Illuminate\/Console\/Command.php",
            "line": 183,
            "function": "call",
            "class": "Illuminate\\Container\\Container",
            "type": "->"
        },
        {
            "file": "\/Users\/ovac\/codes\/omnile\/booconnect\/vendor\/symfony\/console\/Command\/Command.php",
            "line": 252,
            "function": "execute",
            "class": "Illuminate\\Console\\Command",
            "type": "->"
        },
        {
            "file": "\/Users\/ovac\/codes\/omnile\/booconnect\/vendor\/laravel\/framework\/src\/Illuminate\/Console\/Command.php",
            "line": 170,
            "function": "run",
            "class": "Symfony\\Component\\Console\\Command\\Command",
            "type": "->"
        },
        {
            "file": "\/Users\/ovac\/codes\/omnile\/booconnect\/vendor\/symfony\/console\/Application.php",
            "line": 865,
            "function": "run",
            "class": "Illuminate\\Console\\Command",
            "type": "->"
        },
        {
            "file": "\/Users\/ovac\/codes\/omnile\/booconnect\/vendor\/symfony\/console\/Application.php",
            "line": 241,
            "function": "doRunCommand",
            "class": "Symfony\\Component\\Console\\Application",
            "type": "->"
        },
        {
            "file": "\/Users\/ovac\/codes\/omnile\/booconnect\/vendor\/symfony\/console\/Application.php",
            "line": 143,
            "function": "doRun",
            "class": "Symfony\\Component\\Console\\Application",
            "type": "->"
        },
        {
            "file": "\/Users\/ovac\/codes\/omnile\/booconnect\/vendor\/laravel\/framework\/src\/Illuminate\/Console\/Application.php",
            "line": 88,
            "function": "run",
            "class": "Symfony\\Component\\Console\\Application",
            "type": "->"
        },
        {
            "file": "\/Users\/ovac\/codes\/omnile\/booconnect\/vendor\/laravel\/framework\/src\/Illuminate\/Foundation\/Console\/Kernel.php",
            "line": 121,
            "function": "run",
            "class": "Illuminate\\Console\\Application",
            "type": "->"
        },
        {
            "file": "\/Users\/ovac\/codes\/omnile\/booconnect\/artisan",
            "line": 37,
            "function": "handle",
            "class": "Illuminate\\Foundation\\Console\\Kernel",
            "type": "->"
        }
    ]
}
```

### HTTP Request
`GET api/v1/cart/{cart}`

`HEAD api/v1/cart/{cart}`


<!-- END_4812443347d7d406383a6fff4bfc24e4 -->

<!-- START_047c64f2b19f48ea37e72728e5bd305a -->
## Show the form for editing the specified resource.

> Example request:

```bash
curl -X GET "http://booconnect.run/api/v1/cart/{cart}/edit" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "http://booconnect.run/api/v1/cart/{cart}/edit",
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
    "message": "SQLSTATE[42S02]: Base table or view not found: 1146 Table 'booconnect.carts' doesn't exist (SQL: select * from `carts` where `id` = 1 limit 1)",
    "exception": "Illuminate\\Database\\QueryException",
    "file": "\/Users\/ovac\/codes\/omnile\/booconnect\/vendor\/laravel\/framework\/src\/Illuminate\/Database\/Connection.php",
    "line": 664,
    "trace": [
        {
            "file": "\/Users\/ovac\/codes\/omnile\/booconnect\/vendor\/laravel\/framework\/src\/Illuminate\/Database\/Connection.php",
            "line": 624,
            "function": "runQueryCallback",
            "class": "Illuminate\\Database\\Connection",
            "type": "->"
        },
        {
            "file": "\/Users\/ovac\/codes\/omnile\/booconnect\/vendor\/laravel\/framework\/src\/Illuminate\/Database\/Connection.php",
            "line": 333,
            "function": "run",
            "class": "Illuminate\\Database\\Connection",
            "type": "->"
        },
        {
            "file": "\/Users\/ovac\/codes\/omnile\/booconnect\/vendor\/laravel\/framework\/src\/Illuminate\/Database\/Query\/Builder.php",
            "line": 1748,
            "function": "select",
            "class": "Illuminate\\Database\\Connection",
            "type": "->"
        },
        {
            "file": "\/Users\/ovac\/codes\/omnile\/booconnect\/vendor\/laravel\/framework\/src\/Illuminate\/Database\/Query\/Builder.php",
            "line": 1733,
            "function": "runSelect",
            "class": "Illuminate\\Database\\Query\\Builder",
            "type": "->"
        },
        {
            "file": "\/Users\/ovac\/codes\/omnile\/booconnect\/vendor\/laravel\/framework\/src\/Illuminate\/Database\/Eloquent\/Builder.php",
            "line": 479,
            "function": "get",
            "class": "Illuminate\\Database\\Query\\Builder",
            "type": "->"
        },
        {
            "file": "\/Users\/ovac\/codes\/omnile\/booconnect\/vendor\/laravel\/framework\/src\/Illuminate\/Database\/Eloquent\/Builder.php",
            "line": 463,
            "function": "getModels",
            "class": "Illuminate\\Database\\Eloquent\\Builder",
            "type": "->"
        },
        {
            "file": "\/Users\/ovac\/codes\/omnile\/booconnect\/vendor\/laravel\/framework\/src\/Illuminate\/Database\/Concerns\/BuildsQueries.php",
            "line": 77,
            "function": "get",
            "class": "Illuminate\\Database\\Eloquent\\Builder",
            "type": "->"
        },
        {
            "file": "\/Users\/ovac\/codes\/omnile\/booconnect\/vendor\/laravel\/framework\/src\/Illuminate\/Database\/Eloquent\/Model.php",
            "line": 1364,
            "function": "first",
            "class": "Illuminate\\Database\\Eloquent\\Builder",
            "type": "->"
        },
        {
            "file": "\/Users\/ovac\/codes\/omnile\/booconnect\/vendor\/laravel\/framework\/src\/Illuminate\/Routing\/ImplicitRouteBinding.php",
            "line": 35,
            "function": "resolveRouteBinding",
            "class": "Illuminate\\Database\\Eloquent\\Model",
            "type": "->"
        },
        {
            "file": "\/Users\/ovac\/codes\/omnile\/booconnect\/vendor\/laravel\/framework\/src\/Illuminate\/Routing\/Router.php",
            "line": 762,
            "function": "resolveForRoute",
            "class": "Illuminate\\Routing\\ImplicitRouteBinding",
            "type": "::"
        },
        {
            "file": "\/Users\/ovac\/codes\/omnile\/booconnect\/vendor\/laravel\/framework\/src\/Illuminate\/Routing\/Middleware\/SubstituteBindings.php",
            "line": 39,
            "function": "substituteImplicitBindings",
            "class": "Illuminate\\Routing\\Router",
            "type": "->"
        },
        {
            "file": "\/Users\/ovac\/codes\/omnile\/booconnect\/vendor\/laravel\/framework\/src\/Illuminate\/Pipeline\/Pipeline.php",
            "line": 149,
            "function": "handle",
            "class": "Illuminate\\Routing\\Middleware\\SubstituteBindings",
            "type": "->"
        },
        {
            "file": "\/Users\/ovac\/codes\/omnile\/booconnect\/vendor\/laravel\/framework\/src\/Illuminate\/Routing\/Pipeline.php",
            "line": 53,
            "function": "Illuminate\\Pipeline\\{closure}",
            "class": "Illuminate\\Pipeline\\Pipeline",
            "type": "->"
        },
        {
            "file": "\/Users\/ovac\/codes\/omnile\/booconnect\/vendor\/laravel\/framework\/src\/Illuminate\/Routing\/Middleware\/ThrottleRequests.php",
            "line": 57,
            "function": "Illuminate\\Routing\\{closure}",
            "class": "Illuminate\\Routing\\Pipeline",
            "type": "->"
        },
        {
            "file": "\/Users\/ovac\/codes\/omnile\/booconnect\/vendor\/laravel\/framework\/src\/Illuminate\/Pipeline\/Pipeline.php",
            "line": 149,
            "function": "handle",
            "class": "Illuminate\\Routing\\Middleware\\ThrottleRequests",
            "type": "->"
        },
        {
            "file": "\/Users\/ovac\/codes\/omnile\/booconnect\/vendor\/laravel\/framework\/src\/Illuminate\/Routing\/Pipeline.php",
            "line": 53,
            "function": "Illuminate\\Pipeline\\{closure}",
            "class": "Illuminate\\Pipeline\\Pipeline",
            "type": "->"
        },
        {
            "file": "\/Users\/ovac\/codes\/omnile\/booconnect\/vendor\/laravel\/framework\/src\/Illuminate\/Pipeline\/Pipeline.php",
            "line": 102,
            "function": "Illuminate\\Routing\\{closure}",
            "class": "Illuminate\\Routing\\Pipeline",
            "type": "->"
        },
        {
            "file": "\/Users\/ovac\/codes\/omnile\/booconnect\/vendor\/laravel\/framework\/src\/Illuminate\/Routing\/Router.php",
            "line": 661,
            "function": "then",
            "class": "Illuminate\\Pipeline\\Pipeline",
            "type": "->"
        },
        {
            "file": "\/Users\/ovac\/codes\/omnile\/booconnect\/vendor\/laravel\/framework\/src\/Illuminate\/Routing\/Router.php",
            "line": 636,
            "function": "runRouteWithinStack",
            "class": "Illuminate\\Routing\\Router",
            "type": "->"
        },
        {
            "file": "\/Users\/ovac\/codes\/omnile\/booconnect\/vendor\/laravel\/framework\/src\/Illuminate\/Routing\/Router.php",
            "line": 602,
            "function": "runRoute",
            "class": "Illuminate\\Routing\\Router",
            "type": "->"
        },
        {
            "file": "\/Users\/ovac\/codes\/omnile\/booconnect\/vendor\/laravel\/framework\/src\/Illuminate\/Routing\/Router.php",
            "line": 591,
            "function": "dispatchToRoute",
            "class": "Illuminate\\Routing\\Router",
            "type": "->"
        },
        {
            "file": "\/Users\/ovac\/codes\/omnile\/booconnect\/vendor\/laravel\/framework\/src\/Illuminate\/Foundation\/Http\/Kernel.php",
            "line": 176,
            "function": "dispatch",
            "class": "Illuminate\\Routing\\Router",
            "type": "->"
        },
        {
            "file": "\/Users\/ovac\/codes\/omnile\/booconnect\/vendor\/laravel\/framework\/src\/Illuminate\/Routing\/Pipeline.php",
            "line": 30,
            "function": "Illuminate\\Foundation\\Http\\{closure}",
            "class": "Illuminate\\Foundation\\Http\\Kernel",
            "type": "->"
        },
        {
            "file": "\/Users\/ovac\/codes\/omnile\/booconnect\/vendor\/fideloper\/proxy\/src\/TrustProxies.php",
            "line": 57,
            "function": "Illuminate\\Routing\\{closure}",
            "class": "Illuminate\\Routing\\Pipeline",
            "type": "->"
        },
        {
            "file": "\/Users\/ovac\/codes\/omnile\/booconnect\/vendor\/laravel\/framework\/src\/Illuminate\/Pipeline\/Pipeline.php",
            "line": 149,
            "function": "handle",
            "class": "Fideloper\\Proxy\\TrustProxies",
            "type": "->"
        },
        {
            "file": "\/Users\/ovac\/codes\/omnile\/booconnect\/vendor\/laravel\/framework\/src\/Illuminate\/Routing\/Pipeline.php",
            "line": 53,
            "function": "Illuminate\\Pipeline\\{closure}",
            "class": "Illuminate\\Pipeline\\Pipeline",
            "type": "->"
        },
        {
            "file": "\/Users\/ovac\/codes\/omnile\/booconnect\/vendor\/laravel\/framework\/src\/Illuminate\/Foundation\/Http\/Middleware\/TransformsRequest.php",
            "line": 30,
            "function": "Illuminate\\Routing\\{closure}",
            "class": "Illuminate\\Routing\\Pipeline",
            "type": "->"
        },
        {
            "file": "\/Users\/ovac\/codes\/omnile\/booconnect\/vendor\/laravel\/framework\/src\/Illuminate\/Pipeline\/Pipeline.php",
            "line": 149,
            "function": "handle",
            "class": "Illuminate\\Foundation\\Http\\Middleware\\TransformsRequest",
            "type": "->"
        },
        {
            "file": "\/Users\/ovac\/codes\/omnile\/booconnect\/vendor\/laravel\/framework\/src\/Illuminate\/Routing\/Pipeline.php",
            "line": 53,
            "function": "Illuminate\\Pipeline\\{closure}",
            "class": "Illuminate\\Pipeline\\Pipeline",
            "type": "->"
        },
        {
            "file": "\/Users\/ovac\/codes\/omnile\/booconnect\/vendor\/laravel\/framework\/src\/Illuminate\/Foundation\/Http\/Middleware\/TransformsRequest.php",
            "line": 30,
            "function": "Illuminate\\Routing\\{closure}",
            "class": "Illuminate\\Routing\\Pipeline",
            "type": "->"
        },
        {
            "file": "\/Users\/ovac\/codes\/omnile\/booconnect\/vendor\/laravel\/framework\/src\/Illuminate\/Pipeline\/Pipeline.php",
            "line": 149,
            "function": "handle",
            "class": "Illuminate\\Foundation\\Http\\Middleware\\TransformsRequest",
            "type": "->"
        },
        {
            "file": "\/Users\/ovac\/codes\/omnile\/booconnect\/vendor\/laravel\/framework\/src\/Illuminate\/Routing\/Pipeline.php",
            "line": 53,
            "function": "Illuminate\\Pipeline\\{closure}",
            "class": "Illuminate\\Pipeline\\Pipeline",
            "type": "->"
        },
        {
            "file": "\/Users\/ovac\/codes\/omnile\/booconnect\/vendor\/laravel\/framework\/src\/Illuminate\/Foundation\/Http\/Middleware\/ValidatePostSize.php",
            "line": 27,
            "function": "Illuminate\\Routing\\{closure}",
            "class": "Illuminate\\Routing\\Pipeline",
            "type": "->"
        },
        {
            "file": "\/Users\/ovac\/codes\/omnile\/booconnect\/vendor\/laravel\/framework\/src\/Illuminate\/Pipeline\/Pipeline.php",
            "line": 149,
            "function": "handle",
            "class": "Illuminate\\Foundation\\Http\\Middleware\\ValidatePostSize",
            "type": "->"
        },
        {
            "file": "\/Users\/ovac\/codes\/omnile\/booconnect\/vendor\/laravel\/framework\/src\/Illuminate\/Routing\/Pipeline.php",
            "line": 53,
            "function": "Illuminate\\Pipeline\\{closure}",
            "class": "Illuminate\\Pipeline\\Pipeline",
            "type": "->"
        },
        {
            "file": "\/Users\/ovac\/codes\/omnile\/booconnect\/vendor\/laravel\/framework\/src\/Illuminate\/Foundation\/Http\/Middleware\/CheckForMaintenanceMode.php",
            "line": 46,
            "function": "Illuminate\\Routing\\{closure}",
            "class": "Illuminate\\Routing\\Pipeline",
            "type": "->"
        },
        {
            "file": "\/Users\/ovac\/codes\/omnile\/booconnect\/vendor\/laravel\/framework\/src\/Illuminate\/Pipeline\/Pipeline.php",
            "line": 149,
            "function": "handle",
            "class": "Illuminate\\Foundation\\Http\\Middleware\\CheckForMaintenanceMode",
            "type": "->"
        },
        {
            "file": "\/Users\/ovac\/codes\/omnile\/booconnect\/vendor\/laravel\/framework\/src\/Illuminate\/Routing\/Pipeline.php",
            "line": 53,
            "function": "Illuminate\\Pipeline\\{closure}",
            "class": "Illuminate\\Pipeline\\Pipeline",
            "type": "->"
        },
        {
            "file": "\/Users\/ovac\/codes\/omnile\/booconnect\/vendor\/laravel\/framework\/src\/Illuminate\/Pipeline\/Pipeline.php",
            "line": 102,
            "function": "Illuminate\\Routing\\{closure}",
            "class": "Illuminate\\Routing\\Pipeline",
            "type": "->"
        },
        {
            "file": "\/Users\/ovac\/codes\/omnile\/booconnect\/vendor\/laravel\/framework\/src\/Illuminate\/Foundation\/Http\/Kernel.php",
            "line": 151,
            "function": "then",
            "class": "Illuminate\\Pipeline\\Pipeline",
            "type": "->"
        },
        {
            "file": "\/Users\/ovac\/codes\/omnile\/booconnect\/vendor\/laravel\/framework\/src\/Illuminate\/Foundation\/Http\/Kernel.php",
            "line": 116,
            "function": "sendRequestThroughRouter",
            "class": "Illuminate\\Foundation\\Http\\Kernel",
            "type": "->"
        },
        {
            "file": "\/Users\/ovac\/codes\/omnile\/booconnect\/vendor\/mpociot\/laravel-apidoc-generator\/src\/Mpociot\/ApiDoc\/Generators\/LaravelGenerator.php",
            "line": 139,
            "function": "handle",
            "class": "Illuminate\\Foundation\\Http\\Kernel",
            "type": "->"
        },
        {
            "file": "\/Users\/ovac\/codes\/omnile\/booconnect\/vendor\/mpociot\/laravel-apidoc-generator\/src\/Mpociot\/ApiDoc\/Generators\/AbstractGenerator.php",
            "line": 125,
            "function": "callRoute",
            "class": "Mpociot\\ApiDoc\\Generators\\LaravelGenerator",
            "type": "->"
        },
        {
            "file": "\/Users\/ovac\/codes\/omnile\/booconnect\/vendor\/mpociot\/laravel-apidoc-generator\/src\/Mpociot\/ApiDoc\/Generators\/LaravelGenerator.php",
            "line": 79,
            "function": "getRouteResponse",
            "class": "Mpociot\\ApiDoc\\Generators\\AbstractGenerator",
            "type": "->"
        },
        {
            "file": "\/Users\/ovac\/codes\/omnile\/booconnect\/vendor\/mpociot\/laravel-apidoc-generator\/src\/Mpociot\/ApiDoc\/Commands\/GenerateDocumentation.php",
            "line": 264,
            "function": "processRoute",
            "class": "Mpociot\\ApiDoc\\Generators\\LaravelGenerator",
            "type": "->"
        },
        {
            "file": "\/Users\/ovac\/codes\/omnile\/booconnect\/vendor\/mpociot\/laravel-apidoc-generator\/src\/Mpociot\/ApiDoc\/Commands\/GenerateDocumentation.php",
            "line": 85,
            "function": "processLaravelRoutes",
            "class": "Mpociot\\ApiDoc\\Commands\\GenerateDocumentation",
            "type": "->"
        },
        {
            "function": "handle",
            "class": "Mpociot\\ApiDoc\\Commands\\GenerateDocumentation",
            "type": "->"
        },
        {
            "file": "\/Users\/ovac\/codes\/omnile\/booconnect\/vendor\/laravel\/framework\/src\/Illuminate\/Container\/BoundMethod.php",
            "line": 29,
            "function": "call_user_func_array"
        },
        {
            "file": "\/Users\/ovac\/codes\/omnile\/booconnect\/vendor\/laravel\/framework\/src\/Illuminate\/Container\/BoundMethod.php",
            "line": 87,
            "function": "Illuminate\\Container\\{closure}",
            "class": "Illuminate\\Container\\BoundMethod",
            "type": "::"
        },
        {
            "file": "\/Users\/ovac\/codes\/omnile\/booconnect\/vendor\/laravel\/framework\/src\/Illuminate\/Container\/BoundMethod.php",
            "line": 31,
            "function": "callBoundMethod",
            "class": "Illuminate\\Container\\BoundMethod",
            "type": "::"
        },
        {
            "file": "\/Users\/ovac\/codes\/omnile\/booconnect\/vendor\/laravel\/framework\/src\/Illuminate\/Container\/Container.php",
            "line": 564,
            "function": "call",
            "class": "Illuminate\\Container\\BoundMethod",
            "type": "::"
        },
        {
            "file": "\/Users\/ovac\/codes\/omnile\/booconnect\/vendor\/laravel\/framework\/src\/Illuminate\/Console\/Command.php",
            "line": 183,
            "function": "call",
            "class": "Illuminate\\Container\\Container",
            "type": "->"
        },
        {
            "file": "\/Users\/ovac\/codes\/omnile\/booconnect\/vendor\/symfony\/console\/Command\/Command.php",
            "line": 252,
            "function": "execute",
            "class": "Illuminate\\Console\\Command",
            "type": "->"
        },
        {
            "file": "\/Users\/ovac\/codes\/omnile\/booconnect\/vendor\/laravel\/framework\/src\/Illuminate\/Console\/Command.php",
            "line": 170,
            "function": "run",
            "class": "Symfony\\Component\\Console\\Command\\Command",
            "type": "->"
        },
        {
            "file": "\/Users\/ovac\/codes\/omnile\/booconnect\/vendor\/symfony\/console\/Application.php",
            "line": 865,
            "function": "run",
            "class": "Illuminate\\Console\\Command",
            "type": "->"
        },
        {
            "file": "\/Users\/ovac\/codes\/omnile\/booconnect\/vendor\/symfony\/console\/Application.php",
            "line": 241,
            "function": "doRunCommand",
            "class": "Symfony\\Component\\Console\\Application",
            "type": "->"
        },
        {
            "file": "\/Users\/ovac\/codes\/omnile\/booconnect\/vendor\/symfony\/console\/Application.php",
            "line": 143,
            "function": "doRun",
            "class": "Symfony\\Component\\Console\\Application",
            "type": "->"
        },
        {
            "file": "\/Users\/ovac\/codes\/omnile\/booconnect\/vendor\/laravel\/framework\/src\/Illuminate\/Console\/Application.php",
            "line": 88,
            "function": "run",
            "class": "Symfony\\Component\\Console\\Application",
            "type": "->"
        },
        {
            "file": "\/Users\/ovac\/codes\/omnile\/booconnect\/vendor\/laravel\/framework\/src\/Illuminate\/Foundation\/Console\/Kernel.php",
            "line": 121,
            "function": "run",
            "class": "Illuminate\\Console\\Application",
            "type": "->"
        },
        {
            "file": "\/Users\/ovac\/codes\/omnile\/booconnect\/artisan",
            "line": 37,
            "function": "handle",
            "class": "Illuminate\\Foundation\\Console\\Kernel",
            "type": "->"
        }
    ]
}
```

### HTTP Request
`GET api/v1/cart/{cart}/edit`

`HEAD api/v1/cart/{cart}/edit`


<!-- END_047c64f2b19f48ea37e72728e5bd305a -->

<!-- START_41412ed4b414717d56b418f4f9d05420 -->
## Update the specified resource in storage.

> Example request:

```bash
curl -X PUT "http://booconnect.run/api/v1/cart/{cart}" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "http://booconnect.run/api/v1/cart/{cart}",
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
`PUT api/v1/cart/{cart}`

`PATCH api/v1/cart/{cart}`


<!-- END_41412ed4b414717d56b418f4f9d05420 -->

<!-- START_a94e71cd52c25987988db15effc17eb8 -->
## Remove the specified resource from storage.

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
    "current_page": 1,
    "data": [
        {
            "id": 1,
            "name": "Braxton",
            "resturant_id": 49,
            "image": "https:\/\/lorempixel.com\/150\/150\/food\/?48466",
            "description": "Provident laboriosam occaecati quas tempora.",
            "price": 45,
            "user_id": 1,
            "measurement": "plate",
            "quantity": 18,
            "deleted_at": null,
            "created_at": "2018-02-24 16:37:18",
            "updated_at": "2018-02-24 16:37:18",
            "formatted_price": "GHC 45.00"
        },
        {
            "id": 2,
            "name": "Jordon",
            "resturant_id": 93,
            "image": "https:\/\/lorempixel.com\/150\/150\/food\/?84535",
            "description": "Quia beatae adipisci ut nobis.",
            "price": 90,
            "user_id": 1,
            "measurement": "bowl",
            "quantity": 84,
            "deleted_at": null,
            "created_at": "2018-02-24 16:37:18",
            "updated_at": "2018-02-24 16:37:18",
            "formatted_price": "GHC 90.00"
        },
        {
            "id": 3,
            "name": "Shanie",
            "resturant_id": 85,
            "image": "https:\/\/lorempixel.com\/150\/150\/food\/?55208",
            "description": "Repudiandae fuga hic natus ab qui illo hic.",
            "price": 68,
            "user_id": 1,
            "measurement": "bowl",
            "quantity": 73,
            "deleted_at": null,
            "created_at": "2018-02-24 16:37:18",
            "updated_at": "2018-02-24 16:37:18",
            "formatted_price": "GHC 68.00"
        },
        {
            "id": 4,
            "name": "Boyd",
            "resturant_id": 56,
            "image": "https:\/\/lorempixel.com\/150\/150\/food\/?12529",
            "description": "Tempora laboriosam numquam magnam aperiam.",
            "price": 61,
            "user_id": 1,
            "measurement": "bowl",
            "quantity": 96,
            "deleted_at": null,
            "created_at": "2018-02-24 16:37:18",
            "updated_at": "2018-02-24 16:37:18",
            "formatted_price": "GHC 61.00"
        },
        {
            "id": 5,
            "name": "Dexter",
            "resturant_id": 4,
            "image": "https:\/\/lorempixel.com\/150\/150\/food\/?18341",
            "description": "Repellendus voluptas voluptas eveniet error neque corporis.",
            "price": 24,
            "user_id": 1,
            "measurement": "plate",
            "quantity": 32,
            "deleted_at": null,
            "created_at": "2018-02-24 16:37:18",
            "updated_at": "2018-02-24 16:37:18",
            "formatted_price": "GHC 24.00"
        },
        {
            "id": 6,
            "name": "Alessandro",
            "resturant_id": 16,
            "image": "https:\/\/lorempixel.com\/150\/150\/food\/?44502",
            "description": "Dolores praesentium quis tempora fugiat quidem assumenda velit.",
            "price": 39,
            "user_id": 1,
            "measurement": "bowl",
            "quantity": 53,
            "deleted_at": null,
            "created_at": "2018-02-24 16:37:18",
            "updated_at": "2018-02-24 16:37:18",
            "formatted_price": "GHC 39.00"
        },
        {
            "id": 7,
            "name": "Yoshiko",
            "resturant_id": 96,
            "image": "https:\/\/lorempixel.com\/150\/150\/food\/?24412",
            "description": "Quia minus quisquam molestiae consequatur voluptatem facere.",
            "price": 87,
            "user_id": 1,
            "measurement": "plate",
            "quantity": 91,
            "deleted_at": null,
            "created_at": "2018-02-24 16:37:18",
            "updated_at": "2018-02-24 16:37:18",
            "formatted_price": "GHC 87.00"
        },
        {
            "id": 8,
            "name": "Hortense",
            "resturant_id": 4,
            "image": "https:\/\/lorempixel.com\/150\/150\/food\/?99245",
            "description": "Ullam qui aut facere eos.",
            "price": 22,
            "user_id": 1,
            "measurement": "plate",
            "quantity": 60,
            "deleted_at": null,
            "created_at": "2018-02-24 16:37:18",
            "updated_at": "2018-02-24 16:37:18",
            "formatted_price": "GHC 22.00"
        },
        {
            "id": 9,
            "name": "Jaren",
            "resturant_id": 87,
            "image": "https:\/\/lorempixel.com\/150\/150\/food\/?76181",
            "description": "Consequuntur doloremque quos quis ut animi.",
            "price": 23,
            "user_id": 1,
            "measurement": "plate",
            "quantity": 61,
            "deleted_at": null,
            "created_at": "2018-02-24 16:37:18",
            "updated_at": "2018-02-24 16:37:18",
            "formatted_price": "GHC 23.00"
        },
        {
            "id": 10,
            "name": "Trinity",
            "resturant_id": 8,
            "image": "https:\/\/lorempixel.com\/150\/150\/food\/?19557",
            "description": "Consectetur sit nesciunt ipsa.",
            "price": 100,
            "user_id": 1,
            "measurement": "plate",
            "quantity": 42,
            "deleted_at": null,
            "created_at": "2018-02-24 16:37:18",
            "updated_at": "2018-02-24 16:37:18",
            "formatted_price": "GHC 100.00"
        },
        {
            "id": 11,
            "name": "Bobbie",
            "resturant_id": 7,
            "image": "https:\/\/lorempixel.com\/150\/150\/food\/?23543",
            "description": "Eligendi et autem tempore iste laborum et labore.",
            "price": 7,
            "user_id": 1,
            "measurement": "bowl",
            "quantity": 39,
            "deleted_at": null,
            "created_at": "2018-02-24 16:37:18",
            "updated_at": "2018-02-24 16:37:18",
            "formatted_price": "GHC 7.00"
        },
        {
            "id": 12,
            "name": "Brock",
            "resturant_id": 24,
            "image": "https:\/\/lorempixel.com\/150\/150\/food\/?52840",
            "description": "Vel eveniet soluta alias ipsa.",
            "price": 66,
            "user_id": 1,
            "measurement": "bowl",
            "quantity": 25,
            "deleted_at": null,
            "created_at": "2018-02-24 16:37:18",
            "updated_at": "2018-02-24 16:37:18",
            "formatted_price": "GHC 66.00"
        },
        {
            "id": 13,
            "name": "Zita",
            "resturant_id": 81,
            "image": "https:\/\/lorempixel.com\/150\/150\/food\/?43307",
            "description": "Est blanditiis ut sapiente et.",
            "price": 9,
            "user_id": 1,
            "measurement": "bowl",
            "quantity": 77,
            "deleted_at": null,
            "created_at": "2018-02-24 16:37:18",
            "updated_at": "2018-02-24 16:37:18",
            "formatted_price": "GHC 9.00"
        },
        {
            "id": 14,
            "name": "Makenna",
            "resturant_id": 54,
            "image": "https:\/\/lorempixel.com\/150\/150\/food\/?93854",
            "description": "Consequuntur iusto neque exercitationem reiciendis ut doloremque ut.",
            "price": 33,
            "user_id": 1,
            "measurement": "bowl",
            "quantity": 73,
            "deleted_at": null,
            "created_at": "2018-02-24 16:37:18",
            "updated_at": "2018-02-24 16:37:18",
            "formatted_price": "GHC 33.00"
        },
        {
            "id": 15,
            "name": "Peggie",
            "resturant_id": 83,
            "image": "https:\/\/lorempixel.com\/150\/150\/food\/?54399",
            "description": "Nihil minus cupiditate quia illo cupiditate et.",
            "price": 7,
            "user_id": 1,
            "measurement": "bowl",
            "quantity": 38,
            "deleted_at": null,
            "created_at": "2018-02-24 16:37:18",
            "updated_at": "2018-02-24 16:37:18",
            "formatted_price": "GHC 7.00"
        },
        {
            "id": 16,
            "name": "Jermey",
            "resturant_id": 91,
            "image": "https:\/\/lorempixel.com\/150\/150\/food\/?83643",
            "description": "Nihil autem perferendis neque debitis.",
            "price": 45,
            "user_id": 1,
            "measurement": "plate",
            "quantity": 24,
            "deleted_at": null,
            "created_at": "2018-02-24 16:37:18",
            "updated_at": "2018-02-24 16:37:18",
            "formatted_price": "GHC 45.00"
        },
        {
            "id": 17,
            "name": "Zander",
            "resturant_id": 97,
            "image": "https:\/\/lorempixel.com\/150\/150\/food\/?93439",
            "description": "Maiores eos totam tenetur ut.",
            "price": 63,
            "user_id": 1,
            "measurement": "plate",
            "quantity": 76,
            "deleted_at": null,
            "created_at": "2018-02-24 16:37:18",
            "updated_at": "2018-02-24 16:37:18",
            "formatted_price": "GHC 63.00"
        },
        {
            "id": 18,
            "name": "Lonie",
            "resturant_id": 47,
            "image": "https:\/\/lorempixel.com\/150\/150\/food\/?67458",
            "description": "Enim est repellat non laboriosam praesentium commodi ad.",
            "price": 36,
            "user_id": 1,
            "measurement": "bowl",
            "quantity": 86,
            "deleted_at": null,
            "created_at": "2018-02-24 16:37:18",
            "updated_at": "2018-02-24 16:37:18",
            "formatted_price": "GHC 36.00"
        },
        {
            "id": 19,
            "name": "Riley",
            "resturant_id": 93,
            "image": "https:\/\/lorempixel.com\/150\/150\/food\/?61613",
            "description": "Sunt corporis et vel ea maxime qui adipisci.",
            "price": 18,
            "user_id": 1,
            "measurement": "bowl",
            "quantity": 27,
            "deleted_at": null,
            "created_at": "2018-02-24 16:37:18",
            "updated_at": "2018-02-24 16:37:18",
            "formatted_price": "GHC 18.00"
        },
        {
            "id": 20,
            "name": "Virginie",
            "resturant_id": 41,
            "image": "https:\/\/lorempixel.com\/150\/150\/food\/?29628",
            "description": "Eaque ab aliquam adipisci rerum odit id nam quam.",
            "price": 69,
            "user_id": 1,
            "measurement": "plate",
            "quantity": 9,
            "deleted_at": null,
            "created_at": "2018-02-24 16:37:18",
            "updated_at": "2018-02-24 16:37:18",
            "formatted_price": "GHC 69.00"
        }
    ],
    "first_page_url": "http:\/\/localhost\/api\/v1\/checkout?page=1",
    "from": 1,
    "last_page": 10,
    "last_page_url": "http:\/\/localhost\/api\/v1\/checkout?page=10",
    "next_page_url": "http:\/\/localhost\/api\/v1\/checkout?page=2",
    "path": "http:\/\/localhost\/api\/v1\/checkout",
    "per_page": 20,
    "prev_page_url": null,
    "to": 20,
    "total": 200
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
null
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
null
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
null
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
## List Items
Display a listing of the resource.

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
            "name": "Braxton",
            "resturant_id": 49,
            "image": "https:\/\/lorempixel.com\/150\/150\/food\/?48466",
            "description": "Provident laboriosam occaecati quas tempora.",
            "price": 45,
            "user_id": 1,
            "measurement": "plate",
            "quantity": 18,
            "deleted_at": null,
            "created_at": "2018-02-24 16:37:18",
            "updated_at": "2018-02-24 16:37:18",
            "formatted_price": "GHC 45.00"
        },
        {
            "id": 2,
            "name": "Jordon",
            "resturant_id": 93,
            "image": "https:\/\/lorempixel.com\/150\/150\/food\/?84535",
            "description": "Quia beatae adipisci ut nobis.",
            "price": 90,
            "user_id": 1,
            "measurement": "bowl",
            "quantity": 84,
            "deleted_at": null,
            "created_at": "2018-02-24 16:37:18",
            "updated_at": "2018-02-24 16:37:18",
            "formatted_price": "GHC 90.00"
        },
        {
            "id": 3,
            "name": "Shanie",
            "resturant_id": 85,
            "image": "https:\/\/lorempixel.com\/150\/150\/food\/?55208",
            "description": "Repudiandae fuga hic natus ab qui illo hic.",
            "price": 68,
            "user_id": 1,
            "measurement": "bowl",
            "quantity": 73,
            "deleted_at": null,
            "created_at": "2018-02-24 16:37:18",
            "updated_at": "2018-02-24 16:37:18",
            "formatted_price": "GHC 68.00"
        },
        {
            "id": 4,
            "name": "Boyd",
            "resturant_id": 56,
            "image": "https:\/\/lorempixel.com\/150\/150\/food\/?12529",
            "description": "Tempora laboriosam numquam magnam aperiam.",
            "price": 61,
            "user_id": 1,
            "measurement": "bowl",
            "quantity": 96,
            "deleted_at": null,
            "created_at": "2018-02-24 16:37:18",
            "updated_at": "2018-02-24 16:37:18",
            "formatted_price": "GHC 61.00"
        },
        {
            "id": 5,
            "name": "Dexter",
            "resturant_id": 4,
            "image": "https:\/\/lorempixel.com\/150\/150\/food\/?18341",
            "description": "Repellendus voluptas voluptas eveniet error neque corporis.",
            "price": 24,
            "user_id": 1,
            "measurement": "plate",
            "quantity": 32,
            "deleted_at": null,
            "created_at": "2018-02-24 16:37:18",
            "updated_at": "2018-02-24 16:37:18",
            "formatted_price": "GHC 24.00"
        },
        {
            "id": 6,
            "name": "Alessandro",
            "resturant_id": 16,
            "image": "https:\/\/lorempixel.com\/150\/150\/food\/?44502",
            "description": "Dolores praesentium quis tempora fugiat quidem assumenda velit.",
            "price": 39,
            "user_id": 1,
            "measurement": "bowl",
            "quantity": 53,
            "deleted_at": null,
            "created_at": "2018-02-24 16:37:18",
            "updated_at": "2018-02-24 16:37:18",
            "formatted_price": "GHC 39.00"
        },
        {
            "id": 7,
            "name": "Yoshiko",
            "resturant_id": 96,
            "image": "https:\/\/lorempixel.com\/150\/150\/food\/?24412",
            "description": "Quia minus quisquam molestiae consequatur voluptatem facere.",
            "price": 87,
            "user_id": 1,
            "measurement": "plate",
            "quantity": 91,
            "deleted_at": null,
            "created_at": "2018-02-24 16:37:18",
            "updated_at": "2018-02-24 16:37:18",
            "formatted_price": "GHC 87.00"
        },
        {
            "id": 8,
            "name": "Hortense",
            "resturant_id": 4,
            "image": "https:\/\/lorempixel.com\/150\/150\/food\/?99245",
            "description": "Ullam qui aut facere eos.",
            "price": 22,
            "user_id": 1,
            "measurement": "plate",
            "quantity": 60,
            "deleted_at": null,
            "created_at": "2018-02-24 16:37:18",
            "updated_at": "2018-02-24 16:37:18",
            "formatted_price": "GHC 22.00"
        },
        {
            "id": 9,
            "name": "Jaren",
            "resturant_id": 87,
            "image": "https:\/\/lorempixel.com\/150\/150\/food\/?76181",
            "description": "Consequuntur doloremque quos quis ut animi.",
            "price": 23,
            "user_id": 1,
            "measurement": "plate",
            "quantity": 61,
            "deleted_at": null,
            "created_at": "2018-02-24 16:37:18",
            "updated_at": "2018-02-24 16:37:18",
            "formatted_price": "GHC 23.00"
        },
        {
            "id": 10,
            "name": "Trinity",
            "resturant_id": 8,
            "image": "https:\/\/lorempixel.com\/150\/150\/food\/?19557",
            "description": "Consectetur sit nesciunt ipsa.",
            "price": 100,
            "user_id": 1,
            "measurement": "plate",
            "quantity": 42,
            "deleted_at": null,
            "created_at": "2018-02-24 16:37:18",
            "updated_at": "2018-02-24 16:37:18",
            "formatted_price": "GHC 100.00"
        },
        {
            "id": 11,
            "name": "Bobbie",
            "resturant_id": 7,
            "image": "https:\/\/lorempixel.com\/150\/150\/food\/?23543",
            "description": "Eligendi et autem tempore iste laborum et labore.",
            "price": 7,
            "user_id": 1,
            "measurement": "bowl",
            "quantity": 39,
            "deleted_at": null,
            "created_at": "2018-02-24 16:37:18",
            "updated_at": "2018-02-24 16:37:18",
            "formatted_price": "GHC 7.00"
        },
        {
            "id": 12,
            "name": "Brock",
            "resturant_id": 24,
            "image": "https:\/\/lorempixel.com\/150\/150\/food\/?52840",
            "description": "Vel eveniet soluta alias ipsa.",
            "price": 66,
            "user_id": 1,
            "measurement": "bowl",
            "quantity": 25,
            "deleted_at": null,
            "created_at": "2018-02-24 16:37:18",
            "updated_at": "2018-02-24 16:37:18",
            "formatted_price": "GHC 66.00"
        },
        {
            "id": 13,
            "name": "Zita",
            "resturant_id": 81,
            "image": "https:\/\/lorempixel.com\/150\/150\/food\/?43307",
            "description": "Est blanditiis ut sapiente et.",
            "price": 9,
            "user_id": 1,
            "measurement": "bowl",
            "quantity": 77,
            "deleted_at": null,
            "created_at": "2018-02-24 16:37:18",
            "updated_at": "2018-02-24 16:37:18",
            "formatted_price": "GHC 9.00"
        },
        {
            "id": 14,
            "name": "Makenna",
            "resturant_id": 54,
            "image": "https:\/\/lorempixel.com\/150\/150\/food\/?93854",
            "description": "Consequuntur iusto neque exercitationem reiciendis ut doloremque ut.",
            "price": 33,
            "user_id": 1,
            "measurement": "bowl",
            "quantity": 73,
            "deleted_at": null,
            "created_at": "2018-02-24 16:37:18",
            "updated_at": "2018-02-24 16:37:18",
            "formatted_price": "GHC 33.00"
        },
        {
            "id": 15,
            "name": "Peggie",
            "resturant_id": 83,
            "image": "https:\/\/lorempixel.com\/150\/150\/food\/?54399",
            "description": "Nihil minus cupiditate quia illo cupiditate et.",
            "price": 7,
            "user_id": 1,
            "measurement": "bowl",
            "quantity": 38,
            "deleted_at": null,
            "created_at": "2018-02-24 16:37:18",
            "updated_at": "2018-02-24 16:37:18",
            "formatted_price": "GHC 7.00"
        },
        {
            "id": 16,
            "name": "Jermey",
            "resturant_id": 91,
            "image": "https:\/\/lorempixel.com\/150\/150\/food\/?83643",
            "description": "Nihil autem perferendis neque debitis.",
            "price": 45,
            "user_id": 1,
            "measurement": "plate",
            "quantity": 24,
            "deleted_at": null,
            "created_at": "2018-02-24 16:37:18",
            "updated_at": "2018-02-24 16:37:18",
            "formatted_price": "GHC 45.00"
        },
        {
            "id": 17,
            "name": "Zander",
            "resturant_id": 97,
            "image": "https:\/\/lorempixel.com\/150\/150\/food\/?93439",
            "description": "Maiores eos totam tenetur ut.",
            "price": 63,
            "user_id": 1,
            "measurement": "plate",
            "quantity": 76,
            "deleted_at": null,
            "created_at": "2018-02-24 16:37:18",
            "updated_at": "2018-02-24 16:37:18",
            "formatted_price": "GHC 63.00"
        },
        {
            "id": 18,
            "name": "Lonie",
            "resturant_id": 47,
            "image": "https:\/\/lorempixel.com\/150\/150\/food\/?67458",
            "description": "Enim est repellat non laboriosam praesentium commodi ad.",
            "price": 36,
            "user_id": 1,
            "measurement": "bowl",
            "quantity": 86,
            "deleted_at": null,
            "created_at": "2018-02-24 16:37:18",
            "updated_at": "2018-02-24 16:37:18",
            "formatted_price": "GHC 36.00"
        },
        {
            "id": 19,
            "name": "Riley",
            "resturant_id": 93,
            "image": "https:\/\/lorempixel.com\/150\/150\/food\/?61613",
            "description": "Sunt corporis et vel ea maxime qui adipisci.",
            "price": 18,
            "user_id": 1,
            "measurement": "bowl",
            "quantity": 27,
            "deleted_at": null,
            "created_at": "2018-02-24 16:37:18",
            "updated_at": "2018-02-24 16:37:18",
            "formatted_price": "GHC 18.00"
        },
        {
            "id": 20,
            "name": "Virginie",
            "resturant_id": 41,
            "image": "https:\/\/lorempixel.com\/150\/150\/food\/?29628",
            "description": "Eaque ab aliquam adipisci rerum odit id nam quam.",
            "price": 69,
            "user_id": 1,
            "measurement": "plate",
            "quantity": 9,
            "deleted_at": null,
            "created_at": "2018-02-24 16:37:18",
            "updated_at": "2018-02-24 16:37:18",
            "formatted_price": "GHC 69.00"
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

<!-- START_d926c446cc9a4f6c267ac6773aeb53ee -->
## Show the form for creating a new resource.

> Example request:

```bash
curl -X GET "http://booconnect.run/api/v1/items/create" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "http://booconnect.run/api/v1/items/create",
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
null
```

### HTTP Request
`GET api/v1/items/create`

`HEAD api/v1/items/create`


<!-- END_d926c446cc9a4f6c267ac6773aeb53ee -->

<!-- START_7bd5f07d9ba801bd8687585c8cb91196 -->
## Store a newly created resource in storage.

> Example request:

```bash
curl -X POST "http://booconnect.run/api/v1/items" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "http://booconnect.run/api/v1/items",
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
`POST api/v1/items`


<!-- END_7bd5f07d9ba801bd8687585c8cb91196 -->

<!-- START_c82686db284c3bd830a93127392241c8 -->
## Show Item
Display the specified resource.

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
    "name": "Braxton",
    "resturant_id": 49,
    "image": "https:\/\/lorempixel.com\/150\/150\/food\/?48466",
    "description": "Provident laboriosam occaecati quas tempora.",
    "price": 45,
    "user_id": 1,
    "measurement": "plate",
    "quantity": 18,
    "deleted_at": null,
    "created_at": "2018-02-24 16:37:18",
    "updated_at": "2018-02-24 16:37:18",
    "formatted_price": "GHC 45.00",
    "pictures": {
        "id": 27,
        "imageable_id": 1,
        "path": "https:\/\/lorempixel.com\/150\/150\/food\/?10097",
        "description": "I'd hardly.",
        "imageable_type": "App\\Item",
        "created_at": "2018-02-24 16:37:19",
        "updated_at": "2018-02-24 16:37:19"
    }
}
```

### HTTP Request
`GET api/v1/items/{item}`

`HEAD api/v1/items/{item}`


<!-- END_c82686db284c3bd830a93127392241c8 -->

<!-- START_1075db24db4423ce910a1394fafdcb69 -->
## Show the form for editing the specified resource.

> Example request:

```bash
curl -X GET "http://booconnect.run/api/v1/items/{item}/edit" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "http://booconnect.run/api/v1/items/{item}/edit",
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
null
```

### HTTP Request
`GET api/v1/items/{item}/edit`

`HEAD api/v1/items/{item}/edit`


<!-- END_1075db24db4423ce910a1394fafdcb69 -->

<!-- START_919e8dbbe3f5f30687dcab2e5ab9877a -->
## Update the specified resource in storage.

> Example request:

```bash
curl -X PUT "http://booconnect.run/api/v1/items/{item}" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "http://booconnect.run/api/v1/items/{item}",
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
`PUT api/v1/items/{item}`

`PATCH api/v1/items/{item}`


<!-- END_919e8dbbe3f5f30687dcab2e5ab9877a -->

<!-- START_ba04c1a1da1988c5ceb2a873e3c8632d -->
## Remove the specified resource from storage.

> Example request:

```bash
curl -X DELETE "http://booconnect.run/api/v1/items/{item}" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "http://booconnect.run/api/v1/items/{item}",
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
`DELETE api/v1/items/{item}`


<!-- END_ba04c1a1da1988c5ceb2a873e3c8632d -->

#Orders

Orders resource endpoints
<!-- START_985d87fa04a157f2d8b59ef306bf6f06 -->
## List all orders
Display a listing of the resource.

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

<!-- START_c79cb2035f69ac8078c2cec9fc2fab4a -->
## Store a newly created resource in storage.

> Example request:

```bash
curl -X POST "http://booconnect.run/api/v1/orders" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "http://booconnect.run/api/v1/orders",
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
`POST api/v1/orders`


<!-- END_c79cb2035f69ac8078c2cec9fc2fab4a -->

<!-- START_13f4a2ba5be2993e266a0acf8d3bd280 -->
## Display the specified resource.

> Example request:

```bash
curl -X GET "http://booconnect.run/api/v1/orders/{order}" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "http://booconnect.run/api/v1/orders/{order}",
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
`GET api/v1/orders/{order}`

`HEAD api/v1/orders/{order}`


<!-- END_13f4a2ba5be2993e266a0acf8d3bd280 -->

<!-- START_f9c8be8efaa780daaa0328503bf2d45e -->
## Show the form for editing the specified resource.

> Example request:

```bash
curl -X GET "http://booconnect.run/api/v1/orders/{order}/edit" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "http://booconnect.run/api/v1/orders/{order}/edit",
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
`GET api/v1/orders/{order}/edit`

`HEAD api/v1/orders/{order}/edit`


<!-- END_f9c8be8efaa780daaa0328503bf2d45e -->

<!-- START_2e6d997181b1c50b2b94eaa14b66f016 -->
## Update the specified resource in storage.

> Example request:

```bash
curl -X PUT "http://booconnect.run/api/v1/orders/{order}" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "http://booconnect.run/api/v1/orders/{order}",
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
`PUT api/v1/orders/{order}`

`PATCH api/v1/orders/{order}`


<!-- END_2e6d997181b1c50b2b94eaa14b66f016 -->

<!-- START_f34ad9d71f18dd67576cc6db60268192 -->
## Remove the specified resource from storage.

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
## Display a listing of the resource.

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
            "name": "Zulauf Inc",
            "phone": "+1 (396) 808-4309",
            "registration_no": "14752",
            "first_name": "Laurine",
            "last_name": "Gibson",
            "user_id": "90",
            "image": "https:\/\/lorempixel.com\/150\/150\/nightlife\/?51612",
            "cover": "https:\/\/lorempixel.com\/500\/150\/technics\/?82385",
            "place": "Lake Eulalia",
            "city": "Port Larryberg",
            "state": "North Carolina",
            "country": "Bermuda",
            "address": "91701 Gibson Mission",
            "website": "gaylord.com",
            "description": "Est sint cumque ut facilis.",
            "phone_verified": 0,
            "email_verified": 1,
            "deleted_at": null,
            "created_at": "2018-02-24 16:37:17",
            "updated_at": "2018-02-24 16:37:17"
        },
        {
            "id": 2,
            "name": "Mann Inc",
            "phone": "(794) 819-8877 x281",
            "registration_no": "43076",
            "first_name": "Adam",
            "last_name": "Fisher",
            "user_id": "96",
            "image": "https:\/\/lorempixel.com\/150\/150\/nightlife\/?87217",
            "cover": "https:\/\/lorempixel.com\/500\/150\/technics\/?58215",
            "place": "West Kaleville",
            "city": "Lake Bohaven",
            "state": "Idaho",
            "country": "Syrian Arab Republic",
            "address": "67359 Thompson Track Suite 067",
            "website": "dibbert.com",
            "description": "Cum iste minus repudiandae deleniti dolores consequuntur accusantium.",
            "phone_verified": 1,
            "email_verified": 0,
            "deleted_at": null,
            "created_at": "2018-02-24 16:37:17",
            "updated_at": "2018-02-24 16:37:17"
        },
        {
            "id": 3,
            "name": "Schuppe-Douglas",
            "phone": "+14846544328",
            "registration_no": "65692",
            "first_name": "Reuben",
            "last_name": "Walker",
            "user_id": "6",
            "image": "https:\/\/lorempixel.com\/150\/150\/nightlife\/?17140",
            "cover": "https:\/\/lorempixel.com\/500\/150\/technics\/?84615",
            "place": "East Sandrinechester",
            "city": "Port Billiechester",
            "state": "Utah",
            "country": "Liberia",
            "address": "90423 Connelly Circles Apt. 321",
            "website": "wilkinson.biz",
            "description": "Eaque corrupti neque delectus tenetur excepturi dolores et fugit.",
            "phone_verified": 1,
            "email_verified": 0,
            "deleted_at": null,
            "created_at": "2018-02-24 16:37:17",
            "updated_at": "2018-02-24 16:37:17"
        },
        {
            "id": 4,
            "name": "Koch, Ullrich and Cormier",
            "phone": "1-234-293-9532",
            "registration_no": "97876",
            "first_name": "Lori",
            "last_name": "Hessel",
            "user_id": "56",
            "image": "https:\/\/lorempixel.com\/150\/150\/nightlife\/?31149",
            "cover": "https:\/\/lorempixel.com\/500\/150\/technics\/?91705",
            "place": "West Zoraburgh",
            "city": "Port Diamondland",
            "state": "Louisiana",
            "country": "Slovakia (Slovak Republic)",
            "address": "327 Brown Shoal Apt. 901",
            "website": "kemmer.com",
            "description": "Veniam beatae eveniet rem consequuntur qui blanditiis ex.",
            "phone_verified": 0,
            "email_verified": 1,
            "deleted_at": null,
            "created_at": "2018-02-24 16:37:17",
            "updated_at": "2018-02-24 16:37:17"
        },
        {
            "id": 5,
            "name": "Lueilwitz-Botsford",
            "phone": "228-914-1417",
            "registration_no": "46659",
            "first_name": "Zola",
            "last_name": "Goodwin",
            "user_id": "61",
            "image": "https:\/\/lorempixel.com\/150\/150\/nightlife\/?74577",
            "cover": "https:\/\/lorempixel.com\/500\/150\/technics\/?23994",
            "place": "Lake Connie",
            "city": "New Maximillianport",
            "state": "Pennsylvania",
            "country": "Bhutan",
            "address": "2424 Gerhold Burgs",
            "website": "stracke.biz",
            "description": "Voluptas autem rem at ex odit quia quam.",
            "phone_verified": 0,
            "email_verified": 1,
            "deleted_at": null,
            "created_at": "2018-02-24 16:37:17",
            "updated_at": "2018-02-24 16:37:17"
        },
        {
            "id": 6,
            "name": "Powlowski Inc",
            "phone": "(737) 767-7086 x8238",
            "registration_no": "68706",
            "first_name": "Tate",
            "last_name": "Goyette",
            "user_id": "13",
            "image": "https:\/\/lorempixel.com\/150\/150\/nightlife\/?70091",
            "cover": "https:\/\/lorempixel.com\/500\/150\/technics\/?82221",
            "place": "Vivianneside",
            "city": "Sipesstad",
            "state": "Hawaii",
            "country": "Palestinian Territories",
            "address": "4284 Ross Crest Apt. 735",
            "website": "hane.com",
            "description": "Dolores qui tempora tempore consequatur ut earum.",
            "phone_verified": 1,
            "email_verified": 0,
            "deleted_at": null,
            "created_at": "2018-02-24 16:37:17",
            "updated_at": "2018-02-24 16:37:17"
        },
        {
            "id": 7,
            "name": "Hartmann and Sons",
            "phone": "862.735.7695 x534",
            "registration_no": "4931",
            "first_name": "Evans",
            "last_name": "Oberbrunner",
            "user_id": "32",
            "image": "https:\/\/lorempixel.com\/150\/150\/nightlife\/?83957",
            "cover": "https:\/\/lorempixel.com\/500\/150\/technics\/?80729",
            "place": "Morarland",
            "city": "Port Mariano",
            "state": "Colorado",
            "country": "Sao Tome and Principe",
            "address": "659 Hilpert Shoal",
            "website": "ullrich.biz",
            "description": "Et veritatis corrupti nostrum officia illum.",
            "phone_verified": 1,
            "email_verified": 1,
            "deleted_at": null,
            "created_at": "2018-02-24 16:37:17",
            "updated_at": "2018-02-24 16:37:17"
        },
        {
            "id": 8,
            "name": "Walsh, Roob and Runte",
            "phone": "+1-557-639-8400",
            "registration_no": "52804",
            "first_name": "Maryjane",
            "last_name": "Breitenberg",
            "user_id": "3",
            "image": "https:\/\/lorempixel.com\/150\/150\/nightlife\/?68762",
            "cover": "https:\/\/lorempixel.com\/500\/150\/technics\/?21385",
            "place": "South Georgeview",
            "city": "Reicherthaven",
            "state": "North Carolina",
            "country": "United Arab Emirates",
            "address": "2578 Hamill Street Suite 205",
            "website": "sipes.com",
            "description": "Quos at voluptatem consequatur rerum dolor.",
            "phone_verified": 1,
            "email_verified": 1,
            "deleted_at": null,
            "created_at": "2018-02-24 16:37:17",
            "updated_at": "2018-02-24 16:37:17"
        },
        {
            "id": 9,
            "name": "Rau and Sons",
            "phone": "+1-276-514-1248",
            "registration_no": "90868",
            "first_name": "Llewellyn",
            "last_name": "Ratke",
            "user_id": "50",
            "image": "https:\/\/lorempixel.com\/150\/150\/nightlife\/?84988",
            "cover": "https:\/\/lorempixel.com\/500\/150\/technics\/?95601",
            "place": "Keelingview",
            "city": "West Rosemarie",
            "state": "New Hampshire",
            "country": "Tuvalu",
            "address": "94839 Mann Point",
            "website": "stiedemann.com",
            "description": "Minus sed distinctio sunt.",
            "phone_verified": 0,
            "email_verified": 0,
            "deleted_at": null,
            "created_at": "2018-02-24 16:37:17",
            "updated_at": "2018-02-24 16:37:17"
        },
        {
            "id": 10,
            "name": "Rath-Blick",
            "phone": "881-338-9450",
            "registration_no": "71199",
            "first_name": "Christa",
            "last_name": "O'Conner",
            "user_id": "27",
            "image": "https:\/\/lorempixel.com\/150\/150\/nightlife\/?28017",
            "cover": "https:\/\/lorempixel.com\/500\/150\/technics\/?12317",
            "place": "Whiteview",
            "city": "South Stanton",
            "state": "Indiana",
            "country": "Tuvalu",
            "address": "4441 Hannah Garden Suite 350",
            "website": "mueller.biz",
            "description": "Commodi omnis nesciunt quia iure reiciendis dolores est.",
            "phone_verified": 1,
            "email_verified": 0,
            "deleted_at": null,
            "created_at": "2018-02-24 16:37:17",
            "updated_at": "2018-02-24 16:37:17"
        },
        {
            "id": 11,
            "name": "Sauer Group",
            "phone": "+1 (743) 586-5744",
            "registration_no": "76520",
            "first_name": "Dejah",
            "last_name": "Goyette",
            "user_id": "25",
            "image": "https:\/\/lorempixel.com\/150\/150\/nightlife\/?89144",
            "cover": "https:\/\/lorempixel.com\/500\/150\/technics\/?30976",
            "place": "Hillshaven",
            "city": "Vinceport",
            "state": "Illinois",
            "country": "Saint Pierre and Miquelon",
            "address": "2589 Leora Forks Apt. 698",
            "website": "zieme.info",
            "description": "Voluptate illo veritatis commodi.",
            "phone_verified": 1,
            "email_verified": 0,
            "deleted_at": null,
            "created_at": "2018-02-24 16:37:17",
            "updated_at": "2018-02-24 16:37:17"
        },
        {
            "id": 12,
            "name": "Dibbert, Rogahn and Cronin",
            "phone": "245.968.2762 x1793",
            "registration_no": "31143",
            "first_name": "Gerald",
            "last_name": "Powlowski",
            "user_id": "13",
            "image": "https:\/\/lorempixel.com\/150\/150\/nightlife\/?16894",
            "cover": "https:\/\/lorempixel.com\/500\/150\/technics\/?48347",
            "place": "Bethfort",
            "city": "North Christophe",
            "state": "New Hampshire",
            "country": "Slovenia",
            "address": "247 Hudson Knoll",
            "website": "hermann.com",
            "description": "Alias enim exercitationem ut vero ut eos.",
            "phone_verified": 0,
            "email_verified": 1,
            "deleted_at": null,
            "created_at": "2018-02-24 16:37:17",
            "updated_at": "2018-02-24 16:37:17"
        },
        {
            "id": 13,
            "name": "Gleason PLC",
            "phone": "+1.717.393.6370",
            "registration_no": "70078",
            "first_name": "Giovanna",
            "last_name": "Towne",
            "user_id": "95",
            "image": "https:\/\/lorempixel.com\/150\/150\/nightlife\/?28451",
            "cover": "https:\/\/lorempixel.com\/500\/150\/technics\/?60893",
            "place": "New Darien",
            "city": "Corbinstad",
            "state": "Wisconsin",
            "country": "Martinique",
            "address": "4528 Cheyanne Drives",
            "website": "gerlach.com",
            "description": "Sequi et hic voluptatibus ipsam omnis.",
            "phone_verified": 1,
            "email_verified": 0,
            "deleted_at": null,
            "created_at": "2018-02-24 16:37:17",
            "updated_at": "2018-02-24 16:37:17"
        },
        {
            "id": 14,
            "name": "Kuhn-Stracke",
            "phone": "+1-518-657-9647",
            "registration_no": "92976",
            "first_name": "Johnpaul",
            "last_name": "Effertz",
            "user_id": "16",
            "image": "https:\/\/lorempixel.com\/150\/150\/nightlife\/?25768",
            "cover": "https:\/\/lorempixel.com\/500\/150\/technics\/?33537",
            "place": "South Angelitafort",
            "city": "Trantowborough",
            "state": "North Dakota",
            "country": "Guinea-Bissau",
            "address": "792 McGlynn Harbor Apt. 051",
            "website": "hand.com",
            "description": "Inventore eos consequatur occaecati expedita accusantium.",
            "phone_verified": 1,
            "email_verified": 0,
            "deleted_at": null,
            "created_at": "2018-02-24 16:37:17",
            "updated_at": "2018-02-24 16:37:17"
        },
        {
            "id": 15,
            "name": "Medhurst, Renner and Ritchie",
            "phone": "(402) 519-2091 x62526",
            "registration_no": "73682",
            "first_name": "Jeromy",
            "last_name": "Rohan",
            "user_id": "85",
            "image": "https:\/\/lorempixel.com\/150\/150\/nightlife\/?91984",
            "cover": "https:\/\/lorempixel.com\/500\/150\/technics\/?84707",
            "place": "Bridgettefort",
            "city": "Lake Webster",
            "state": "Michigan",
            "country": "Azerbaijan",
            "address": "45473 Larissa Radial Apt. 176",
            "website": "jacobi.com",
            "description": "Ea libero eius reiciendis repellendus ut debitis dolorem.",
            "phone_verified": 1,
            "email_verified": 0,
            "deleted_at": null,
            "created_at": "2018-02-24 16:37:17",
            "updated_at": "2018-02-24 16:37:17"
        },
        {
            "id": 16,
            "name": "Stokes and Sons",
            "phone": "1-476-512-1471 x77192",
            "registration_no": "81198",
            "first_name": "Corine",
            "last_name": "Greenfelder",
            "user_id": "20",
            "image": "https:\/\/lorempixel.com\/150\/150\/nightlife\/?94973",
            "cover": "https:\/\/lorempixel.com\/500\/150\/technics\/?81515",
            "place": "West Malvinaville",
            "city": "Randyfort",
            "state": "Tennessee",
            "country": "Togo",
            "address": "651 Streich Skyway Suite 771",
            "website": "bins.net",
            "description": "Ipsam sed omnis voluptatem et laboriosam totam.",
            "phone_verified": 0,
            "email_verified": 1,
            "deleted_at": null,
            "created_at": "2018-02-24 16:37:17",
            "updated_at": "2018-02-24 16:37:17"
        },
        {
            "id": 17,
            "name": "Thompson Ltd",
            "phone": "410.316.2477 x693",
            "registration_no": "44335",
            "first_name": "Jess",
            "last_name": "Considine",
            "user_id": "80",
            "image": "https:\/\/lorempixel.com\/150\/150\/nightlife\/?10647",
            "cover": "https:\/\/lorempixel.com\/500\/150\/technics\/?18607",
            "place": "South Emerson",
            "city": "New Immanuel",
            "state": "Oklahoma",
            "country": "Costa Rica",
            "address": "895 Ondricka Turnpike Suite 152",
            "website": "bartell.info",
            "description": "Explicabo inventore aspernatur ducimus est.",
            "phone_verified": 1,
            "email_verified": 1,
            "deleted_at": null,
            "created_at": "2018-02-24 16:37:17",
            "updated_at": "2018-02-24 16:37:17"
        },
        {
            "id": 18,
            "name": "Nitzsche and Sons",
            "phone": "(356) 420-1008 x9645",
            "registration_no": "29193",
            "first_name": "Nia",
            "last_name": "Hickle",
            "user_id": "66",
            "image": "https:\/\/lorempixel.com\/150\/150\/nightlife\/?60454",
            "cover": "https:\/\/lorempixel.com\/500\/150\/technics\/?59107",
            "place": "East Julianne",
            "city": "South Geraldine",
            "state": "Utah",
            "country": "Dominican Republic",
            "address": "37180 Zena Forest",
            "website": "grimes.com",
            "description": "Magni quod eos corporis cumque repudiandae est.",
            "phone_verified": 1,
            "email_verified": 0,
            "deleted_at": null,
            "created_at": "2018-02-24 16:37:17",
            "updated_at": "2018-02-24 16:37:17"
        },
        {
            "id": 19,
            "name": "Pfeffer, Altenwerth and Ullrich",
            "phone": "323.340.3572 x044",
            "registration_no": "14318",
            "first_name": "Dangelo",
            "last_name": "Jacobs",
            "user_id": "31",
            "image": "https:\/\/lorempixel.com\/150\/150\/nightlife\/?72518",
            "cover": "https:\/\/lorempixel.com\/500\/150\/technics\/?47693",
            "place": "Lake Janychester",
            "city": "Runolfsdottirfort",
            "state": "Kansas",
            "country": "Ireland",
            "address": "4310 Turner Wall",
            "website": "strosin.com",
            "description": "In eum maiores error voluptatem.",
            "phone_verified": 0,
            "email_verified": 0,
            "deleted_at": null,
            "created_at": "2018-02-24 16:37:17",
            "updated_at": "2018-02-24 16:37:17"
        },
        {
            "id": 20,
            "name": "Ward-Erdman",
            "phone": "583.968.3019",
            "registration_no": "13965",
            "first_name": "Luciano",
            "last_name": "Dibbert",
            "user_id": "39",
            "image": "https:\/\/lorempixel.com\/150\/150\/nightlife\/?56421",
            "cover": "https:\/\/lorempixel.com\/500\/150\/technics\/?90241",
            "place": "Wuckerthaven",
            "city": "Lake Amaya",
            "state": "Illinois",
            "country": "Isle of Man",
            "address": "31069 Hickle Cliffs Suite 379",
            "website": "cremin.com",
            "description": "Exercitationem possimus quas non et iste error et.",
            "phone_verified": 0,
            "email_verified": 0,
            "deleted_at": null,
            "created_at": "2018-02-24 16:37:17",
            "updated_at": "2018-02-24 16:37:17"
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

<!-- START_a07983172a04d58cf049c251c2f898f3 -->
## Show the form for creating a new resource.

> Example request:

```bash
curl -X GET "http://booconnect.run/api/v1/resturants/create" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "http://booconnect.run/api/v1/resturants/create",
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
null
```

### HTTP Request
`GET api/v1/resturants/create`

`HEAD api/v1/resturants/create`


<!-- END_a07983172a04d58cf049c251c2f898f3 -->

<!-- START_febb293390ecddc1f8218113ece4dbed -->
## Store a newly created resource in storage.

> Example request:

```bash
curl -X POST "http://booconnect.run/api/v1/resturants" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "http://booconnect.run/api/v1/resturants",
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
`POST api/v1/resturants`


<!-- END_febb293390ecddc1f8218113ece4dbed -->

<!-- START_5c475d198dde109f40d350154d38700d -->
## Display the specified resource.

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
    "name": "Zulauf Inc",
    "phone": "+1 (396) 808-4309",
    "registration_no": "14752",
    "first_name": "Laurine",
    "last_name": "Gibson",
    "user_id": "90",
    "image": "https:\/\/lorempixel.com\/150\/150\/nightlife\/?51612",
    "cover": "https:\/\/lorempixel.com\/500\/150\/technics\/?82385",
    "place": "Lake Eulalia",
    "city": "Port Larryberg",
    "state": "North Carolina",
    "country": "Bermuda",
    "address": "91701 Gibson Mission",
    "website": "gaylord.com",
    "description": "Est sint cumque ut facilis.",
    "phone_verified": 0,
    "email_verified": 1,
    "deleted_at": null,
    "created_at": "2018-02-24 16:37:17",
    "updated_at": "2018-02-24 16:37:17",
    "items": {
        "current_page": 1,
        "data": [
            {
                "id": 98,
                "name": "Jalyn",
                "resturant_id": 1,
                "image": "https:\/\/lorempixel.com\/150\/150\/food\/?78735",
                "description": "Enim sed et officia nulla itaque.",
                "price": 92,
                "user_id": 1,
                "measurement": "plate",
                "quantity": 41,
                "deleted_at": null,
                "created_at": "2018-02-24 16:37:18",
                "updated_at": "2018-02-24 16:37:18",
                "formatted_price": "GHC 92.00"
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

<!-- START_3a21b5f6d9a56085af928230389f797e -->
## Show the form for editing the specified resource.

> Example request:

```bash
curl -X GET "http://booconnect.run/api/v1/resturants/{resturant}/edit" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "http://booconnect.run/api/v1/resturants/{resturant}/edit",
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
null
```

### HTTP Request
`GET api/v1/resturants/{resturant}/edit`

`HEAD api/v1/resturants/{resturant}/edit`


<!-- END_3a21b5f6d9a56085af928230389f797e -->

<!-- START_849633cf5473bf4d0571eab9e3866dca -->
## Update the specified resource in storage.

> Example request:

```bash
curl -X PUT "http://booconnect.run/api/v1/resturants/{resturant}" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "http://booconnect.run/api/v1/resturants/{resturant}",
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
`PUT api/v1/resturants/{resturant}`

`PATCH api/v1/resturants/{resturant}`


<!-- END_849633cf5473bf4d0571eab9e3866dca -->

<!-- START_749c4704248edd855b6ca4722052fd36 -->
## Remove the specified resource from storage.

> Example request:

```bash
curl -X DELETE "http://booconnect.run/api/v1/resturants/{resturant}" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "http://booconnect.run/api/v1/resturants/{resturant}",
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
`DELETE api/v1/resturants/{resturant}`


<!-- END_749c4704248edd855b6ca4722052fd36 -->

#Verify

phone verification endpoints
<!-- START_aa558d00f323830cf03c0cdf62bf4f4f -->
## Display a listing of the resource.

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

<!-- START_75d029285a6014fbe3dea9ac047fe456 -->
## Show the form for creating a new resource.

> Example request:

```bash
curl -X GET "http://booconnect.run/api/v1/verify/create" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "http://booconnect.run/api/v1/verify/create",
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
`GET api/v1/verify/create`

`HEAD api/v1/verify/create`


<!-- END_75d029285a6014fbe3dea9ac047fe456 -->

<!-- START_2986fe2644729ef9fa55818efeeda18c -->
## Store a newly created resource in storage.

> Example request:

```bash
curl -X POST "http://booconnect.run/api/v1/verify" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "http://booconnect.run/api/v1/verify",
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
`POST api/v1/verify`


<!-- END_2986fe2644729ef9fa55818efeeda18c -->

<!-- START_bd0686bcd77d2e86915477144181cb4d -->
## Display the specified resource.

> Example request:

```bash
curl -X GET "http://booconnect.run/api/v1/verify/{verify}" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "http://booconnect.run/api/v1/verify/{verify}",
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
`GET api/v1/verify/{verify}`

`HEAD api/v1/verify/{verify}`


<!-- END_bd0686bcd77d2e86915477144181cb4d -->

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
## Update the specified resource in storage.

> Example request:

```bash
curl -X PUT "http://booconnect.run/api/v1/verify/{verify}" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "http://booconnect.run/api/v1/verify/{verify}",
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
`PUT api/v1/verify/{verify}`

`PATCH api/v1/verify/{verify}`


<!-- END_3b30ae7fc7fb9e3fea044b298668df82 -->

<!-- START_56dd8d9950105f6c47c0eba843d56c04 -->
## Remove the specified resource from storage.

> Example request:

```bash
curl -X DELETE "http://booconnect.run/api/v1/verify/{verify}" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "http://booconnect.run/api/v1/verify/{verify}",
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
`DELETE api/v1/verify/{verify}`


<!-- END_56dd8d9950105f6c47c0eba843d56c04 -->

#Wishlist

Item-Wishlist resource endpoints
<!-- START_3f8d78a807f16aa9a1195e047bf25b96 -->
## Display a listing of the resource.

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
    "current_page": 1,
    "data": [
        {
            "id": 1,
            "name": "Braxton",
            "resturant_id": 49,
            "image": "https:\/\/lorempixel.com\/150\/150\/food\/?48466",
            "description": "Provident laboriosam occaecati quas tempora.",
            "price": 45,
            "user_id": 1,
            "measurement": "plate",
            "quantity": 18,
            "deleted_at": null,
            "created_at": "2018-02-24 16:37:18",
            "updated_at": "2018-02-24 16:37:18",
            "formatted_price": "GHC 45.00"
        },
        {
            "id": 2,
            "name": "Jordon",
            "resturant_id": 93,
            "image": "https:\/\/lorempixel.com\/150\/150\/food\/?84535",
            "description": "Quia beatae adipisci ut nobis.",
            "price": 90,
            "user_id": 1,
            "measurement": "bowl",
            "quantity": 84,
            "deleted_at": null,
            "created_at": "2018-02-24 16:37:18",
            "updated_at": "2018-02-24 16:37:18",
            "formatted_price": "GHC 90.00"
        },
        {
            "id": 3,
            "name": "Shanie",
            "resturant_id": 85,
            "image": "https:\/\/lorempixel.com\/150\/150\/food\/?55208",
            "description": "Repudiandae fuga hic natus ab qui illo hic.",
            "price": 68,
            "user_id": 1,
            "measurement": "bowl",
            "quantity": 73,
            "deleted_at": null,
            "created_at": "2018-02-24 16:37:18",
            "updated_at": "2018-02-24 16:37:18",
            "formatted_price": "GHC 68.00"
        },
        {
            "id": 4,
            "name": "Boyd",
            "resturant_id": 56,
            "image": "https:\/\/lorempixel.com\/150\/150\/food\/?12529",
            "description": "Tempora laboriosam numquam magnam aperiam.",
            "price": 61,
            "user_id": 1,
            "measurement": "bowl",
            "quantity": 96,
            "deleted_at": null,
            "created_at": "2018-02-24 16:37:18",
            "updated_at": "2018-02-24 16:37:18",
            "formatted_price": "GHC 61.00"
        },
        {
            "id": 5,
            "name": "Dexter",
            "resturant_id": 4,
            "image": "https:\/\/lorempixel.com\/150\/150\/food\/?18341",
            "description": "Repellendus voluptas voluptas eveniet error neque corporis.",
            "price": 24,
            "user_id": 1,
            "measurement": "plate",
            "quantity": 32,
            "deleted_at": null,
            "created_at": "2018-02-24 16:37:18",
            "updated_at": "2018-02-24 16:37:18",
            "formatted_price": "GHC 24.00"
        },
        {
            "id": 6,
            "name": "Alessandro",
            "resturant_id": 16,
            "image": "https:\/\/lorempixel.com\/150\/150\/food\/?44502",
            "description": "Dolores praesentium quis tempora fugiat quidem assumenda velit.",
            "price": 39,
            "user_id": 1,
            "measurement": "bowl",
            "quantity": 53,
            "deleted_at": null,
            "created_at": "2018-02-24 16:37:18",
            "updated_at": "2018-02-24 16:37:18",
            "formatted_price": "GHC 39.00"
        },
        {
            "id": 7,
            "name": "Yoshiko",
            "resturant_id": 96,
            "image": "https:\/\/lorempixel.com\/150\/150\/food\/?24412",
            "description": "Quia minus quisquam molestiae consequatur voluptatem facere.",
            "price": 87,
            "user_id": 1,
            "measurement": "plate",
            "quantity": 91,
            "deleted_at": null,
            "created_at": "2018-02-24 16:37:18",
            "updated_at": "2018-02-24 16:37:18",
            "formatted_price": "GHC 87.00"
        },
        {
            "id": 8,
            "name": "Hortense",
            "resturant_id": 4,
            "image": "https:\/\/lorempixel.com\/150\/150\/food\/?99245",
            "description": "Ullam qui aut facere eos.",
            "price": 22,
            "user_id": 1,
            "measurement": "plate",
            "quantity": 60,
            "deleted_at": null,
            "created_at": "2018-02-24 16:37:18",
            "updated_at": "2018-02-24 16:37:18",
            "formatted_price": "GHC 22.00"
        },
        {
            "id": 9,
            "name": "Jaren",
            "resturant_id": 87,
            "image": "https:\/\/lorempixel.com\/150\/150\/food\/?76181",
            "description": "Consequuntur doloremque quos quis ut animi.",
            "price": 23,
            "user_id": 1,
            "measurement": "plate",
            "quantity": 61,
            "deleted_at": null,
            "created_at": "2018-02-24 16:37:18",
            "updated_at": "2018-02-24 16:37:18",
            "formatted_price": "GHC 23.00"
        },
        {
            "id": 10,
            "name": "Trinity",
            "resturant_id": 8,
            "image": "https:\/\/lorempixel.com\/150\/150\/food\/?19557",
            "description": "Consectetur sit nesciunt ipsa.",
            "price": 100,
            "user_id": 1,
            "measurement": "plate",
            "quantity": 42,
            "deleted_at": null,
            "created_at": "2018-02-24 16:37:18",
            "updated_at": "2018-02-24 16:37:18",
            "formatted_price": "GHC 100.00"
        },
        {
            "id": 11,
            "name": "Bobbie",
            "resturant_id": 7,
            "image": "https:\/\/lorempixel.com\/150\/150\/food\/?23543",
            "description": "Eligendi et autem tempore iste laborum et labore.",
            "price": 7,
            "user_id": 1,
            "measurement": "bowl",
            "quantity": 39,
            "deleted_at": null,
            "created_at": "2018-02-24 16:37:18",
            "updated_at": "2018-02-24 16:37:18",
            "formatted_price": "GHC 7.00"
        },
        {
            "id": 12,
            "name": "Brock",
            "resturant_id": 24,
            "image": "https:\/\/lorempixel.com\/150\/150\/food\/?52840",
            "description": "Vel eveniet soluta alias ipsa.",
            "price": 66,
            "user_id": 1,
            "measurement": "bowl",
            "quantity": 25,
            "deleted_at": null,
            "created_at": "2018-02-24 16:37:18",
            "updated_at": "2018-02-24 16:37:18",
            "formatted_price": "GHC 66.00"
        },
        {
            "id": 13,
            "name": "Zita",
            "resturant_id": 81,
            "image": "https:\/\/lorempixel.com\/150\/150\/food\/?43307",
            "description": "Est blanditiis ut sapiente et.",
            "price": 9,
            "user_id": 1,
            "measurement": "bowl",
            "quantity": 77,
            "deleted_at": null,
            "created_at": "2018-02-24 16:37:18",
            "updated_at": "2018-02-24 16:37:18",
            "formatted_price": "GHC 9.00"
        },
        {
            "id": 14,
            "name": "Makenna",
            "resturant_id": 54,
            "image": "https:\/\/lorempixel.com\/150\/150\/food\/?93854",
            "description": "Consequuntur iusto neque exercitationem reiciendis ut doloremque ut.",
            "price": 33,
            "user_id": 1,
            "measurement": "bowl",
            "quantity": 73,
            "deleted_at": null,
            "created_at": "2018-02-24 16:37:18",
            "updated_at": "2018-02-24 16:37:18",
            "formatted_price": "GHC 33.00"
        },
        {
            "id": 15,
            "name": "Peggie",
            "resturant_id": 83,
            "image": "https:\/\/lorempixel.com\/150\/150\/food\/?54399",
            "description": "Nihil minus cupiditate quia illo cupiditate et.",
            "price": 7,
            "user_id": 1,
            "measurement": "bowl",
            "quantity": 38,
            "deleted_at": null,
            "created_at": "2018-02-24 16:37:18",
            "updated_at": "2018-02-24 16:37:18",
            "formatted_price": "GHC 7.00"
        },
        {
            "id": 16,
            "name": "Jermey",
            "resturant_id": 91,
            "image": "https:\/\/lorempixel.com\/150\/150\/food\/?83643",
            "description": "Nihil autem perferendis neque debitis.",
            "price": 45,
            "user_id": 1,
            "measurement": "plate",
            "quantity": 24,
            "deleted_at": null,
            "created_at": "2018-02-24 16:37:18",
            "updated_at": "2018-02-24 16:37:18",
            "formatted_price": "GHC 45.00"
        },
        {
            "id": 17,
            "name": "Zander",
            "resturant_id": 97,
            "image": "https:\/\/lorempixel.com\/150\/150\/food\/?93439",
            "description": "Maiores eos totam tenetur ut.",
            "price": 63,
            "user_id": 1,
            "measurement": "plate",
            "quantity": 76,
            "deleted_at": null,
            "created_at": "2018-02-24 16:37:18",
            "updated_at": "2018-02-24 16:37:18",
            "formatted_price": "GHC 63.00"
        },
        {
            "id": 18,
            "name": "Lonie",
            "resturant_id": 47,
            "image": "https:\/\/lorempixel.com\/150\/150\/food\/?67458",
            "description": "Enim est repellat non laboriosam praesentium commodi ad.",
            "price": 36,
            "user_id": 1,
            "measurement": "bowl",
            "quantity": 86,
            "deleted_at": null,
            "created_at": "2018-02-24 16:37:18",
            "updated_at": "2018-02-24 16:37:18",
            "formatted_price": "GHC 36.00"
        },
        {
            "id": 19,
            "name": "Riley",
            "resturant_id": 93,
            "image": "https:\/\/lorempixel.com\/150\/150\/food\/?61613",
            "description": "Sunt corporis et vel ea maxime qui adipisci.",
            "price": 18,
            "user_id": 1,
            "measurement": "bowl",
            "quantity": 27,
            "deleted_at": null,
            "created_at": "2018-02-24 16:37:18",
            "updated_at": "2018-02-24 16:37:18",
            "formatted_price": "GHC 18.00"
        },
        {
            "id": 20,
            "name": "Virginie",
            "resturant_id": 41,
            "image": "https:\/\/lorempixel.com\/150\/150\/food\/?29628",
            "description": "Eaque ab aliquam adipisci rerum odit id nam quam.",
            "price": 69,
            "user_id": 1,
            "measurement": "plate",
            "quantity": 9,
            "deleted_at": null,
            "created_at": "2018-02-24 16:37:18",
            "updated_at": "2018-02-24 16:37:18",
            "formatted_price": "GHC 69.00"
        }
    ],
    "first_page_url": "http:\/\/localhost\/api\/v1\/wishlist?page=1",
    "from": 1,
    "last_page": 10,
    "last_page_url": "http:\/\/localhost\/api\/v1\/wishlist?page=10",
    "next_page_url": "http:\/\/localhost\/api\/v1\/wishlist?page=2",
    "path": "http:\/\/localhost\/api\/v1\/wishlist",
    "per_page": 20,
    "prev_page_url": null,
    "to": 20,
    "total": 200
}
```

### HTTP Request
`GET api/v1/wishlist`

`HEAD api/v1/wishlist`


<!-- END_3f8d78a807f16aa9a1195e047bf25b96 -->

<!-- START_4d1fa3ad1690a80d42de9d2152ca4e1a -->
## Show the form for creating a new resource.

> Example request:

```bash
curl -X GET "http://booconnect.run/api/v1/wishlist/create" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "http://booconnect.run/api/v1/wishlist/create",
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
null
```

### HTTP Request
`GET api/v1/wishlist/create`

`HEAD api/v1/wishlist/create`


<!-- END_4d1fa3ad1690a80d42de9d2152ca4e1a -->

<!-- START_3e7cbd9fc15711ca2f1ba22883c3187f -->
## Store a newly created resource in storage.

> Example request:

```bash
curl -X POST "http://booconnect.run/api/v1/wishlist" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "http://booconnect.run/api/v1/wishlist",
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
`POST api/v1/wishlist`


<!-- END_3e7cbd9fc15711ca2f1ba22883c3187f -->

<!-- START_9b0ce4f4d71dda14c2a6c1d9e9f6cfa0 -->
## Display the specified resource.

> Example request:

```bash
curl -X GET "http://booconnect.run/api/v1/wishlist/{wishlist}" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "http://booconnect.run/api/v1/wishlist/{wishlist}",
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
null
```

### HTTP Request
`GET api/v1/wishlist/{wishlist}`

`HEAD api/v1/wishlist/{wishlist}`


<!-- END_9b0ce4f4d71dda14c2a6c1d9e9f6cfa0 -->

<!-- START_668ac0755487582515e20f5e9791b6d5 -->
## Show the form for editing the specified resource.

> Example request:

```bash
curl -X GET "http://booconnect.run/api/v1/wishlist/{wishlist}/edit" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "http://booconnect.run/api/v1/wishlist/{wishlist}/edit",
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
null
```

### HTTP Request
`GET api/v1/wishlist/{wishlist}/edit`

`HEAD api/v1/wishlist/{wishlist}/edit`


<!-- END_668ac0755487582515e20f5e9791b6d5 -->

<!-- START_a2e2e72ff4213d3012d24922a62cca37 -->
## Update the specified resource in storage.

> Example request:

```bash
curl -X PUT "http://booconnect.run/api/v1/wishlist/{wishlist}" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "http://booconnect.run/api/v1/wishlist/{wishlist}",
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
`PUT api/v1/wishlist/{wishlist}`

`PATCH api/v1/wishlist/{wishlist}`


<!-- END_a2e2e72ff4213d3012d24922a62cca37 -->

<!-- START_a5f004f583dea1e2c1062ef16977de92 -->
## Remove the specified resource from storage.

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

