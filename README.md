# Experiment 6: React Forms & Client-Side Validation

## 🎯 Aim
To create and validate forms in a React application using controlled components and client-side validation techniques.

---

## 🧰 Software Requirements
- Node.js  
- React.js  
- VS Code  
- Web Browser  

---

## 📚 Theory

### Controlled Components
Controlled components in React store form data inside the component’s state. This provides full control over user input and allows validation, dynamic updates, and better data handling.

### Client-Side Validation
Client-side validation checks user input before form submission. It improves user experience by providing instant feedback and reduces incorrect data submission.

---

## 📝 Experiment Description

This experiment consists of two parts:

---

## 🔹 Part 1: Registration Form (Controlled Components)

A user registration form was created using React controlled components.

### 📋 Fields Included
- First Name  
- Last Name  
- Gender (Radio Buttons)  
- Address  
- Date of Birth (Date Picker)  
- State (Dropdown with all Indian States & Union Territories)  
- Skills (Checkboxes: Python, Java, C++)  
- Submit Button  

### 🧠 Concepts Used
- useState for state management  
- Handling input change events  
- Managing checkbox selections using arrays  
- Handling form submission  

<img width="456" height="847" alt="Screenshot 2026-03-02 100156" src="https://github.com/user-attachments/assets/7d50e05c-c876-485e-a25a-7cd6b34a746a" />

---

## 🔹 Part 2: Login Form with Client-Side Validation

A login form was created with real-time validation for email and password.

### 📋 Fields Included
1. Email ID  
2. Password  

---

## ✅ Email Validation Rules

✔ Must contain exactly one `@`  
✔ Must include a valid domain name  
✔ Must include extension (.com, .in, etc.)  
✔ Username cannot end with domain words like `.com` before @  

### ✔ Valid Examples
- user@gmail.com  
- rishabh.kumar@yahoo.in  

### ❌ Invalid Examples
- rishabh.com@gmail.com  
- user@gmail  
- @@gmail.com  

---

## 🔐 Password Validation Rules

Password must:

1. Start with a **capital letter**  
2. Contain at least **one number**  
3. Contain at least **one special character**  
4. Be at least **5 characters long**  

### ✔ Valid Examples
- A@123  
- Secure@9  

### ❌ Invalid Examples
- abc@1  
- Abcde  
- A1234  

<img width="453" height="680" alt="Screenshot 2026-03-02 100307" src="https://github.com/user-attachments/assets/10e52b1d-072c-42bb-95ff-35055e1c82b4" />

<img width="452" height="660" alt="Screenshot 2026-03-02 100324" src="https://github.com/user-attachments/assets/30f0cf40-5aae-42f7-a689-0f8d0e74d153" />

---

## ⚙️ Features Implemented

✅ Controlled form inputs  
✅ Radio button & checkbox handling  
✅ Dropdown selection  
✅ Real-time email validation  
✅ Password strength validation  
✅ Instant feedback messages  
✅ Conditional form submission  
✅ Clean & responsive UI  

---

## 🚀 How to Run the Project

### 1️⃣ Install dependencies
```bash
npm install
npm start
http://localhost:3000
```
---
🧠 Learning Outcomes

Understanding controlled components in React

Handling multiple form inputs efficiently

Implementing client-side validation using Regex

Providing real-time user feedback

Improving UI/UX with validation messages

---

📌 Conclusion

This experiment demonstrated how React controlled components manage form data effectively and how client-side validation ensures correct input before submission. These techniques enhance usability, reliability, and overall user experience.

---

👨‍💻 Author

Rishabh Wadhwa

23BAI71442
