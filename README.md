# find-your-space
A Google-powered web MVP helping students find budget-friendly hangout spots using Flask, Pandas, and Google Sheets. 🚀

---

## 👥 Meet Team SIZZLERS
**Event:** TechSprint - Leveraging The Power of AI

| Name | Role | Responsibility |
| :--- | :--- | :--- |
| **SHAIKH IRFAN** | **Lead Architect & Developer** | Conceptualized the idea, designed the Google Ecosystem integration, and built the full Flask-Python backend. |
| **KHAN SHOAIB** | **Communications Lead** | Crafting the project presentation (PPT) and defining the visual brand for the TechSprint pitch. |
| **KHAN ZIDAN** | **Market Analyst** | Verified project feasibility, validated student budget data, and conducted market research. |
| **SHOAIB RAZA** | **QA & Support** | Handled system testing, bug reporting, and maintained backups for a stable build. |

---

## 📌 Problem Statement
College students often struggle to find affordable hangout places that fit their budget. At the same time, local cafes, restaurants, and entertainment spots lack a simple platform to showcase budget-friendly offers to students.

## 💡 Solution
**Find Your Space** is a simple web-based MVP that helps students discover nearby hangout spots based on their budget and preferred category.

* **Local shopkeepers** can submit their offers through a Google Form, which automatically updates a Google Sheet used as the project database.
* **Students** enter their budget and hangout type, and the system instantly shows matching places.

---

## 👥 Target Users
* **College students**
* **Local businesses:** Cafes, restaurants, movie places, and gaming zones

---

## ⚙️ Features
* **Budget-based filtering** of hangout spots.
* **Category selection** (Cafe, Restaurant, Movie, Playstation).
* **Real-time data updates** using Google Sheets.
* **Separate flow** for data entry (Google Form) and data viewing (Web App).

---

## 🛠️ Tech Stack
* **Frontend:** HTML, CSS
* **Backend:** Python (Flask)
* **Data Handling:** Pandas
* **Database:** Google Sheets
* **Google Tools Used:** Google Forms, Google Sheets
---

## 🔗 Project Links & Resources
To showcase the seamless integration of Google Workspace, here are the live components of the project:

* **Data Entry Portal:** [Google Form](https://forms.gle/LUzyVDzudVW8QhQN7) — *Used by shopkeepers to submit new offers.*
* **Live Database:** [Google Sheets](https://docs.google.com/spreadsheets/d/1xXJznjhzh0P2Q1CLieVPDBEW3z1Az0Xbmlr5HknBqis/edit?usp=sharing) — *Where all hangout data is stored and managed.*
* **CSV API Endpoint:** [Live CSV Link](https://docs.google.com/spreadsheets/d/1xXJznjhzh0P2Q1CLieVPDBEW3z1Az0Xbmlr5HknBqis/export?format=csv) — *The real-time data bridge used by the Flask backend.*

---

## 🔄 How It Works
1. **Submit:** Shopkeepers submit hangout details through a Google Form.
2. **Store:** Data is stored automatically in a Google Sheet.
3. **Search:** Students enter their budget and preferred category on the website.
4. **Process:** Flask backend reads the Google Sheet as CSV using Pandas.
5. **Display:** Matching hangout spots are displayed to the user.

---

## 📁 Project Structure
```text
find-your-space/
├── app.py              # Flask backend and filtering logic
├── requirements.txt    # Python dependencies
├── templates/
│   └── index.html      # Frontend UI
└── README.md           # Project documentation


https://github.com/user-attachments/assets/7909cadf-2f02-4ed5-a00f-3ef836da6bdc
