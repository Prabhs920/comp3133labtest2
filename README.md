# 🚀 SpaceX Mission Tracker

*Author:* Prabhnoor Singh
*Student ID:* 101415063

*Live Demo:* [https://comp3133-labtest2-dusky.vercel.app](https://comp3133-labtest2-dusky.vercel.app)

---

## 🧾 Project Overview

This Angular application fetches and displays SpaceX mission data using the public SpaceX REST API. It is built as part of *COMP3133 – Lab Test 2*.

Users can:
- View a list of all missions
- Filter by launch year, launch success, and landing success
- Click a mission to view full details

---

## 🖼️ Screenshots

### ✅ Home Page + Filter
![image]!![Screenshot 2025-04-02 165520](https://github.com/user-attachments/assets/0a75cb17-d549-4d7a-94cc-e4ffdabdea22)




### ✅ Filtered Mission List
![image]![Screenshot 2025-04-02 165317](https://github.com/user-attachments/assets/fc709a90-45d1-4b2e-ab0a-83a2f2ffbe35)


### ✅ Mission Details
![image]![Screenshot 2025-04-02 165456](https://github.com/user-attachments/assets/d13d9bf9-d28c-4fd4-9e8c-abd255df7efb)

![image]![Screenshot 2025-04-02 165334](https://github.com/user-attachments/assets/4417c456-f7bd-44e5-81d3-153577291e6f)


---

## 🛠️ Tech Stack

- Angular (Standalone Components)
- Angular Material
- SpaceX REST API v3
- Vercel (Hosting)
- GitHub (Version control)

---

## 📦 How to Run Locally

1. Clone the repository:

git clone https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
cd YOUR_REPO_NAME


2. Install dependencies:

npm install


3. Run the app:

ng serve


Then open http://localhost:4200/ in your browser.---

## 📂 Project Structure Highlights


/src
  /app
    /missionlist         → Lists all missions
    /missionfilter       → Filters for year, launch, landing
    /missiondetails      → Individual mission details
    /network             → API service for SpaceX data
    /models              → Mission data interface


---

## ✅ Features

- Angular standalone app setup
- Angular Material cards and spinners
- SpaceX REST API integration
- Filter functionality:
  - By launch year
  - Launch success (radio)
  - Landing success (radio)
- Clickable mission cards → routed mission detail view
- Responsive design
- Deployed via Vercel

---

## 📬 Submission Info

- ✅ GitHub Repo: https://github.com/samramantej/comp3133-labtest2
- ✅ Deployed App: [https://comp3133-labtest2-dusky.vercel.app](https://comp3133-labtest2-dusky.vercel.app)
- ✅ Screenshots: included in this README

---
