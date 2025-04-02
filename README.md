# 🚀 SpaceX Mission List

## 📌 Project Overview
This project is an Angular-based web application that fetches and displays information about SpaceX missions using the SpaceX API. Users can filter missions by launch year, success status, and landing success.

## 🛠️ Tech Stack
- **Frontend:** Angular, TypeScript, Angular Material
- **Backend API:** [SpaceX API v3](https://api.spacexdata.com/v3/launches)
- **Styling:** CSS, Angular Material
- **Deployment:** Vercel

## 📷 Demo
🔗 **Live App:** [SpaceX Mission List](https://comp3133-lab-test2-spacex.vercel.app/)

## 🚀 Features
- Display a list of SpaceX missions with mission patches.
- Filter missions by launch year, success status, and landing success.
- Click on a mission to view more details.
- Responsive UI with Angular Material.

## 📦 Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/spacex-mission-list.git
   ```
2. Navigate to the project folder:
   ```sh
   cd spacex-mission-list
   ```
3. Install dependencies:
   ```sh
   npm install
   ```
4. Run the application locally:
   ```sh
   ng serve
   ```
5. Open the browser and go to:
   ```
   http://localhost:4200
   ```

## 🔗 API Usage
This project fetches SpaceX mission data from:
```
https://api.spacexdata.com/v3/launches
```
Each mission contains:
- `mission_name` (string)
- `launch_year` (string)
- `rocket.rocket_name` (string)
- `links.mission_patch_small` (URL to mission patch image)

## 🛠️ Deployment
This project is deployed on **Vercel**:
1. Install Vercel CLI:
   ```sh
   npm install -g vercel
   ```
2. Deploy the project:
   ```sh
   vercel
   ```

## ❓ Troubleshooting
### **Images Not Loading?**
- Ensure the API response contains `mission_patch_small`.
- Check console errors in DevTools (F12 → Console).
- Try using SpaceX API v5 for more updated data.

### **CORS Issues?**
- If images fail to load due to CORS restrictions, use a proxy server or download images locally.

## 👨‍💻 Author
**Prabhnoor Singh**  
[GitHub](https://github.com/Prabhs920) | [LinkedIn](#)

## 📜 License
This project is open-source and available under the MIT License.
