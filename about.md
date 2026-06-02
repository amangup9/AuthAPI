Demo link: https://bit.ly/4hvD1Je

This module provides services for user registration, login with JWT token issuance, token refresh and revocation (in-memory), and access to protected resources upon valid token request.

JWT Authentication Integration: Implemented secure JWT-based authentication with a custom token service, JwtUtil, and JwtFilter, providing secure access to APIs.
User Management: Designed and implemented user operations in UserService with repository access via UserRepository.
Environment Configuration: Used .env file for environment-specific configurations and sensitive data management.
Dockerized Deployment: Added a Dockerfile and docker-compose.yml for containerized deployments, making it easy to deploy in any environment.
