# 📒 KhaataPushtak

KhaataPushtak is a lightweight, file-based bookkeeping web application inspired by the traditional "Khaata" (ledger) system.  
It allows you to easily **create, edit, view, and delete daily transaction records** — stored locally as `.txt` files — using a clean and simple web interface.

> **Future Plans:**  
> In upcoming updates, KhaataPushtak will support **database integration** (MySQL/PostgreSQL or MongoDB) for more scalability, search features, and better data management.

---

## 🚀 Features
- **Create Daily Records** – Automatically saves files with the current date.
- **View Past Entries** – Quickly read and review previous records.
- **Edit Records** – Update content for any existing file.
- **Delete Records** – Remove old or unwanted files.
- **File-based Storage** – No database required; data stored in `/hisaab` folder as `.txt` files.
- **Responsive UI** – Styled with Tailwind CSS for a modern look.

---

## 🛠️ Tech Stack
- **Backend:** Node.js, Express.js
- **Templating Engine:** EJS
- **Styling:** Tailwind CSS
- **File Handling:** Node.js `fs` module

---

## 📂 Project Structure
```
KhaataPushtak/
│
├── app.js # Main server file
├── package.json # Project metadata & dependencies
├── /views # EJS templates for UI
├── /public # Static assets (CSS, JS, images)
├── /hisaab # Stored ledger files (.txt)
└── .gitignore # Ignored files & folders
```


---

## ⚙️ Installation & Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/<your-username>/KhaataPushtak.git
   cd KhaataPushtak
   ```
2. **Install dependencies**
   ```
   npm install
   ```

3. **Run in development mode (auto-reloads with nodemon)**
   ```
    npm run dev
   ```
4. **Run in production mode**
   ```
    npm start
   ```
5. **Open in browser**
   ```
    http://localhost:3000
   ```

## 📸 Screenshots
(Add screenshots of your app here for better presentation)

## 📝 Usage
-Navigate to /create to make a new daily record.
-Click on any record from the home page to view or edit it.
-Use the delete option to remove a record from /hisaab.

## 🗓️ Roadmap / Future Updates
-Database Support: Migrate from .txt file storage to database for better scalability and security.
-User Authentication: Add login/register system for multi-user use.
-Search & Filter: Quickly find past records.
-Export Data: Export records to CSV or PDF.


