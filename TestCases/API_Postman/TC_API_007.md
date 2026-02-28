# filmru – Test Case 7

## ID: TC-API-007
## Title: Delete game (unsupported method)

### Preconditions:
- Postman is opened;
- Collection is imported (Collection is located in directory “Api/Postman”);
- API endpoint is available.

### Steps:
1. Send DELETE request to `/game/dota-2`.

### Expected Result:
- Status 405 Method Not Allowed.
