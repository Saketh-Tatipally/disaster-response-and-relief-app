# disaster-response-and-relief-app
Full-stack web application for disaster management — provides real-time alerts, donation campaigns, volunteer coordination, and shelter tracking with Google Maps integration.



---

## 📘 Project Overview
The **Disaster Response and Relief App** is a web-based platform that helps coordinate **real-time disaster information**, **donations**, **volunteers**, and **shelter resources** in one unified system.  

The application is designed to connect citizens, donors, and responders during emergencies — enabling faster, data-driven relief operations.

---

## 🎯 Objectives
- Deliver **real-time disaster alerts** using live Weather API data.  
- Provide modules for **donations**, **volunteer coordination**, and **shelter tracking**.  
- Enable cloud-based CRUD operations through **MongoDB Atlas**.  
- Visualize shelter data using **Google Maps API** for geolocation insights.

---

## 🧩 System Components and CRUD Operations

| Component | Assigned Member | Create | Read | Update | Delete |
|------------|----------------|--------|-------|--------|--------|
| **Disaster Alerts** | Saketh Tatipally | Generate real-time alerts (Weather API) | View alerts by location | Update alerts dynamically | Remove resolved alerts |
| **Donation Campaigns** | Navya Prakash Mamidisetti | Create donation campaigns | View campaign details | Update progress | Close completed campaigns |
| **Help Requests & Volunteers** | Pavan Sai Kumar Jalluri | Post help requests / volunteer sign-ups | View tasks | Update status | Mark tasks completed |
| **Shelter Locations** | Nikhilesh Buddi | Register new shelters | View shelters & capacity | Update availability | Remove inactive shelters |

---

## 🧭 User Flow Diagram
*(Insert image: `/docs/user_flow_diagram.png`)*

**Flow Summary:**
1. Admins manage alerts, shelters, and campaigns.  
2. Users can view alerts and request help.  
3. Volunteers respond to tasks.  
4. Donors contribute to live campaigns.  

---

## 🧱 Technology Stack

| Layer | Technologies |
|--------|---------------|
| **Frontend** | HTML, CSS, JavaScript |
| **Backend** | Node.js, Express.js |
| **Database** | MongoDB Atlas (Cloud) |
| **APIs** | Weather API, Google Maps API |
| **Version Control** | Git + GitHub |


---

## ⚙️ Component Details

### 🌀 Component 1 – Disaster Alerts
**Developer:** *Saketh Tatipally*  
- Integrates a **Weather API** to generate and update alerts in real time.  
- Stores alert data in **MongoDB Atlas**.  
- Allows users to view alerts based on their region.  


---

### 💰 Component 2 – Donation Campaigns
**Developer:** *Navya Prakash Mamidisetti*  
- Admins can create and update donation campaigns.  
- Users can view active campaigns and contribute.  
- MongoDB used to track campaign status and total donations.  


---

### 🤝 Component 3 – Help Requests & Volunteers
**Developer:** *Pavan Sai Kumar Jalluri*  
- Allows users to post help requests.  
- Volunteers can sign up for available tasks.  
- Admins update task progress and mark requests as resolved.  



---

### 🏠 Component 4 – Shelter Locations
**Developer:** *Nikhilesh Buddi*  
- Manages shelter registration, capacity, and resource availability.  
- Integrated **Google Maps API** to visualize shelter locations.  
- Users can filter shelters by country and city.  


---

## 🗺️ Google Maps API Integration
- Displays registered shelters as **red location markers** on the map.  
- Updates dynamically when admins modify shelter details.  
- Improves geographical clarity and accessibility for users.  

---

## 🧪 Database Verification
All CRUD operations were successfully tested and verified using **MongoDB Atlas (Cloud)**.  
Collections were maintained for:
- Alerts  
- Campaigns  
- Help Requests  
- Shelters  
 

---

## 🚀 How to Run the Application

### 🔹 Prerequisites
- Node.js installed  
- MongoDB Atlas cluster and connection URI  
- Weather API key and Google Maps API key  


