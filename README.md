# 💼 FinancialCRM

**FinancialCRM** is a simple desktop CRM application developed for individuals or small businesses to manage invoices, banks, and expenses. It is built with C# and uses Entity Framework for database operations.

---

## 🔧 Features

- User login system  
- Category management  
- Bank information and transaction tracking  
- Invoice and expense management  
- Payment operations (list, add, delete, update)  
- Financial analytics dashboard  
- Modern interface for easy usage

---

## 🖼️ Screenshots

### 🔐 Login Screen
![ec31e23a-5e63-4811-9501-54b9bdbc596a](https://github.com/user-attachments/assets/052a1e88-6a81-4071-9c5a-7d53bd680c55)


To access the application, users must log in with a username and password. Default credentials:
- Username: `admin`
- Password: `1234`

---

### 💳 Payment Management Screen
![e8c00260-29d6-4bff-a08f-27fac9378a03](https://github.com/user-attachments/assets/4ad49dc8-d602-4eb9-8ae3-4c81aead0d15)


In this section, you can:
- Create new payment records  
- Enter amount and period information  
- List, delete, or update existing payments

---

### 📊 Dashboard Overview
![4bc2963a-d2aa-42f8-8aed-d447594ceff1](https://github.com/user-attachments/assets/361a4282-29ff-4e13-acbe-2b21287002a1)


Analyze your overall financial status through visual charts:
- Total balance  
- Total invoice amount  
- Most recent incoming transfer

---

### 🏦 Bank Management Screen
![1cfe1ffb-9fda-4025-8707-bff2acbe4483](https://github.com/user-attachments/assets/02191b0f-52a6-4915-9158-a2b87d1afb20)


View the current balance for each bank and track the last 5 transactions for better financial control.

---

### 🧩 Project Structure

The project consists of the following main files:
- `FrmBanks.cs`: Bank screen
- `FrmBilling.cs`: Payment/Invoice screen
- `FrmDashboard.cs`: Dashboard screen
- `Login.cs`: Login screen
- `Model1.edmx`: Entity Framework data model

---

## 🛠️ Technologies Used

- C#
- .NET Framework
- Windows Forms
- Entity Framework
- Microsoft SQL Server

---

## 🚀 Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/yourusername/FinancialCRM.git
