# 📇 Contacts Manager App

A  **C# Windows Forms Contact Management Application** built following the **3-Tier Architecture** pattern and utilizing **ADO.NET** for SQL Server database operations.

---

## 🏗️ Architecture Overview

This project follows the **3-Tier Software Architecture** to ensure separation of concerns, maintainability, and scalability.

### 🖥️ Presentation Layer
**`Contacts`**

Windows Forms UI responsible for:

- User interactions
- Form validation
- Data visualization
- Managing application forms

### 🧠 Business Logic Layer
**`ContactsBusinessLayer`**

Responsible for:

- Business rules
- Entity validation
- Processing application logic
- Connecting the Presentation Layer with the Data Access Layer

### 🗄️ Data Access Layer
**`ContactsDataAccessLayer`**

Responsible for database operations using ADO.NET:

- `SqlConnection`
- `SqlCommand`
- `SqlDataReader`

---

## ✨ Features

- ➕ Add contacts
- ✏️ Edit contacts
- 🗑️ Delete contacts
- 🔍 Search contacts
- 🌍 Link contacts with country data
- 🖥️ User-friendly Windows Forms interface
- 🧩 Custom controls and resource icons
- 🏗️ Clean 3-Tier Architecture
- 🗄️ SQL Server database integration
- 🔌 ADO.NET data access

---

## 📸 Screenshots

### Main Screen

![Contacts Manager Main Screen](ScreenShots/Screenshot%202026-08-20%20122438.png)

### Add/Edit Screen

![Contacts Manager Contact Screen](ScreenShots/Screenshot%202026-08-20%20122448.png)

---

## 🛠️ Tech Stack

| Technology | Usage |
|------------|-------|
| **C#** | Application development |
| **.NET Framework** | Application framework |
| **Windows Forms** | Graphical User Interface |
| **ADO.NET** | Database access |
| **Microsoft SQL Server** | Database |
| **Visual Studio 2022** | Development Environment |
| **3-Tier Architecture** | Application architecture |

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/moe-stack24x/Contacts-Manager-App.git
