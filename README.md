# 🤖 Seminar Bot — Telegram Bot for Seminar Management  

A **Telegram bot** built using the **python-telegram-bot** library to manage and interact with seminar-related information.  
The bot makes it easy for users to **stay updated on upcoming seminars**, **add new events**, and **view existing ones** — all through simple chat commands.  

---

## 🚀 **Project Overview**
This bot streamlines seminar management for both organizers and participants by offering features like **adding**, **viewing**, **updating**, and **removing** seminar details.  
It provides an interactive and user-friendly experience directly inside Telegram.

---

## 🛠️ **Features & Functionalities**

| Command / Function        | Description                                                                 |
|-------------------------|-----------------------------------------------------------------------------|
| **/start**              | Sends a **welcome message** and introduces the bot.                         |
| **/help**               | Displays a list of available commands and their usage.                     |
| **add_seminar**         | Starts the process of **adding a new seminar** by letting the user select a category. |
| **list_categories**     | Returns a **list of seminar categories** for easy selection.                |
| **choose_category**     | Handles **category selection** and prompts the user to enter seminar details. |
| **save_seminar_details**| Saves the seminar information after validation.                             |
| **display_seminars**    | Displays all available seminars in a **clean, formatted message**.          |
| **remove_seminar**      | Automatically **removes outdated seminars** based on date and time.        |
| **handle_response**     | Processes user inputs and generates appropriate responses.                 |
| **handle_message**      | Routes incoming messages to the correct function based on the user's step. |

---

## 🧩 **How It Works**
1. The user interacts with the bot using Telegram commands.
2. The bot handles different flows:
   - Starting the conversation (`/start`)
   - Adding a seminar by selecting a **category** and providing **details**
   - Displaying all current seminars
   - Removing outdated seminars automatically.
3. The code uses the **python-telegram-bot** library to manage:
   - Handlers for commands
   - Message routing  
   - State management for multi-step user interactions.

---

## 📌 **Example Workflow**

**Step 1:** User sends `/start` → Bot sends a welcome message.  
**Step 2:** User selects **“Add Seminar”** → Bot shows available categories.  
**Step 3:** User chooses a category → Bot asks for seminar details.  
**Step 4:** Bot validates and saves the details → Confirms successful addition.  
**Step 5:** At any time, the user can view all seminars or remove outdated ones.

---

## 👨‍💻 **Tech Stack**
- **Language:** Python 🐍  
- **Library:** [python-telegram-bot](https://python-telegram-bot.org/)  
- **Platform:** Telegram Messenger  
- **Data Handling:** Uses in-memory storage and filtering for expired seminars.

---

## 👥 **Team Members**
- **Osama Alharbi**  
- **Ali Alfares**  
- **Mohammed Alamri**  
- **Ashwaq Almalki**  

---

## 📬 **Future Improvements**
- 🔹 Integrate **database storage** (e.g., SQLite / PostgreSQL) for persistence.  
- 🔹 Add support for **seminar reminders** and **notifications**.  
- 🔹 Include an **admin dashboard** for managing seminars visually.  
- 🔹 Enable exporting seminar schedules in **PDF** or **CSV**.
