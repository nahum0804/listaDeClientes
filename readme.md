# Client List - CRUD with IndexedDB

This project is an old development I created in **2022** for a course I took at that time. It is a web application that implements a client management system using **IndexedDB**, the browser's local database. It allows performing **CRUD** operations (Create, Read, Update, and Delete) efficiently without requiring a server connection.

## 📌 Main Features
- Uses **IndexedDB** for data storage in the browser.
- Simple interface to add, edit, and delete clients.
- Data persistence even after closing the browser.
- Transaction implementation to ensure data integrity.
- Form validation and alert messages to improve user experience.

## 🚀 Technologies Used
- **HTML** and **CSS** for the user interface.
- **JavaScript** for application logic.
- **IndexedDB** for data storage.
- **Netlify** for project deployment.

## 📂 Code Structure
The project consists of several JavaScript files handling different functionalities:

1. **IndexedDB Connection**: Database setup and management with `indexedDB.open('crm',1)`.
2. **Create Clients**: Store data in `objectStore.add(client)`.
3. **Read Clients**: Retrieve the client list using `objectStore.openCursor()`.
4. **Update Clients**: Modify a record with `objectStore.put(updatedClient)`.
5. **Delete Clients**: Remove a record with `objectStore.delete(idToDelete)`.
6. **Alert Handling and Validations**: Notify errors or successful actions.

## 📌 Features
- **Add Client**: Fill out the form and store the information in IndexedDB.
- **List Clients**: Display all clients saved in the database.
- **Edit Client**: Modify existing client details.
- **Delete Client**: Remove a client from the database after user confirmation.

## 🌐 Live Project
You can see the project in action at the following link:
🔗 [Client List](https://listadeclientes.netlify.app/)


