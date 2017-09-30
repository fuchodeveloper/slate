# Errors

The more recipes API uses the following error codes:


Error Code | Meaning
---------- | -------
400 | Bad Request -- You sent a bad request to our server.
401 | Unauthorized -- You are not authorized to perform action.
403 | Forbidden -- The action requested is hidden for administrators only.
404 | Not Found -- The specified recipe could not be found.
405 | Method Not Allowed -- You tried to access a recipe with an invalid method.
406 | Not Acceptable -- You requested a format that isn't json.
410 | Gone -- The recipe requested has been removed from our servers.
429 | Too Many Requests -- You're requesting too many recipes.
500 | Internal Server Error -- We had a problem with our server. Try again later.
503 | Service Unavailable -- We're temporarily offline for maintenance. Please try again later.
