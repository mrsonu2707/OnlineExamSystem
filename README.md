# Online Examination System 🎓

This is a web-based Online Examination System developed using **ASP.NET Core MVC** and **SQL Server**. It allows administrators to manage questions and students to take timed exams online. The system features secure login for both students and admins, question management, a countdown timer, and auto-scoring functionality.

## ✨ Features

- 🔐 **User Authentication** (Student/Admin)
- 📋 **Question Management** (CRUD operations for admins)
- 🕒 **Countdown Timer** for exams (Auto-submit on timeout)
- 🧠 **Exam Interface** with multiple choice questions
- 📊 **Result Calculation** and display after submission
- 🔎 **Role-based Dashboards**

## 🛠️ Technologies Used

- ASP.NET Core MVC
- SQL Server
- Entity Framework Core
- HTML/CSS/JavaScript
- Bootstrap (for UI)

## 📂 Project Structure

- `/Controllers` – Application logic
- `/Models` – Database models
- `/Views` – Razor views (UI)
- `Startup.cs` – Configuration
- `appsettings.json` – DB connection string and settings

## 📦 Setup Instructions

1. Clone the repo or download and extract the ZIP.
2. Set up the SQL Server database and update the connection string in `appsettings.json`.
3. Run the project using Visual Studio or `dotnet run`.
4. Navigate to `/Home/Login` to get started.

---

Feel free to customize this project for your educational or organizational needs.

