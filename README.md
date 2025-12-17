# 📍 Find Your Space - Team SIZZLERS

**Find Your Space** is an automated ecosystem designed to help students discover hyper-local, budget-friendly hangout spots—such as cafes, study zones, and stalls—tailored to their specific financial capacity. By bridging the gap between budget-conscious students and local vendors, the platform ensures students find the best spots without financial stress.

---

## 🚀 Key Features
* **Wallet-Centric Filtering:** Users can search for spots based on an exact budget range (e.g., ₹50 - ₹200), preventing any "price anxiety."
* **Live Crowdsourcing:** Integrated with **Google Forms**, the platform allows students and vendors to instantly "Add a Spot," which reflects in the app in real-time.
* **Hidden Gems:** The system digitizes local vendors and "hidden" campus haunts that mainstream navigation apps like Google Maps often ignore.
* **Zero-Cost for Vendors:** Small-scale vendors can increase their visibility and reach their target student audience without paying high commissions or requiring technical skills.

---

## 🛠️ Google Technologies Used
* **Google Sheets API:** Utilized as a real-time, serverless NoSQL database to store and fetch hangout data.
* **Google Forms:** Functions as a seamless front-end tool for data ingestion and community crowdsourcing.
* **Python Flask:** Powers the backend logic for processing data and applying budget filters.
* **Google Cloud Assets:** Used for managing environment variables, project documentation, and hosting simulation.

---

## 🏗️ Technical Architecture
The solution follows a scalable, three-layer architecture designed for cost-efficiency:



1.  **Input Layer:** Students and local vendors submit hangout details via **Google Forms**.
2.  **Processing Layer:** The **Python Flask backend** fetches live data from **Google Sheets** and applies the specific budget filtering logic.
3.  **Output Layer:** A mobile-optimized **Web UI (HTML/CSS/JS)** displays the instant matching results to the student user.

---

## 📄 Project Resources & Links
* **Live Database:** [Google Sheets Backend](https://docs.google.com/spreadsheets/d/1xXJznjhzh0P2Q1CLieVPDBEW3z1Az0Xbmlr5HknBqis/edit?usp=sharing)
* **Data Entry Portal:** [Google Form for Vendors](https://forms.gle/LUzyVDzudVW8QhQN7)
* ## 📄 Project Documentation
View our detailed project methodology, market research, and architecture:
👉 **[Download/View Project PDF](./find-your-space.pdf)**

* ## 📺 Project Demo
https://github.com/user-attachments/assets/7909cadf-2f02-4ed5-a00f-3ef836da6bdc
---

## 👥 Meet Team SIZZLERS
| Name | Role |
| :--- | :--- |
| **SHAIKH IRFAN** | **Lead Developer** (Backend, Logic & API Integration) |
---
*Developed for Google Developer Group On Campus: TechSprint 2025*
