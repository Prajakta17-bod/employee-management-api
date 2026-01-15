                                 
   Employee Management REST API
   
This is a REST API built using Django REST Framework to manage employees in a company. It supports:

- Create, Read, Update, Delete (CRUD) operations
- JWT token-based authentication
- Filtering by department and role
- Pagination (10 results per page)
- Proper error handling with HTTP status codes

---

## Setup Instructions

1. **Clone the repository**
```bash
git clone https://github.com/yourusername/employee-management-api.git

2. Navigate to the project folder
cd employee_api

 3.Install dependencies
pip install -r requirements.txt


4. Apply database migrations
python manage.py migrate

5.Run the server
python manage.py runserver

Authentication
Obtain a JWT token by sending a POST request to:
POST /api/token/

Include the token in the Authorization header (Bearer Token) for all API requests.
