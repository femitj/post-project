# post-project
posting service with nodeJs, restAPI using JSON server

Install JSON Server

``` npm install -g json-server ```

create a db.json file with some data
```
{
    "posts": [
        {
           "id": 1,
           "title": "Post One",
           "body": "this is post one" 
        },
        {
            "id": 2,
            "title": "Post Two",
            "body": "this is post two" 
         },
         {
            "id": 3,
            "title": "Post Three",
            "body": "this is post three" 
         }
    ]
}
```

Add to your package.json 'sripts' 
```
"json:server": "json-server --watch db.json"
```
