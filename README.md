# TranXend: Love Beyond Labels
Inclusive Dating App for the Transgender Community

TranXend is a dating platform tailored for the transgender community, focusing on inclusivity, safety, and meaningful connections. This app provides user-friendly features like profile creation, geolocation-based matching, privacy controls, and real-time chat.

---

## Core Features

- **User Profiles**: Create and manage personal profiles with customizable privacy settings.
- **Real-Time Chat**: Engage in secure and private conversations.
- **Geolocation-Based Matching**: Discover users nearby with location-based recommendations.
- **Safety Features**:
  - User verification to ensure authenticity.
  - Reporting/blocking functionality to enhance user safety.
- **Privacy Controls**: Enable users to control who can view their profiles or contact them.

### Optional Enhancements (Planned for Future Releases)

- Advanced search filters (e.g., interests, location radius).
- Media sharing (images/videos) within chat.
- Notifications for matches and messages.
- Community engagement features (forums, events).

---

## Technical Stack

- **Frontend**: React Native (for cross-platform mobile app development).
- **Backend**: Node.js with Express.js and PostgreSQL.
- **Services**:
  - **Geolocation**: Native device APIs (via React Native libraries).
  - **Notifications**: Firebase Cloud Messaging.
  - **Media Storage**: AWS S3 for scalable and secure file storage.

---

## Getting Started

### Prerequisites

- **Node.js** (>= 14.x)
- **PostgreSQL** (>= 12.x)
- **React Native CLI** (for iOS/Android development)
- **Firebase Account** (for notifications)
- **AWS Account** (for media storage)

### Setup Instructions

#### Clone the Repository
```bash
git clone https://github.com/your-username/TranXend-App.git
cd TranXend-App

Backend Setup

    Navigate to the backend directory:
    bash

cd backend

Install dependencies:
bash

npm install

Set up the PostgreSQL database:

    Create a new PostgreSQL database.
    Update the database configuration in backend/config/config.json to match your PostgreSQL setup.

Start the backend server:
bash

    npm run dev

    If you encounter issues, ensure that your PostgreSQL server is running and the credentials in the configuration file are correct.

Frontend Setup

    Navigate to the frontend directory:
    bash

cd frontend

Install dependencies:
bash

npm install

Set up Firebase for notifications:

    Follow the Firebase setup instructions to create a new project.
    Download the google-services.json file for Android and GoogleService-Info.plist file for iOS.
    Place these files in the appropriate directories (android/app for google-services.json and ios for GoogleService-Info.plist).

Start the frontend application:
bash

    npm run start

    If you encounter issues, ensure that you have the correct Firebase configurations and that your mobile device or emulator is properly set up.

Troubleshooting Tips

    Backend Issues:
        Ensure the PostgreSQL server is running.
        Check the database connection configuration in backend/config/config.json.
        Verify that all necessary environment variables are set.

    Frontend Issues:
        Ensure you have the correct versions of Node.js, React Native CLI, and other dependencies.
        Verify your Firebase setup and configurations.
        Check the emulator or device setup for compatibility issues.

Contributing

We welcome contributions to improve the TranXend platform. Please follow our contributing guidelines for submitting issues and pull requests.
License

This project is licensed under the MIT License - see the LICENSE file for details.
Code
