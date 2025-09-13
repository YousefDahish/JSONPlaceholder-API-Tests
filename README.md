# JSONPlaceholder-API-Tests

This project contains a Postman Collection for testing the [JSONPlaceholder](https://jsonplaceholder.typicode.com/) public API.

##  Project Structure
- **collections/** → Contains Postman collection JSON file.

##  How to Run

### 1. Import into Postman
- Open Postman → Import → Select `JSONPlaceholder_API_Collection.postman_collection.json`.

### 2. Run with Newman

```bash
# Install Newman globally
npm install -g newman

# Run the collection
newman run collections/JSONPlaceholder_API_Collection.postman_collection.json
