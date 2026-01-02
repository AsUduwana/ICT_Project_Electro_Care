# ICT_Project_Electro_Care  
**Electro Care – Electricity Billing Management System**

Electro Care is a **web-based electricity billing management system** that automates meter reading, bill generation, and complaint handling for the **Ceylon Electricity Board (CEB)**.  
It combines **OCR + deep learning**, **barcode validation**, and a **role-based web portal** to streamline monthly electricity billing for both customers and CEB staff.

> 🧑‍🎓 Originally developed as an undergraduate group project at the **Department of ICT, University of Sri Jayewardenepura (Batch 18).**

---

## 🧱 System Architecture

### 🖥️ Frontend

- **HTML**
- **CSS**
- **Bootstrap 5**
- **EJS templates**
- **JavaScript** for client-side logic

---

### 🧮 Backend

- **Node.js**
- **Express.js**
- Role-based routing for:
  - Customer
  - Administrator
  - Area Officer
  - Meter Reader

---

### 🗄️ Database

- **MySQL**

**ERD includes entities such as:**

- `Customers`  
- `AreaOffices`  
- `MeterReaders`  
- `Complaints`  
- `Bills`  
- `UnitPricing`  
- `MeterReadings`  

---

### 🌐 External Services

- **Nanonets OCR API** – meter reading detection  
- **Cloudinary** – image storage  
- **PDFKit** – PDF bill generation  


