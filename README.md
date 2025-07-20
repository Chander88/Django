## 📦 Requirements
This project implements **OAuth2 Authorization Code Flow** using **FastAPI** and **Google OAuth**. After users authenticate via Google, your server issues a **JWT token** for use in protected routes.

- Python 3.8+
- Google Cloud OAuth2 Credentials

### 🔧 Install dependencies
This is the updated 
```bash
pip install fastapi[all] authlib python-jose[cryptography]

GOOGLE_CLIENT_ID=your-google-client-id
GOOGLE_CLIENT_SECRET=your-google-client-secret
uvicorn main:app --reload
