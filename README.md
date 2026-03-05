# Experiment 9: Authentication Methods in Flask
This experiment demonstrates three different authentication methods implemented in a Flask web application:
1. Basic Authentication - Using HTTP Basic Auth headers
2. Simple Token Authentication - Custom token-based authentication with base64 encoding
3. JWT Authentication - JSON Web Token authentication using Flask-JWT-Extended

# Features
- In-memory user store with predefined users (admin/admin123, kumud/kumud123)
- Three authentication endpoints for each method
- Protected routes that require authentication
- JSON responses for all endpoints

# LEARNING OUTCOMES:

1. HTTP Basic Authentication
   - How Basic Auth headers are formatted and transmitted
   - The role of username and password in HTTP header

2. Token-Based Authentication
   - How custom tokens can be generated and validated
   - Base64 encoding for token representation

3. JWT (JSON Web Token) Authentication
   - JWT structure and components (header, payload, signature)
   - How to generate and validate JWT tokens

4. General Authentication Concepts
   - Difference between authentication and authorization
   - Server-side vs client-side authentication handling

5. Flask Application Development
   - Building protected routes with decorators
   - Handling authentication headers in Flask
