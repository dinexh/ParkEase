# **ParkEase: AI-Powered Smart Parking System**

ParkEase is an intelligent parking management solution designed to tackle parking challenges in multi-floor parking lots. The platform uses ESP32 for data collection and provides real-time parking availability updates via an intuitive web application.

---

## **Features**
- 🚗 **Real-Time Parking Updates**: Get live updates on available and occupied parking spots.
- 🖥️ **Interactive Dashboard**: Visualize parking data with a user-friendly interface.
- 📊 **High Data Accuracy**: Powered by sensors and reliable backend technology.
- 🔄 **Scalable System**: Supports multi-floor and large parking lots.
- 🌱 **Eco-Friendly**: Optimized for energy efficiency.

---

## **Technology Stack**

### **Hardware**
- **ESP32**: Microcontroller for real-time data collection.
- **Ultrasonic Sensors**: Detect parking spot occupancy.
- **Cameras (Optional)**: For computer vision-based detection.

### **Backend**
- **Spring Boot**: Handles API development and server-side logic.
- **MySQL**: Database for storing parking and user data.

### **Frontend**
- **React.js**: Provides a responsive and interactive dashboard.

### **Communication Protocol**
- **MQTT Protocol**: For seamless communication between hardware and server.

---

## **Setup Instructions**

### **Prerequisites**
1. ESP32 microcontroller and ultrasonic sensors or cameras.
2. Software tools:
   - **Java**: For Spring Boot.
   - **Node.js** and **npm**: For React.js frontend.
   - **MySQL**: For data storage.

### **Steps to Deploy**
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/ParkEase.git
   cd ParkEase
