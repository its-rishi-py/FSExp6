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

<img width="580" height="889" alt="Screenshot 2026-02-23 152912" src="https://github.com/user-attachments/assets/27ef6cf1-10c3-40d3-b42c-47ac41f8d04c" />

<img width="461" height="875" alt="Screenshot 2026-02-23 152922" src="https://github.com/user-attachments/assets/62e8c2df-9e75-430e-81a0-6b8593749cf2" />


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

<img width="465" height="606" alt="Screenshot 2026-02-23 153414" src="https://github.com/user-attachments/assets/719991db-4ec3-46ce-8947-78ec607b1fcd" />

<img width="461" height="701" alt="image" src="https://github.com/user-attachments/assets/a7413e79-14d8-4267-ae76-ac3d98d992a8" />

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
