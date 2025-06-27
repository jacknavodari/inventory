# Advanced Inventory Management System

This is a desktop inventory management system built using **Electron**, which allows for cross-platform desktop applications using web technologies.

## How it's Made

The application is primarily built with:
*   **Electron**: For creating the desktop application shell.
*   **HTML5**: For structuring the user interface (`inventory.html`).
*   **CSS3 (Bootstrap 5 & Custom CSS)**: For styling and responsive design.
*   **JavaScript**: For all the application logic, including data management, UI interactions, and functionality.

Data is persisted locally using **`localStorage`**, making it a self-contained application without the need for a backend server or database.

## How to Start

To run this application, you will need Node.js and npm (Node Package Manager) installed on your system.

1.  **Clone the repository (if applicable) or navigate to the project directory**:
    ```bash
    cd path/to/your/inventory-app
    ```

2.  **Install dependencies**:
    ```bash
    npm install
    ```

3.  **Start the application in development mode**:
    ```bash
    npm start
    ```

4.  **To build an installer (e.g., for Windows)**:
    ```bash
    npm run dist
    ```
    This will create an executable installer in the `dist` directory.

## Functionality

This Inventory Management System provides the following key features:

*   **Dashboard**: An overview of inventory statistics, including total items, total value, and stock alerts.
*   **Inventory Management**: 
    *   Add new inventory items with details such as name, SKU, quantity, price, category, supplier, description, and location.
    *   Edit existing item details.
    *   Delete items.
    *   Search and filter inventory by various criteria.
*   **Category Management**: Add and manage product categories.
*   **Supplier Management**: Add and manage supplier information.
*   **Reporting**: Generate reports based on inventory data.
*   **Data Persistence**: All inventory, category, and supplier data is saved locally using `localStorage` and persists across application sessions.
*   **Clear All Data**: Option to clear all stored data and reset the application to its initial state.