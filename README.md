# Enterprise Management System with Real-time Notifications and WebSocket Chat

## Project Overview
The Enterprise Management System is a comprehensive application designed to facilitate efficient management of organizational tasks and resources. Built with a focus on role-based access and real-time communication, the system caters to three main roles: Gestionnaire, Manager, and Collaborateur.
## Project Structure

### ROLE_GESTIONNAIRE
- 🛡️ **Badge Management**
  - List badges with actions (accept, reject)
  - Manage badge requests via email API

- 🧑‍💼 **User Management**
  - Manage user roles and statuses
  - Manage user requests with actions (accept, reject)

- 📜 **Attestations**
  - Create, upload or generate PDF attestations
  - Manage attestation requests with actions (accept, reject)

- 💬 **Real-time Chat**
  - Chat with all collaborators and managers via WebSocket

### ROLE_MANAGER
- 🩺 **Conger Maldier List**
  - List sick leave requests with details
  - Manage leave requests with actions (accept, reject)

- 📋 **Donner Details**
  - Provide detailed information about leave duration
  - Manage questions about leave duration

- 📢 **Real-time Notifications**
  - Implement notifications using WebSockets

### ROLE_COLLABORATEUR
- 🛡️ **Demande Badge**
  - Submit badge requests
  - Manage badge requests with actions (accept, reject)

- 📅 **Total Leave Days (Solde)**
  - View remaining leave days
  - Select attestations for leave days

- 📄 **Select Attestation**
  - Select attestation types for leave days

- ❓ **Add Question**
  - Add questions related to the project

### Additional Features
- 📢 **Real-time Notifications**
  - Implement real-time notifications using WebSockets

- 💬 **WebSocket Chat**
  - Enable real-time chat functionality using WebSockets

- 📧 **API Email Integration**
  - Integrate API for email notifications

## SQL Database Setup
Include instructions and SQL scripts for setting up the database.

## Contact Information
For support and inquiries, contact [rabiezouita82@gmail.com](mailto:rabiezouita82@gmail.com).
