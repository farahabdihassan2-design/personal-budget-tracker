# Personal Budget Tracker - Visual Identity Upgrade

A responsive personal budget tracking web application designed to help users log, manage, and organize financial records in a clean, modern interface. This version focuses on enhancing the user experience through a modern visual design system built with custom CSS properties, global typography, interactive form elements, and structured box-model card layouts.

---

## Project Structure

* **index.html**: Contains the semantic HTML structure for the application header, the expense entry form, and the expense ledger table.
* **style.css**: Defines the modular design system, CSS custom variables, typography hierarchy, form and table interactions, and responsive card layouts.
* **README.md**: Provides documentation of the application architecture, design choices, and technical features.

---

## Design and Rubric Features Implemented

### 1. Intentional Color Palette (:root Variables)
The styling relies exclusively on custom CSS variables defined at the root level to ensure color consistency and ease of maintenance:
* --primary-color (#2c3e50): Deep navy applied to section headings and table headers.
* --accent-color (#2e7d32): Forest green used for action buttons to promote high visual clarity.
* --accent-hover (#1b5e20): Darker green shade triggered on button hover states.
* --bg-color (#f4f6f8): Soft light gray canvas background.
* --card-bg (#ffffff): Pure white background for distinct content cards.
* --text-color (#333333): Dark gray for readable body typography.
* --border-color (#e0e0e0): Subtle border dividers.
* --alt-row-bg (#f8f9fa): Light gray for alternating table rows.

### 2. Custom Typography and Global Inheritance
* Integrated Google Fonts: Poppins for bold, clean headings and Inter for legibility across body text, form inputs, and table cells.
* Enforced global font-family: inherit across all form elements (input, select, button) to guarantee uniform typography throughout the layout.

### 3. Table and Form Styling
* Form Styling: Full-width inputs and category dropdowns with consistent padding, rounded corners, and clear focused outlines.
* Button Component: Styled submit button with full-width layout, hover transition effects, and pointer cursor feedback.
* Expense Table: Dark header row with white text, clear cell padding (12px), alternating row shading for improved row tracking, and dynamic row hover effects.

### 4. CSS Box Model and Card Layout
Utilized CSS Box Model principles (margin, padding, border, border-radius) to organize content into three visually separated cards:
* Page Heading Card: Centered branding header container.
* Add Expense Form Card: Form section grouped inside a padded white card container.
* Recent Expenses Table Card: Table wrapper styled with equal card padding and border radius.

---

## How to Run Locally

1. Clone or download this repository.
2. Open the project folder in Visual Studio Code.
3. Launch the project using the Live Server extension to view it live in your browser at `http://127.0.0.1:5500`.