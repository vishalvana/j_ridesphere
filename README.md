# RideSphere – Smart Carpooling Application

RideSphere is a modern Carpooling and Ride Sharing Android application built using Java and XML.  
The application helps users search rides, host rides, manage vehicle details, and connect commuters through a clean and interactive user interface.

The project integrates Firebase Authentication, Cloud Firestore, and Google Maps API to provide secure authentication, cloud database support, and real-time location-based ride services.

---

# Features

- User Authentication System
- Login & Registration
- Search Available Rides
- Host a Ride
- Vehicle Information Management
- Ride Listing System
- Google Maps Integration
- Cloud Firestore Database
- Modern Dark UI
- Responsive Android Layouts

---

# Tech Stack

| Technology | Usage |
|------------|-------|
| Java | Main Programming Language |
| XML | UI Design |
| Firebase Authentication | User Authentication |
| Cloud Firestore | Cloud Database |
| Google Maps API | Maps & Location Services |
| Android Studio | Development IDE |

---

# Modules

## Authentication Module
- Secure Login System
- User Registration
- Firebase Authentication Integration

## Ride Search Module
- Search rides using source and destination
- Vehicle type selection

## Host Ride Module
- Add vehicle details
- Add available seats
- Host rides for commuters

## Vehicle Management
- Store vehicle information
- Manage seat availability

## Maps Module
- Google Maps Integration
- Location-based ride support

---

# Screenshots

<img src="https://github.com/vishalvana/j_ridesphere/assets/127835696/490d6ea8-c56d-4567-ad00-ea9a6e02eda4" width="220" height="450" />

<img src="https://github.com/vishalvana/j_ridesphere/assets/127835696/9e36201c-de03-4f7c-bebf-2d362cac83d7" width="220" height="450" />

<img src="https://github.com/vishalvana/j_ridesphere/assets/127835696/01ba671c-4340-488a-a8d3-bed4cd55fb87" width="220" height="450" />

<img src="https://github.com/vishalvana/j_ridesphere/assets/127835696/78d35aeb-d5f2-480d-aee7-0ec413ebeb1f" width="220" height="450" />

<img src="https://github.com/vishalvana/j_ridesphere/assets/127835696/ce727aa4-ce46-4262-b3fc-00b23874ab02" width="220" height="450" />

<img src="https://github.com/vishalvana/j_ridesphere/assets/127835696/8c4bb981-8f87-4a5a-bc9d-3b2e90412332" width="220" height="450" />

<img src="https://github.com/vishalvana/j_ridesphere/assets/127835696/064fde13-4ab2-4d18-a439-e1fdedd78aaf" width="220" height="450" />

<img src="https://github.com/vishalvana/j_ridesphere/assets/127835696/e7a98ebe-7f6c-45b7-85f0-d8a76f5e2523" width="220" height="450" />

---


```

---

# Installation

1. Clone the repository

```bash
git clone https://github.com/vishalvana/j_ridesphere.git
```

2. Open the project in Android Studio

3. Connect Firebase to the project

4. Add Google Maps API Key

5. Sync Gradle

6. Run the application on Emulator or Physical Device

---

# Firebase Setup

1. Create a Firebase Project
2. Enable Firebase Authentication
3. Enable Cloud Firestore Database
4. Download `google-services.json`
5. Place the file inside:

```text
app/google-services.json
```

---

# Google Maps Setup

1. Open Google Cloud Console
2. Enable Maps SDK for Android
3. Generate API Key
4. Add the API key inside `AndroidManifest.xml`

```xml
<meta-data
    android:name="com.google.android.geo.API_KEY"
    android:value="YOUR_API_KEY"/>
```

---

# Learning Outcomes

This project helped in learning:

- Firebase Authentication
- Cloud Firestore Database
- Google Maps API Integration
- Java-based Android Development
- XML UI Design
- Form Validation
- Android Activity Lifecycle
- Ride Sharing System Logic

---

# Future Improvements

- Real-Time Ride Tracking
- In-App Chat System
- Push Notifications
- Payment Gateway Integration
- Ride History
- Ratings & Reviews
- Route Optimization

---

# Contribution

Contributions are welcome!

Steps to contribute:
1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Push the branch
5. Open a Pull Request

---

# Developer

Vishal Vana

- Android Developer
- Java & Firebase Enthusiast
- Android UI Developer

---

# Support

If you liked this project, consider giving it a star on GitHub.
