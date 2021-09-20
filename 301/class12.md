# CRUD

#### CRUD - Create Read Update Delete

##### Methods for CRUD

- Create - use POST

- Read - use GET

- Update - use PUT or PATCH

- Delete - use DELETE

- Status code - first number is the status class, then a code afterward. A reason for the error might be shown as well.

- 100-199 - This refers to the header being received from the client by the server and the server will begin to work through the request. The server will tell the client whether it passed or failed.

- 200-299 - Success, request received.

- 300-399 - Redirection. Resource unavailable or not at expected location.

- 400-499 - Error. Invalid request from client to server. (timeouts, missing information, etc)

- 500-599 - Server Error - Commonly referring to overloaded and/or servers not reachable. Sometimes from a client request.

- The 202 code specifically does not necessarily mean success, just that the requirements have been met from an asynchronous request.

- 308 - Permanent Redirect - States that there has been a permanent redirect, change to the location. Resource has been moved to the url stated in location header.

- 204 - No Content - Updates returning no content beck to the client that requested the data.

- 410 - Gone - This resource used to exist but is now gone. The implication is that the server knows that it used to exist.

- 403 - Forbidden - Server understood but denied (did not authorize) the request.
