# Website-Performance-Testing-JMeter
Performance testing of a website using JMeter.
# Reqres API Performance Testing with JMeter

This project uses **Apache JMeter** to perform performance testing on the Reqres API. We simulate multiple users accessing the API to check how it handles user registration, login, and fetching user data under load.

## Endpoints Tested
1. **GET /api/users?page=2**: Retrieve a paginated list of users.
2. **POST /api/login**: Simulate user login with valid credentials.
3. **GET /api/users/2**: Retrieve a single user.

## Results

Performance metrics, such as response times and throughput, will be displayed in the JMeter listeners.

