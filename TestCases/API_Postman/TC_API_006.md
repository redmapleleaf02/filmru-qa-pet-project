# filmru – Test Case 6

## ID: TC-API-006
## Title: Delete movie (unsupported method)

### Preconditions:
- Postman is opened;
- Collection is imported (Collection is located in directory “Api/Postman”);
- API endpoint is available.

### Steps:
1. Send DELETE request to `/movies/sumerki-0`.

### Expected Result:
- Status 405 Method Not Allowed.
