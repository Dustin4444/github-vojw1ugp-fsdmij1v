# API Documentation

## Endpoints

### GET /api/users
- Description: Retrieve a list of users
- Response: JSON array of user objects

### POST /api/users
- Description: Create a new user
- Request Body: JSON object with user details
- Response: JSON object of the created user

### GET /api/users/{id}
- Description: Retrieve a specific user by ID
- Response: JSON object of the user

### PUT /api/users/{id}
- Description: Update a specific user by ID
- Request Body: JSON object with updated user details
- Response: JSON object of the updated user

### DELETE /api/users/{id}
- Description: Delete a specific user by ID
- Response: JSON object with a success message
