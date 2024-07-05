# Enterprise Management System with Real-time Notifications and WebSocket Chat

## Project Overview
Describe the project briefly, emphasizing its role-based functionalities and real-time communication features.

## Project Structure
- **ROLE_GESTIONNAIRE**
  - **Badge Management**
    - List badges ![List](icons/list.png) with actions ![Actions](icons/actions.png) (accept, reject).
    - Implement actions via email API ![Email](icons/email.png).

  - **User Management**
    - Manage user roles and statuses ![Roles](icons/roles.png).
    - Implement actions via email API ![Email](icons/email.png).

  - **Attestations**
    - Create, upload ![Upload](icons/upload.png), or generate PDF ![PDF](icons/pdf.png) attestations.
    - Manage attestation requests with actions ![Actions](icons/actions.png).

  - **Chat with Collaborators and Managers**
    - Real-time chat functionality using WebSockets ![WebSocket](icons/websocket.png).

- **ROLE_MANAGER**
  - **Conger Maldier List**
    - List sick leave requests ![List](icons/list.png) with details.
    - Manage leave requests with actions ![Actions](icons/actions.png).

  - **Donner Details**
    - Provide detailed information about leave duration ![Details](icons/details.png).
    - Manage questions about leave duration ![Questions](icons/questions.png).

- **ROLE_COLLABORATEUR**
  - **Demande Badge**
    - Submit badge requests ![Request](icons/request.png).
    - Manage badge requests with actions ![Actions](icons/actions.png).

  - **Total Leave Days (Solde)**
    - View remaining leave days ![Calendar](icons/calendar.png).
    - Select attestations for leave days ![Select](icons/select.png).

## Additional Features
- **Real-time Notifications**
  - Implement notifications using WebSockets ![WebSocket](icons/websocket.png).

- **WebSocket Chat**
  - Enable real-time chat functionality ![Chat](icons/chat.png).

- **API Email Integration**
  - Integrate API for email notifications ![Email](icons/email.png).

## SQL Database Setup
Include instructions and SQL scripts for setting up the database.

## Contact Information
For support and inquiries, contact [email@example.com](mailto:email@example.com).
