# petpulse_ai
# PetPulse

**PetPulse** is a cloud-hosted AI-powered platform designed to help pet owners manage their pets’ health efficiently. It combines intelligent health tracking, cloud-based storage, and real-time vet connectivity to create a seamless pet care experience.

---

## 🔗 Live Project

Access the live app here: [http://65.20.87.234](http://65.20.87.234)

---

## 🛠 Technology Stack

- **Frontend:** React.js, HTML, CSS, JavaScript  
- **Backend:** Node.js, Express.js  
- **Database:** MongoDB (cloud-hosted on Vultr)  
- **Authentication:** JWT (JSON Web Tokens)  
- **API Integration:** Google Maps API  
- **Hosting:** Vultr Cloud Server  

---

## ⚙️ Features

1. **Smart Health Tracking and AI Insights**  
   - Personalized health timelines for pets  
   - Predictive monitoring for weight, medications, and check-ups  
   - Preventive alerts for early issue detection  

2. **Vet Connectivity and Cloud Records**  
   - Secure communication between owners and vets  
   - Digital prescriptions, post-visit summaries, and medical history  
   - Unified, cloud-synced health records  

3. **Emergency Assistance**  
   - Real-time identification of nearby open veterinary clinics  
   - Contact numbers, directions, and availability information  

4. **User-Friendly Interface**  
   - Intuitive, responsive design  
   - Easy access to pet profiles, reminders, and vet services  

---

## 💻 How It Works

1. Users register and log in securely via JWT-based authentication.  
2. Pet profiles are created with essential details like breed, age, and vaccination history.  
3. Data is stored in MongoDB, ensuring cloud backup and cross-device access.  
4. Smart notifications and AI-based insights guide owners in managing pet health.  
5. Google Maps API integration helps locate nearby veterinary clinics.  

---

## 🚀 Future Plans

- Integration with wearable IoT devices for real-time pet monitoring  
- AI-powered 24/7 vet assistant chatbot  
- Predictive health analytics to detect early signs of illness  

---

## 📂 Installation

1. Clone the repository:
   ```bash
   git clone <repo-url>


2.Navigate to the backend folder:

cd backend



3.Install dependencies:

npm install



4.Create a .env file in the backend folder and add:

MONGO_URI="mongodb://<user>:<password>@<host>:27017/petpulse_db"
JWT_SECRET="<your_secret_key>"
GOOGLE_MAPS_API_KEY="YOUR_API"


5.Start the backend server:

npm start



6.Access the platform in your browser at:

http://65.20.87.234







Notes:

Ensure MongoDB is running on the cloud server before starting the backend.

All user data is securely stored in the cloud and accessible from any device.

Sensitive keys and configurations are safely managed via .env files.

Contact: For any queries or support, reach out to abhivocopedia@gmail.com
].



