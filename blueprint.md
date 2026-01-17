# Blueprint: Lotto Number Generator

## Overview

This project is a simple, user-friendly web application for generating lottery numbers. It provides users with five sets of randomly generated numbers, and includes features like copying the numbers to the clipboard and switching between light and dark themes for better user experience.

## Design and Features

### Implemented

*   **UI/UX:**
    *   **Layout:** A clean, centered card-based layout that is easy to read and interact with.
    *   **Responsive Design:** The application is fully responsive and works well on both desktop and mobile devices.
    *   **Themeing:**
        *   **Light Mode:** A clean, bright interface.
        *   **Dark Mode:** A darker, eye-friendly interface for low-light environments.
        *   **Theme Toggle:** A button that allows users to switch between light and dark modes. The user's preference is saved in local storage.
    *   **Iconography:** Uses icons to enhance the user experience for theme toggling and copy actions.
*   **Functionality:**
    *   **Number Generation:** Generates five sets of six unique lottery numbers, sorted in ascending order.
    *   **Number Display:** Displays the generated numbers in a visually appealing format, with each number in a colored "ball" based on its range.
    *   **Copy to Clipboard:**
        *   A "Copy All" button to copy all five sets of numbers.
        *   Individual copy buttons for each set of numbers.
    *   **Toast Notifications:** Provides feedback to the user when numbers are copied to the clipboard.

### Current Plan

*   Create the initial version of the Lotto Number Generator application.

### Steps

1.  Create the main `index.html` file with the complete HTML structure, CSS, and JavaScript.
2.  Implement the theme (light/dark mode) switching functionality.
3.  Implement the lottery number generation logic.
4.  Implement the UI for displaying the numbers.
5.  Implement the "copy to clipboard" functionality.
