#introduction
Various javascript files

### apiservice.js
an angular service file for Database-connection and management with oauth2 and Webservice (ex.Apigility)
get, save (post), put, patch, delete. Some parameters with .filter({}).



```bash
  ##get
  APIService
    .service('my-webservice-path')
    .filter({name: value})
    .get(function(response){
        // some code
  })
  
  ##post
  APIService
    .service('my-webservice-path')
    .filter({name: value})
    .save(function(response){
        // some code
  })
  
  etc..  

```

