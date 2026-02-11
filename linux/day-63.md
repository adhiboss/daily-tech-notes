# Day 63
## Focus
HTTP Request Methods (GET, POST, PUT, DELETE)

## GET
- Used to fetch data from server
- No request body normally
- Safe and idempotent

Example:
- Fetch a webpage
- Fetch API data

## POST
- Used to send data to server
- Creates new resource or submits form
- Not idempotent

Example:
- login form submission
- creating a new user

## PUT
- Used to update or replace a resource
- Idempotent

Example:
- update user profile completely

## DELETE
- Used to delete a resource
- Idempotent

Example:
- delete a post or record

## PATCH
- Partial update of a resource
- Not always idempotent

Example:
- update only email field

## Observations
- GET should not modify server state
- POST is most common for form/API submission
- PUT replaces entire resource, PATCH modifies partial
- DELETE removes resource from server
