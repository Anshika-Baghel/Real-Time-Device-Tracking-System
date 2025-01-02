
# Real-Time Device Tracking System:

This project is live at : https://real-time-device-tracking-system.onrender.com

## Overview
This project is a **Real-Time Device Tracking System** built with **Express.js** and **OpenStreetMap API**. It allows users to track the real-time location of devices on a map interface, providing a seamless and intuitive experience.

---

## Features
- **Real-Time Tracking**: Tracks devices in real-time and updates their location dynamically on the map.
- **Interactive Map**: Integrated with OpenStreetMap for rendering device locations.
- **RESTful API**: Backend powered by Express.js to manage devices and their locations.

---

## Technologies Used
### Backend
- **Express.js**: For building the RESTful API

### APIs
- **OpenStreetMap API**: For map data and visualization.

---

## Installation and Setup
### Prerequisites
- **Node.js** installed on your system.
- **npm** (Node Package Manager).

### Steps
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/real-time-device-tracking.git
   cd real-time-device-tracking
   ```

2. **Install Dependencies**:
   ```bash
   npm install
   ```

3. **Set Environment Variables**:
   Create a `.env` file in the root directory and add the following:
   ```env
   PORT=3000
   OPENSTREETMAP_API_KEY=your-api-key
   ```

4. **Run the Application**:
   ```bash
   npm start
   ```
   The application will be accessible at `http://localhost:3000`.

---

## Usage
1. Open the application in your browser.
2. Add devices via the provided interface or API endpoints.
3. View the real-time location of the devices on the map.

---

## API Endpoints
### Base URL
`http://localhost:3000`

### Endpoints
| Method | Endpoint        | Description               |
|--------|-----------------|---------------------------|
| GET    | `/devices`      | Fetch all devices         |
| POST   | `/devices`      | Add a new device          |
| PUT    | `/devices/:id`  | Update device location    |
| DELETE | `/devices/:id`  | Remove a device           |

---

## Screenshots

---

## Future Enhancements
- **Authentication and Authorization** for secure access.
- **Geofencing** to trigger alerts when devices leave a defined area.
- **Database Integration** for persistent storage.
- **Historical Tracking** to view past movements of devices.

---

## Contributing
1. Fork the repository.
2. Create a new branch for your feature (`git checkout -b feature-name`).
3. Commit your changes (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature-name`).
5. Create a pull request.





