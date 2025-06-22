#  Shipment Management Web Form using JsonPowerDB

---

##  Table of Contents

- [Title of the Project](#-title-of-the-project)
- [Description](#-description)
- [Benefits of using JsonPowerDB](#-benefits-of-using-jsonpowerdb)
- [Scope of Functionalities](#-scope-of-functionalities)
- [Examples of Use](#-examples-of-use)
- [Project Status](#-project-status)
- [Release History](#-release-history)
- [Illustrations](#-illustrations)
- [Sources](#-sources)
- [Other Information](#-other-information)

---

##  Title of the Project

**Shipment Management Form using HTML, JavaScript, and JsonPowerDB**

---

##  Description

This project is a responsive and interactive shipment data entry form built using **HTML**, **Bootstrap**, and **JavaScript**, connected to **JsonPowerDB**. It allows the user to insert and update shipment records based on a primary key (`Shipment-No`), making it ideal for small logistics or delivery-related applications.

The form communicates with JPDB using the `PUT` (Replace) and `GET_BY_KEY` APIs to save or update records dynamically without reloading the page.

---

##  Benefits of using JsonPowerDB

-  **Fast and Lightweight**: Extremely quick for single-page applications
-  **Easy to Use**: No SQL queries needed, only JSON and JavaScript
-  **Secure**: Token-based authentication
-  **REST API Powered**: Simple integration into any frontend
-  **Schema-less**: Add new fields without modifying the database schema
-  **Supports CRUD Operations**: Create, Read, Update, Delete easily via API

---

##  Scope of Functionalities

- Uses `Shipment-No` as a **Primary Key**
- Automatically **checks if record exists**
- Enables Save if new, or Update if existing
- All inputs are **validated** before submission
- One-click **Reset** button
- Built with only **client-side technologies**

---

##  Examples of Use

- Logistics companies managing shipments
- Educational projects on API & frontend integration
- Mini projects for college web development courses
- Simple admin dashboard for internal tracking

---

##  Project Status

 Completed  
 Submitted as a **college mini/micro project**  
 Includes test token — replace with your own for production use

---

##  Release History

- **v1.0 – June 22, 2025**  
   First working version using Replace API (PUT)  
   Save, Update, and Reset features  
   JPDB token support and data validation  

---

## 🖼 Illustrations

![Screenshot of the shipment form](screenshot.png)  
*(Add your screenshot with the name `screenshot.png` in the repo)*

---

##  Sources
- [JsonPowerDB Official Site](https://login2explore.com/jpdb)
- [JPDB Docs (API Guide)](https://login2explore.com/jpdb/docs.html)
- Bootstrap 4 CDN  
- jQuery CDN

---

##  Other Information

- This project was developed by **[Your Name]**, 1st Year Engineering Student
- Guided by: [Teacher/College Name] (if required)
- Works completely offline after token setup
- Easy to extend with more fields or features like delete, filter, etc.

---

##  License

This project is licensed under the MIT License — feel free to use or extend.
