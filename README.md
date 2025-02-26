# hospital-management-system-with-chatbot<img width="587" alt="Screenshot 2025-02-26 at 10 29 11 AM" src="https://github.com/user-attachments/assets/ef6cb0c3-e76c-4bce-948d-71e152ad3663" />


# **Hospital Management System with AI-Powered Chatbot**  

## **Project Overview**  
The **Hospital Management System with Chatbot** is an AI-powered healthcare solution designed to streamline hospital operations, improve patient engagement, and automate appointment scheduling. The chatbot assists patients in identifying symptoms, suggesting available doctors, and guiding them through the booking process.  

## **Features**  
✅ **AI Chatbot for Patient Assistance** – Provides 24/7 support, symptom-based doctor recommendations, and appointment scheduling.  
✅ **Admin Panel** – Manages doctors, patient records, prescriptions, and hospital operations.  
✅ **Doctor Module** – Allows doctors to update schedules, manage prescriptions, and view patient reports.  
✅ **Patient Module** – Enables patients to check doctor availability, book appointments, and interact with the chatbot.  
✅ **SMS Notifications** – Sends automated updates for appointments and prescriptions.  

## **System Requirements**  

### **Hardware Requirements**  
- **Processor:** Intel Pentium IV or higher  
- **RAM:** Minimum 4GB  
- **Hard Disk:** Minimum 20GB  
- **Monitor:** SVGA  

### **Software Requirements**  
- **Operating System:** Windows 7/10/11, macOS, or Linux  
- **Backend:** Python (Django Framework)  
- **Frontend:** HTML, CSS, JavaScript  
- **Database:** MySQL (WAMP/XAMPP Server)  
- **Other Dependencies:** TensorFlow, NumPy, Pandas, Matplotlib, Scikit-learn  

## **Installation & Setup**  

### **Step 1: Install Required Software**  
Ensure Python and MySQL are installed. If not, install them using:  

```sh
sudo apt install python3 python3-pip mysql-server  # For Linux  
brew install python mysql  # For macOS  
```

### **Step 2: Clone the Repository & Install Dependencies**  
```sh
git clone https://github.com/your-repo/hospital-chatbot.git  
cd hospital-chatbot  
pip install -r requirements.txt  
```

### **Step 3: Set Up the Database**  
1. Open MySQL and create a database:  
   ```sql
   CREATE DATABASE hospital_db;
   ```
2. Import the database from `DB.txt`:  
   ```sh
   mysql -u root -p hospital_db < DB.txt
   ```

### **Step 4: Run the Server**  
```sh
python manage.py makemigrations  
python manage.py migrate  
python manage.py runserver  
```
Visit **http://127.0.0.1:8000/** in your browser to access the application.  

## **Usage Instructions**  

### **Admin Login**  
- Username: `admin`  
- Password: `admin`  
- Manages doctors, patients, prescriptions, and insurance details.  

### **Doctor Panel**  
- Logs in to update patient records, schedule appointments, and provide prescriptions.  

### **Patient Panel**  
- Logs in to check doctor availability, chat with the AI chatbot, and book appointments.  

## **Future Enhancements**  
🚀 **Voice-enabled Chatbot** for hands-free patient interaction.  
📡 **Telemedicine Integration** for remote consultations.  
📊 **Predictive Analytics** for AI-driven health risk assessment.  
💬 **Multilingual Support** for global accessibility.  



