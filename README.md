
# Offline Note Keeper 

A simple, offline-first note-taking application built using HTML, CSS, and JavaScript. This app stores notes directly in your browser's local storage, allowing you to create, edit, delete, and view notes even without an internet connection.

## Features

*   **Create Notes:** Easily add new notes with a summary and detailed content.
*   **View Notes:** Notes are displayed in a clean and organized card layout.
*   **Edit Notes:** Modify existing notes to update their summary and details.
*   **Delete Notes:** Remove notes that are no longer needed.
*   **Offline Functionality:** All notes are stored in the browser's local storage, ensuring access even when offline.
*   **Bootstrap 4 Styling:** Uses Bootstrap for a responsive and visually appealing interface.
*   **Modals:** Uses Bootstrap modals for adding, editing, and deleting notes, providing a smooth user experience.

## How to Run Locally

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/gha873/offlinenotekeeper
    cd offlinenotekeeper
    ```
   

2.  **Install `http-server` (if you don't have it globally):**
    ```bash
    npm install # This will install devDependencies listed in package.json
    ```

3.  **Start the local server:**
    ```bash
    npm start
    ```
    This will use the `http-server` to serve the `public` directory.

4.  **Open in your browser:**  Go to `http://localhost:8080` (or the port shown in your terminal after running `npm start`) in your web browser.

## Deployment to CapRover

This application is designed to be easily deployed to CapRover as a static HTML app. Follow these steps to deploy:

1.  **Push your code to a GitHub repository.**
2.  **In your CapRover dashboard, create a new app.** Choose "HTML Static App" as the app type.
3.  **Configure the app source:**  Set the "Source Code" to your GitHub repository URL and the branch you want to deploy (e.g., `main`).
4.  **Click "Deploy".** CapRover will automatically deploy your static files.

## License

This project is licensed under the [MIT License](LICENSE) - see the [LICENSE](LICENSE) file for details.

## Credits

Built with ❤️ using HTML, CSS, JavaScript, and [Bootstrap](https://getbootstrap.com/).

---

**[Ghazanfar Ali / gha873]** - (https://github.com/gha873/offlinenotekeeper)