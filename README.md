# Kanban Board Project

---

## Project Title

**Kanban Board UI Implementation**

---

## Project Description

This project implements a basic Kanban board web application, designed to help users visualize and manage their workflow. It features a **responsive layout** that adapts gracefully to both desktop and mobile screens. The board displays tasks organized into "TODO," "DOING," and "DONE" columns, providing a clear overview of progress. The current version focuses purely on the structural and visual presentation of a static Kanban board, showcasing a **desktop sidebar for navigation** and a streamlined mobile layout.

---

## Technologies Used

* **HTML5**: For structuring the content and defining the elements of the web page.

* **CSS3**: For styling the application, including layout, typography, colors, and responsive design.

    * **CSS Variables**: Used to define a theme's color palette, making it easy to manage and potentially switch themes.

    * **Flexbox**: Utilized for responsive layout of various components.

    * **CSS Grid**: Employed for arranging the Kanban columns.

* **Google Fonts**: Specifically, 'Plus Jakarta Sans', for consistent and modern typography.

---

## Features Created and Updated

### Core Features:

* **Responsive Layout**: Adapts seamlessly to different screen sizes, providing an optimal viewing experience on both desktop and mobile devices.

* **Static Kanban Columns**: Displays "TODO," "DOING," and "DONE" columns with predefined task cards.

* **Desktop Sidebar**: A persistent sidebar on larger screens for navigation and board selection.

* **Mobile-Optimized Header**: A compact header for mobile devices, displaying the Kanban logo and the current board title.

* **Themed Styling**: Uses CSS variables for a clean, light theme, making it straightforward to modify or extend the visual style.

* **Typography Management**: Consistent font styling applied across the application using Google Fonts and specific CSS rules.

 
### Updates & Enhancements:

* **Code Cleanup**: Removed redundant or unnecessary CSS properties and improved declaration grouping for better readability.

* **Comprehensive Comments**: Added detailed comments to both HTML and CSS files to explain the purpose of elements, styles, and responsive behaviors.

* **CSS Variable Organization**: Ensured consistent usage of CSS variables for colors and other properties.

* **Structural Clarity**: Minor HTML structural adjustments for better semantic meaning without altering functionality.

---

## Setup Instructions
To run this project locally, follow these simple steps:

1.  **Clone the repository (if applicable):**
    Clone it to your local machine:

    ```bash

    git clone https://github.com/KhodaniD/KHOMAI25088_PTO2502_GroupA_KhodaniMailula_JSL01

    ```

2.  **Navigate to the project directory:**
    Open your terminal or command prompt and change to the project's root directory:

    ```bash
    cd kanban-board-project/ # Replace with your actual project folder name

    ```
3.  **Open `index.html`:**

    Locate the `index.html` file in the root of the project directory.
    Open this file using your preferred web browser (e.g., Chrome, Firefox, Safari). You can usually do this by double-clicking the file.

    That's it! The Kanban board should now be displayed in your browser.
---

## Working Usage Examples

### Desktop View:

* Open `index.html` in a desktop browser.
* Observe the full-width sidebar on the left with the Kanban logo and board list.
* The main content area will display the "Launch Career" title and the "TODO," "DOING," and "DONE" columns arranged horizontally.
* Resize your browser window to simulate different desktop screen sizes; the columns will adjust their layout.

### Mobile View:

* Open `index.html` in a mobile browser or use your desktop browser's developer tools to enable device emulation (e.g., Chrome DevTools -> Toggle device toolbar).
* The desktop sidebar will disappear.
* The header will show a compact "Kanban" logo along with the "Launch Career" board title.
* The Kanban columns ("TODO," "DOING," "DONE") will stack vertically, making them easily scrollable on smaller screens.

---

## Interaction Instructions

This project currently provides a **static visual representation** of a Kanban board. As such, direct interaction with tasks (e.g., dragging, dropping, editing, deleting) is not implemented in this version.

* **Viewing Boards:** The "Launch Career" board is pre-selected and displayed. While the structure allows for multiple boards, the current implementation does not include functionality to switch between them dynamically.

This Kanban board provides a solid foundation for future development, like adding interactive features for tasks and board management!