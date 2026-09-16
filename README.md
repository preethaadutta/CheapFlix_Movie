# 🎬 CheapFlix – Web Design and Databases Coursework

## 🎯 Project Overview
CheapFlix is a web based streaming service application developed as part of the Web Design and Databases module coursework.  
The system simulates a subscription based movie streaming platform similar to Netflix with multiple subscription plans, user management, payment simulation, admin features, and database integration.

This project demonstrates full stack web development using Flask and SQLite with a responsive user interface and automated testing.

---

## 🌟 Features Implemented

### User Features
- User registration and login  
- User profile management  
- View available movies  
- Subscription selection  
- Payment simulation  
- Secure authentication  
- Responsive web interface  

### Admin Features
- Admin dashboard  
- Add new movies  
- View registered users  
- View user activity  
- Basic reporting features  

### Database Features
- User table  
- Movie table  
- Subscription table  
- Payment table  
- Relational mapping between users, subscriptions, and payments  

### Testing
- Automated unit tests for:
  - Models  
  - Routes  
  - Payment logic  

---

## 🛠 Technologies Used

- Frontend:  
  - HTML  
  - CSS  
  - JavaScript  

- Backend:  
  - Python  
  - Flask  

- Database:  
  - SQLite  

- Testing:  
  - PyTest  

- Tools:  
  - VS Code  
  - Git  
  - Browser for UI testing  

---


---

## ⚙️ How to Run the Project

### 1️⃣ Step 1: Create Virtual Environment
```bash
python -m venv venv
```

### 2️⃣ Step 2: Activate Virtual Environment
Windows:
```bash
venv\Scripts\activate
```
Mac or Linux:
```bash
source venv/bin/activate
```

### 3️⃣ Step 3: Install Dependencies
```bash
pip install -r requirements.txt
```

### 4️⃣ Step 4: Run the Application
```bash
python run.py
```

### 5️⃣ Step 5: Open in Browser
```bash
http://127.0.0.1:5000
```

---

## 🔐 Admin Login Details (For Testing)

Email: admin@cheapflix.com  
Password: admin123  

Note  
These credentials are for academic testing only.

---

## How to Run Tests
```bash
pytest
```

Test coverage includes:
- User creation  
- Payment simulation  
- Route responses  
- Database model validation  

---

## 🧩 Database Design

The database follows relational design principles:

- One user can have one subscription  
- One user can have multiple payments  
- Movies are stored independently  
- Subscriptions link users and payment history  

Tables:
- users  
- movies  
- subscriptions  
- payments  

---

## Assumptions Made

- Payments are simulated and not connected to real payment gateways  
- Movie files are placeholders  
- Email sending is not connected to real email services  
- Currency conversion is not implemented and is simulated  
- Device restriction logic is not enforced in current version  
- Subscription cancellation logic is not enforced in current version  

---

## 🔮 Future Improvements

- Implement currency conversion  
- Add email notifications for receipts and new movies  
- Enforce device restrictions  
- Implement subscription upgrade and downgrade logic  
- Add cancellation notice workflow  
- Add monthly revenue analytics  
- Improve admin reporting dashboard  
- Add charts and visual analytics  

---

## Academic Declaration

This project was developed for educational purposes only as part of the Web Design and Databases module.  
External references were used for learning and development following Harvard referencing guidelines in the final report.

---

## Author

Developed By: Preethaa Dutta 
University: Ravensbourne University London  
Module: Web Design and Databases  
Year: 2025  
