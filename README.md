# 🎓 Educational Management System (EMS) - ServiceNow Project

## 📌 Overview
The **Educational Management System (EMS)** is a streamlined solution built on the ServiceNow platform to enhance administrative efficiency within educational institutions. It manages student and teacher data, simplifies the admission process, and provides tools for tracking academic progress.

By implementing EMS in ServiceNow, institutions benefit from a user-friendly, customizable, and automated environment that supports better decision-making and operational management.

---

## 🛠 Features

- 🔖 **Custom Tables**: 
  - `Salesforce` (for student data)
  - `Admission` (extends Salesforce)
  - `Student Progress`
- ⚙️ **Process Flow**:
  - Stages: `Joined → Rejected → Rejoined → Closed → Cancelled`
- 🧠 **Client Scripts**:
  - Auto-fill student data on selection
  - Pincode-based location updates
  - Disable fields to prevent manual entry
  - Auto-calculation of total marks
- 📋 **Dynamic Form Design**
- 🔢 **Admin Number Generation** using Number Maintenance
- 📊 **Results Tracking** for student progress
- 📧 **Email Notifications & Workflows**

---

## 🗂 Project Structure

| Folder          | Description                                      |
|-----------------|--------------------------------------------------|
| `update-set/`   | Contains exported ServiceNow update set (XML)    |
| `screenshots/`  | UI screenshots (form views, workflows, etc.)     |
| `README.md`     | This documentation file                          |

---

## 🚀 How to Set Up the Project

### 🧾 1. Request a Personal Developer Instance
- Go to: [developer.servicenow.com](https://developer.servicenow.com)
- Create an account and request a new instance

### 📥 2. Import Update Set
- Navigate to `System Update Sets → Retrieved Update Sets`
- Click **Import Update Set from XML**
- Upload: `Dileep_Educational_Organization.xml`
- Preview and **Commit** it

### 🧪 3. Explore the App
- View custom tables: Salesforce, Admission, Student Progress
- Open forms and submit sample entries
- Observe automated workflows and client scripts in action

---

## 📸 Screenshots

> _(actual images in `/screenshots` folder)



## ✅ Results

- Centralized management of student and admission data
- Automated workflows for error-free operations
- Dynamic forms enhance data entry and validation
- Seamless tracking of academic progress and admission stages

---

## 👍 Advantages

- Cloud-accessible from anywhere
- Automation improves efficiency and accuracy
- Highly customizable for different institutions
- Role-based access ensures data security

---

## ⚠️ Disadvantages

- Requires some knowledge of ServiceNow platform
- Complex customizations may take time
- Licensing may apply for enterprise deployment

---

## 🔮 Future Scope

- Integration with BI tools like Tableau or Power BI
- Teacher performance tracking and scheduling
- Mobile app support using ServiceNow Mobile Studio
- API integration with external databases

---

## 👨‍💻 Author

**Devi Dileep**  
Final Year IT Student  
ServiceNow Certified Administrator & Developer
[LinkedIn Profile](https://www.linkedin.com/in/devi-dileep-chodapuneedi) 
---

## 🏷️ Tags

`ServiceNow` `Update Set` `Educational System` `Automation` `Client Scripts` `Workflow` `Student Management`
