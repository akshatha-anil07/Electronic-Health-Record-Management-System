# Electronic-Health-Record-Management-System-

The Electronic Health Records (EHR) Management System is a digital solution designed to  modernize healthcare by transitioning from paper-based to fully electronic records. This project leverages a hybrid database architecture combining a Relational Database Management System (RDBMS) for structured data and MongoDB for unstructured data, enabling efficient storage, real time updates, and seamless data access. The system supports four primary user roles—patients, doctors, pharmacies, and laboratories—each with dedicated functionalities to streamline healthcare processes, including appointment scheduling, prescription management, and laboratory test orders. 
To enhance user experience and operational efficiency, an AI-driven chatbot is integrated to automate administrative tasks, such as handling inquiries and assisting with patient onboarding. Additionally, the system addresses societal concerns by improving healthcare accessibility, reducing medical errors, and fostering equity. By providing a centralized and interoperable digital framework, this project aims to transform healthcare delivery, ensuring efficiency, accuracy, and enhanced patient outcomes evolving healthcare landscape.

## 📌 Features

### 👩‍⚕️ Patient
- Create and manage profiles  
- Book, view, and cancel appointments  
- Track health history, medications, and test results  

### 👨‍⚕️ Doctor
- View patient medical records (history, prescriptions, scans)  
- Prescribe medications and recommend tests  
- Manage appointments and follow-ups  

### 💊 Pharmacy
- Access and process prescriptions directly  
- Maintain stock and dispense medicines  

### 🔬 Laboratory
- Receive test orders electronically  
- Upload and share results with doctors & patients  

### 🤖 AI Chatbot
- Handles routine queries (appointments, prescriptions, test updates)  
- Provides patient onboarding assistance  
- Offers first-aid guidance  

---

## 🛠️ Tech Stack
- **Frontend**: HTML, CSS, JavaScript  
- **Backend**: Python (Flask Framework)  
- **Databases**:  
  - MySQL → structured data (patients, doctors, appointments, prescriptions)  
  - MongoDB → unstructured data (medical images like X-rays, MRI scans)  
- **Libraries/Tools**: Pandas, NumPy, LLM APIs (for chatbot)  
- **Security**: MFA, bcrypt-based password hashing  
