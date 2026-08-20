# Contacts Manager App 📇

A robust C# Windows Forms Contact Management Application built following the **3-Tier Architecture** pattern and utilizing **ADO.NET** for SQL Server database operations.

---

## 🏗️ Architecture Overview

This project strictly adheres to the 3-Tier Software Architecture to ensure separation of concerns, maintainability, and scalability:

* **Presentation Layer (`Contacts`)**: Windows Forms UI for handling user interactions, form validation, and data visualization.
* **Business Logic Layer (`ContactsBusinessLayer`)**: Handles core business rules, entity validations, and acts as the bridge between UI and Data Access.
* **Data Access Layer (`ContactsDataAccessLayer`)**: Manages direct database interactions using standard ADO.NET (`SqlConnection`, `SqlCommand`, `SqlDataReader`).

---

## ✨ Features

* **Contact Operations**: Add, Edit, Delete, and Search contacts seamlessly.
* **Country Data Integration**: Dynamically link contacts to their respective countries.
* **Clean UI**: User-friendly forms built with custom controls and resource icons.
* **Decoupled Architecture**: Fully isolated database logic for easy testing and updates.

---

## 🛠️ Tech Stack & Prerequisites

* **Language**: C# (.NET Framework)
* **UI**: Windows Forms (WinForms)
* **Database**: Microsoft SQL Server
* **Data Access**: ADO.NET
* **IDE**: Visual Studio 2022

---

## 🚀 Getting Started

1. **Clone the Repository**:
   ```bash
   git clone [https://github.com/moe-stack24x/Contacts-Manager-App.git](https://github.com/moe-stack24x/Contacts-Manager-App.git)
