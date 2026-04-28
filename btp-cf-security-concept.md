# BTP CF Security Concept

* When API is called, it first goes to CF router
* It routes the request to applications
* It first routes to xsuaa
* It will validate the user and generate jwt token
* If we call the API trigger which we got for business process without jwt then we will error
* While calling the API from postman
* Set the authentication type as OATH2
* For bearer token - get the xsuaa url from bpa service key
* Put the url, client id, client password
* In xsuaa url, append /oath/token
* Get jwt token
* Then call the API again
