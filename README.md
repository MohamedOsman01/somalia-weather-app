# Somalia Weather Information System (SWIS)
**Course Project for University Flutter Course**
**Lecturer:** SHARMAKE ALI KAHIE

## Project Context
A full-stack weather information system designed to provide real-time weather data and forecasts for Somali cities. The system includes a secure backend and a modern Flutter mobile application with separate dashboards for Administrators and regular Users.

## Features
### Admin Dashboard
- **User Management**: View and delete registered users.
- **City Management**: Full CRUD for Somali cities and regions.
- **Weather Management**: Full CRUD for historical and current weather data.
- **Statistics Overview**: Centralized control panel for system monitoring.

### User Dashboard
- **City Selection**: Select any registered Somali city to view weather.
- **Real-time Data**: Temperature, Condition, Humidity, Wind Speed.
- **5-Day Forecast**: Predictive weather patterns for the selected city.
- **Profile Management**: Account settings and theme customization.

## Technical Architecture
- **Frontend**: Flutter (Mobile Only)
- **Backend**: Node.js + Express.js
- **Database**: MongoDB
- **Authentication**: JWT (JSON Web Tokens)
- **State Management**: Provider

## Jira Task Breakdown (Project Management)

| Task ID | Component | Task Description | Assigned To | Status |
|---------|-----------|------------------|-------------|--------|
| SWIS-1 | Backend | Setup Node.js/Express & MongoDB Connection | Lead Dev | Done |
| SWIS-2 | Backend | Implement User Auth (JWT & Hashing) | Security Dev | Done |
| SWIS-3 | Backend | Create City & Weather REST APIs | Backend Dev | Done |
| SWIS-4 | Frontend | Design Core Theme & Blue Sky Gradients | UI/UX Designer | Done |
| SWIS-5 | Frontend | Implement Role-Based Navigation | Lead Dev | Done |
| SWIS-6 | Frontend | Admin Dashboard: User/City/Weather Management | Frontend Dev | Done |
| SWIS-7 | Frontend | User Dashboard: City Selector & Forecast | Frontend Dev | Done |
| SWIS-8 | Testing | API Verification & Manual App Walkthrough | QA Tester | Done |

## Setup Instructions
### Backend
1. `cd backend`
2. `npm install`
3. Configure `.env` (use `.env.example` as template)
4. `node server.js`

### Frontend
1. Ensure Flutter is installed.
2. `flutter pub get`
3. `flutter run`

---
*Developed for academic evaluation compliance.*
