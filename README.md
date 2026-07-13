# Hospital Roster Management System (RMS)

This is a professional, responsive web-based Hospital Roster Management Application inspired by PaperShift.

## Features

- **User Roles & Authentication:**
  - **Admin:** Can manage departments, employees, and the roster.
  - **Guest:** View-only access to the roster.
  - **Default Credentials:** Username: `admin`, Password: `password123`.
- **Departments Management:** CRUD operations for hospital departments.
- **Employee Management:** Manage staff details and assign them to departments.
- **Roster Management:**
  - Weekly view with specific dates.
  - Three standard shifts: Morning, Evening, and Night.
  - Manual assignment and "Auto-Generate" feature.
- **Tech Stack:**
  - HTML5, Tailwind CSS (Styling)
  - Alpine.js (Reactive Logic)
  - FontAwesome (Icons)
  - LocalStorage (Data Persistence)

## Setup & Running

This is a single-page application (SPA) prototype. No complex setup or installation is required.

### 1. Simple Open
Simply open the `index.html` file in any modern web browser (Chrome, Firefox, Edge, Safari).

### 2. Local Server (Recommended for best experience)
If you have Python installed, you can run a simple server from the `roster-web` directory:
```bash
python -m http.server 8000
```
Then visit `http://localhost:8000` in your browser.

## Data Persistence
The application uses the browser's `localStorage` to save your departments, employees, and roster assignments. Your data will remain even after refreshing the page or closing the browser.

## UI Inspiration
The design follows a clean, medical-professional aesthetic with a trustworthy color palette (Clinical Blues, Whites, and Soft Grays), featuring a structured grid similar to **PaperShift**.
