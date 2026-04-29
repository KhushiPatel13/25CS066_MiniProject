# 🔐 Secure Login System with OTP (C++)

A simple console-based Login System with OTP Authentication implemented in C++.  
This project demonstrates basic security concepts like password verification, account lockout, and one-time password (OTP) validation.

---

## 📌 Features

- 👤 User login with username & password  
- 🔒 Account lock after multiple wrong password attempts  
- 🔑 OTP (One-Time Password) generation  
- ⏳ OTP expiry (valid for 30 seconds)  
- ⚠️ Only one chance to enter OTP
  - Wrong OTP → Login failed  
  - Expired OTP → Login failed  
- 🧹 Simple and clean console interface (no special characters)

---

## 🛠️ Technologies Used

- C++ (Standard Library)
- Concepts used:
  - map
  - struct
  - time functions
  - basic OOP

---

## 🚀 How It Works

1. User enters username and password
2. System verifies credentials
3. If correct:
   - OTP is generated and shown on console
4. User enters OTP:
   - ✅ Correct → Login successful  
   - ❌ Wrong OR expired → Login failed (no retry)

---

## 🧪 Demo Accounts

| Username | Password  |
|----------|----------|
| alice    | pass123  |
| bob      | secure!  |

---

## ⚙️ How to Run

### 1. Compile
bash g++ main.cpp -o login 

### 2. Run
bash ./login 

---

## 📂 Project Structure

. ├── main.cpp └── README.md

---

## ⚠️ Limitations

- OTP is displayed in console (not sent via email/SMS)
- No database (data stored in memory)
- No encryption for passwords
- Basic implementation (for learning purposes)

---

## 💡 Future Improvements

- 📧 Send OTP via Email/SMS API  
- 🔐 Password hashing (security upgrade)  
- ⏱️ Real-time OTP countdown timer  
- 🎨 Better UI (GUI or Web version)  
- 🗄️ Database integration  

---

## 📜 License

This project is for educational purposes and free to use.

---

## 🙌 Author

Made with C++ for learning authentication sys