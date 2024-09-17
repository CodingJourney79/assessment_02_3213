# assessment_02_3213
Add your content here ....

# NIT3213 Final Assignment Android Application

This is the final assignment project for NIT3213. The Android application demonstrates API integration, user interface design, and best practices for Android development.

## Project Overview

The app consists of three main screens:
1. **Login Screen**: Allows users to log in by entering their username (first name) and password (student ID).
2. **Dashboard Screen**: Displays a list of entities retrieved from the API.
3. **Details Screen**: Shows detailed information about a selected entity.

The app interacts with the following API: `https://vu-nit3213-api.onrender.com`.

## Requirements

- Android Studio 4.1 or later
- Kotlin 1.4 or later
- Internet connection to fetch data from the API

## Features

- **Login Screen**: The app allows users to log in using their first name and student ID (format: `s12345678`).
- **Dashboard Screen**: Displays a list of entities fetched from the API.
- **Details Screen**: Provides detailed information about a selected entity.
- **Dependency Injection**: Implemented using Hilt.
- **API Integration**: Implemented using Retrofit for network requests.

## Installation

To build and run the application, follow these steps:

### Step 1: Clone the Repository

Clone the repository or download the project zip file.

```bash
git clone https://github.com/your-repository-url.git


Step 2: Open the Project in Android Studio
Open Android Studio.
Click on "Open an existing Android Studio project."
Navigate to the project directory and select it.
Step 3: Build the Project
Ensure you have an active internet connection.
Sync the Gradle project by clicking on "Sync Now" at the top of the screen when prompted.
Wait for Gradle to build the project.

Step 4: Set Up an Emulator or Connect a Device
You can run the project using an Android Emulator or a physical Android device.
Ensure that the device or emulator is running API level 21 (Lollipop) or higher.

Step 5: Run the Project
Click the green "Run" button in the Android Studio toolbar.
Select your target device or emulator.
The app should now compile and run.
API Usage
Login Endpoint: The app makes a POST request to authenticate the user based on their location (/footscray/auth, /sydney/auth, /ort/auth).
Dashboard Endpoint: A GET request is made to /dashboard/{keypass} to fetch the list of entities.
API Base URL: https://vu-nit3213-api.onrender.com

