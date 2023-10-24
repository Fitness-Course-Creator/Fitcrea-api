# Fitcrea-api
Api documentation of Fitcrea

<strong>Fitcrea API</strong> provides functionality for developers to fetch users and view courses on the FitCrea platform.

## Get started

To get the API access, email info@fitcrea.com to give the account access.

We are using bearer token authorization.

## API functions

Api endpoints are called by the appropriate HTTP methods.

* GET - returns data about object, does not make any change
* POST - sends new data object
* PUT - updates existing data object
* DELETE - deletes data object

## HTTP codes

* 200 OK - everything is fine and the data is returned correctly
* 201 Created - sent data was accepted and entity created
* 204 No content - response for your request does not contain any data
* 400 Bad Request - the data sent by the client are not valid (detailed description is returned in the message attribute)
* 401 Unauthorized - unauthorized access, missing or bad client_id
* 403 Forbidden - you do not have access to this endpoint and method combination
* 404 Not Found - requested data not found
* 429 Too Many Requests - you have been rate limited and should slow down your request rate
* 500 Internal Server Error - may be caused e.g. by unavailable access to one of the system interfaces (database, webservices)

# Users

[List users](/docs/list_users.md)

[Create user](/docs/create_user.md.md)

[View User](/docs/view_user.md.md)

[Manager User Courses](/docs/manage_user_courses.md.md)

# Courses

[List courses](/docs/list_courses.md)

[View course](/docs/view_course.md)


## Data validation

API requests are validated. If there are any errors to fix, error list is returned in the response body.


## Release notes

| Date        |    What's new                                                                                           |
|-------------|---------------------------------------------------------------------------------------------------------|
| 24.10.2023  |    Added support for lisiting, creating, viewing users and managing their courses                       |
|-------------|---------------------------------------------------------------------------------------------------------|
