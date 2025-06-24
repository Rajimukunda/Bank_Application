# 🏦 Simple Banking Application using Docker

A minimalistic web-based banking application built with Flask and SQLite. This project simulates basic banking operations like account creation, balance check, deposit, and withdrawal, all via a clean web interface.

---
## 📌 Objective

To build a lightweight banking application for learning and demonstration purposes, allowing users to interact with core banking functionalities using a simple web interface and backend database.

---

## 🛠️ Tech Stacks

- **Backend**: Python, Flask
- **Frontend**: HTML (rendered using Jinja2 templates via Flask)
- **Database**: SQLite
- **Containerization**: Docker

---
## 🚀 Steps Included

1. **Database Initialization**
   - Creates an SQLite database (`bank.db`) with an `accounts` table.

2. **User Interface**
   - Basic HTML form rendered through Flask's `render_template_string`.

3. **Routes & Functionalities**
   - `/create`: Create a new bank account with an initial deposit.
   - `/balance`: Check account balance by account ID.
   - `/deposit`: Deposit an amount into an account.
   - `/withdraw`: Withdraw funds from an account.
   - `/statement`: Placeholder route for future transaction history.
4. **Running with Docker**
   - Uses a `Dockerfile` to containerize the application for consistent deployment.

---

## 🔍 Key Insights

- Demonstrates basic CRUD operations using Flask and SQLite.
- Uses a shared base HTML template to reduce code duplication.
- Input validation is kept simple to focus on functionality.
- Provides modular structure and clean UI for ease of use and extension.
- Docker integration makes it easy to run in any environment.

---









