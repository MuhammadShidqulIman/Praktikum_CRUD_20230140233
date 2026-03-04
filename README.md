Tampilan web
<img width="2875" height="1529" alt="image" src="https://github.com/user-attachments/assets/09d9d200-e160-4c6b-9a34-98f1cdc45820" />

1. Create User
Endpoint: POST /api/users

Request Body:
{
  "name" : "Shidqul",
  "age" : 21
}

Response Body (success):
{
    "data": {
        "age": 21,
        "id": "a0fdf9ad-7043-4103-ad5e-ac4bd89a6182",
        "name": "Shidqul"
    },
    "status": "success"
}

Response Body (failed):
{
    "timestamp": "2026-03-04T04:43:25.248Z",
    "status": 500,
    "error": "Internal Server Error",
    "path": "/api/users"
}

2. Update User
Endpoint: PUT /api/users/{id}

Request Body:
{
  "name" : "Shidqul",
  "age" : 22
}

Response Body (success):
{
    "data": {
        "age": 22,
        "id": "a0fdf9ad-7043-4103-ad5e-ac4bd89a6182",
        "name": "Shidqul"
    },
    "status": "success"
}

3. Get User
Endpoint: GET /api/users

Response Body (success):
{
    "data": [
        {
            "age": 22,
            "id": "a0fdf9ad-7043-4103-ad5e-ac4bd89a6182",
            "name": "Shidqul"
        },
        {
            "age": 20,
            "id": "ffe36667-f437-4246-b0ca-902ed039d934",
            "name": "Muhammad Shidqul Iman"
        }
    ],
    "status": "success"
}

4 DELETE User
Endpoint: DELETE /api/users/{id}

Response Body (success):
{
    "status": "success delete user with id a0fdf9ad-7043-4103-ad5e-ac4bd89a6182"
}

DATABASE
<img width="2876" height="1702" alt="image" src="https://github.com/user-attachments/assets/c1750975-ff5e-4e8f-8212-fe427928c575" />




