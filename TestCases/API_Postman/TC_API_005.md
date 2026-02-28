# filmru – Test Case 5

## ID: TC-API-005
## Title: Resource not found

### Preconditions:
- Postman is opened;
- Collection is imported (Collection is located in directory “Api/Postman”);
- API endpoint is available.

### Steps:
1. Send GET request to `/movies/999999`.

### Expected Result:
- Status 404; response body contains error message “Страница не найдена”.
