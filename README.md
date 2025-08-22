# Login
## Features

- **Signup**: Naya user register kare.
- **Login**: Registered user login kare.
- **Postman ready**: Saare endpoints Postman se easily test kiye ja sakte hain.
- **JSON responses**: Clear success/error messages.

---

## API Endpoints

### 1. Signup

- **URL**: `/signup`
- **Method**: `POST`
- **Request Body** (JSON):
```json
{
  "name": "Aarti Kumari",
  "email": "aarti@example.com",
  "password": "yourpassword"
}
{
  "success": true,
  "message": "User registered successfully"
}
{
  "success": false,
  "message": "Email already registered"
}
