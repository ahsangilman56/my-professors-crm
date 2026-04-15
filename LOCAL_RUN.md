# How to Run the App Locally

If you see a **blank screen** when opening `index.html`, it is because React applications require a local server to run. **Do not open index.html directly by double-clicking it.**

Follow these steps to run the app:

1.  **Open your terminal** (Command Prompt or PowerShell) inside the `Professor` folder.
2.  **Run the development server**:
    ```bash
    npm run dev
    ```
3.  **Open the link**: Copy the address shown in the terminal (usually `http://localhost:5173`) and paste it into your browser.

## Why is it blank if I click index.html?
1.  **Absolute Paths**: Modern web apps use absolute paths (like `/src/main.jsx`) which browsers cannot resolve from the local file system (`file://`).
2.  **Modules**: The browser security model prevents ES Modules from being loaded from the file system.
3.  **Vite**: The project is built using Vite, which handles the "translation" of React code into something the browser understands on-the-fly.

---
**Your site will be live soon at:**
`https://ahsangilman56.github.io/professor-outreach-crm-v2/`
