# filmru – Test Case 1

## ID: TC-API-001
## Title: Get list of movies

### Preconditions:
- Postman is opened;
- Collection is imported (Collection is located in directory “Api/Postman”);
- API endpoint is available.

### Steps:
1. Send GET request to `/compilation/samye-lampovye-filmy`.

### Expected Result:
- Status 200; response body contains list of movies consistent with UI.
