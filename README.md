
## 🚀 Getting Started

### 1. Create and Activate a Virtual Environment

#### Windows
```
python -m venv venv
venv\Scripts\activate
```

#### Mac/Linux
```
python3 -m venv venv
source venv/bin/activate
```

---

### 2. Install Dependencies
```
pip install -r requirements.txt
```

---

### 3. Run the FastAPI Server
```
uvicorn main:app --reload
```

The server will start at:  
```
http://localhost:8000
```

---

## 🧪 API Endpoints (Postman Testing)

### 🔹 Transcribe Audio  
- **Method**: POST  
- **URL**:  
```
http://localhost:8000/transcribe/
```  
- **Body**: form-data  
  - Key: `file`  
  - Value: *(Select your audio file)*

---

### 🔹 Analyze Transcription  
- **Method**: GET 
- **URL**:  
```
http://localhost:8000/analyze/
```

---

✅ Make sure the server is running before testing the endpoints.

---

## 📂 Project Structure
```
project/
├── main.py
├── requirements.txt
├── venv/
└── .env
```

---




