# filmru – Checklist. API (Backend validation via Network monitoring)

## 1. HTTP Methods:
- GET – retrieve data (e.g., list of movies);
- POST – create data (new review, new collection);
- PUT/PATCH – update data (edit profile);
- DELETE – delete data (delete account/delete collection).

## 2. Status Codes:
- 200 OK – successful request;
- 201 Created – resource successfully created;
- 400 Bad Request – request error;
- 401 Unauthorized – no authorization;
- 404 Not Found – resource not found;
- 500 Internal Server Error – server error.

## 3. Response Body:
- Verify that the data is returned correctly (e.g., JSON with required fields);
- Verify that there are no extra or empty values.

## 4. Positive Cases:
- Successful registration via API;
- Successful login;
- Adding a movie to a collection.

## 5. Negative Cases:
- Attempt to register with an invalid or empty email;
- Login with an incorrect password;
- Request to a non‑existent resource.
