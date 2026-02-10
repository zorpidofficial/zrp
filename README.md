# zrp

### Key Features:
* **Redirect Logic**: The script automatically checks `window.location.pathname` on load. If it matches the `/d/` pattern, it immediately queries Google Sheets and redirects the user.
* **No-Backend Hosting**: Since Google Sheets acts as your database and API, you can host the frontend for free on Vercel without needing a dedicated server.
* **6-Digit Random Codes**: Uses a custom generator to create short, unique identifiers.
