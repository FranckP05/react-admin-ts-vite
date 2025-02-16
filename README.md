# react-admin-ts-vite

## Project Overview
This project is a **React Admin Dashboard** developed as part of a frontend developer assessment. The goal was to create a fully functional **admin panel** using **React Admin**, with features such as **user and post management, custom theming, bulk actions, charts, and API integration** via `json-server`.

## Features Implemented

### 1. **Project Setup & API Configuration**
- Initialized the project using **Vite** with TypeScript.
- Configured **json-server** as a mock API for users and posts.
- Integrated **React Admin** and connected it to the mock API.
- Defined resources for `users` and `posts`.

### 2. **CRUD Operations on Users & Posts**
- Implemented **List, Create, Edit, and Show** views for both users and posts.
- Used **ReferenceField** to display user names in post lists.
- Formatted date fields using **DateField**.
- Added sorting and pagination to lists.

### 3. **Custom Actions & Bulk Updates**
- Added a **bulk deactivate action** for users, updating their active status.
- Used **React Admin's BulkActionButton** to enable batch processing.
- Implemented API calls with `dataProvider` to ensure changes reflect in the UI.

### 4. **UI Customization & Theming**
- Implemented a **custom theme** using **ThemeProvider**.
- Changed primary and secondary colors to match a professional UI design.
- Improved typography for better readability.
- Ensured **accessibility standards** (contrast, keyboard navigation, etc.).

### 5. **Dashboard with Charts & Statistics**
- Designed a **dashboard** featuring:
  - A **bar chart** showing the number of posts per user.
  - A **pie chart** displaying published vs. draft posts.
- Used **Recharts** for visualization.
- Fetched data dynamically from the API.
- Made charts **interactive** with tooltips and clickable segments.

## Technology Stack
- **React Admin** (Admin UI Framework)
- **React & TypeScript** (Frontend Development)
- **Vite** (Project Setup & Build Tool)
- **MUI (Material-UI)** (UI Components & Styling)
- **Recharts** (Data Visualization)
- **json-server** (Mock API for Development)

## Installation & Setup
### Prerequisites
Ensure you have the following installed:
- **Node.js (>=16.x)**
- **npm or yarn**

### Steps to Run the Project
1. **Clone the Repository**
   ```sh
   git clone <repo-url>
   cd react-admin-ts-vite
   ```
2. **Install Dependencies**
   ```sh
   npm install  # or yarn install
   ```
3. **Start the Mock API (json-server)**
   ```sh
   npm run server
   ```
4. **Run the React Admin Panel**
   ```sh
   npm run dev
   ```
5. Open [http://localhost:5173](http://localhost:5173) in your browser.


## Evaluation Criteria and How I Met Them
| Criteria                  | Implementation Details |
|---------------------------|-------------------------------------------------|
| **React Admin Expertise** | Used List, Create, Edit, Show, ReferenceField, Bulk Actions, Filters |
| **Customizations**        | Custom List UI, Themed Status Column, Dashboard, Interactive Charts |
| **Code Quality**          | TypeScript, Modular Components, State Management |
| **Problem Solving**       | Bulk Deactivation, Dynamic Data Fetching, API Integration |
| **UI/UX**                 | Custom Theme, Accessibility, Responsive Design |

## Deployment
To deploy the project:
1. **Build the project:**
   ```sh
   npm run build
   ```
2. **Deploy to GitHub Pages / Vercel / Netlify.**
---
Developed by **Franck Yoteu** as part of the internship's frontend developer entrance test.
For inquiries, contact   **franckyoteu.62@gmail.com**.


