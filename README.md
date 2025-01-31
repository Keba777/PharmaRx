# PharmaRx - Online Pharmacy Platform

## Project Overview
The PharmaRx project is an online pharmacy platform allowing users to order medications online, with delivery or pick-up from nearby pharmacies. Features include browsing medications, uploading prescriptions, managing orders, and real-time notifications.

## Backend

The backend is built with TypeScript, Node.js, Express, and MongoDB. It is containerized using Docker for easier deployment and scalability.

### Features:
- User Authentication & Registration (JWT, email verification)
- Prescription Upload & Order Management
- Real-time Notifications
- API Routes for managing medications and users

### Running the Backend with Docker

#### Prerequisites:
- Docker and Docker Compose installed

#### Steps to run the backend:

1. Clone the repository:
   ```
   git clone https://github.com/Keba777/PharmaRx
2. Navigate to the backend folder:
```
cd backend
```
3. Build the Docker containers:
```
npm run docker:build
```
4. Start the Docker containers:
```
npm run docker:up
```
To stop the containers:
```
npm run docker:down
```
To view logs:
```
npm run docker:logs
```
## Mobile (Flutter)

The mobile application is built with Flutter for cross-platform compatibility (iOS & Android). It communicates with the backend API for user authentication, medication browsing, and order management.

### Features:
- User Authentication
- Medication Browsing
- Order Placement
- Prescription Upload (with image scanning functionality)
- Running the Mobile App
  
1. Clone the repository:
```
git clone https://github.com/Keba777/PharmaRx
```
2. Navigate to the mobile folder:
```
cd mobile
```
3. Run the Flutter app:
```
flutter run
