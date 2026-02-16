AlerSense is an AI-powered Android mobile application developed as my Final Year Project. The purpose of this application is to help individuals with food allergies make safer food choices by analyzing product ingredients and detecting potential allergen risks in real time.

This project combines mobile application development, artificial intelligence concepts, barcode scanning, and personalized user profiling to create a smart and practical health-support system.

🎯 Problem Statement

Food allergies can be life-threatening. Many individuals struggle to quickly determine whether a food product contains ingredients that may trigger allergic reactions. Ingredient lists are often difficult to interpret, and product packaging may not always clearly highlight allergen risks.

AlerSense addresses this issue by allowing users to:

Create a personalized allergy profile

Scan product barcodes

Analyze ingredients

Receive instant allergen risk warnings

The goal is to improve safety, awareness, and convenience for individuals managing food allergies.

🚀 Key Features
1️⃣ User Authentication

Secure login and registration system

User-specific allergy profile management

2️⃣ Personalized Allergy Profile

Users can select allergens (e.g., peanuts, dairy, gluten, etc.)

Define severity levels

Customize dietary preferences

System uses this profile to generate personalized warnings

3️⃣ Barcode Scanning

Scan food product barcodes using the device camera

Retrieve product information

Analyze ingredient list

Detect potential allergen matches

4️⃣ AI-Based Food Analysis

Uses AI/ML processing pipeline for:

Ingredient normalization

Feature extraction

Classification

Risk scoring

Generates intelligent warnings based on risk thresholds

5️⃣ Allergen Risk Alerts

Clear, user-friendly notifications

Risk levels categorized (Safe / Warning / High Risk)

Designed to support quick decision-making

🏗 System Architecture

The project follows a multi-layer architecture:

📱 Mobile Application Layer

Built using Android Studio

Handles user interface, barcode scanning, and API communication

🌐 Backend / Service Layer

Manages authentication

Stores user profiles

Retrieves product data

🤖 AI Processing Layer

Processes ingredient data

Applies classification logic

Calculates allergen risk score

Returns analysis results to the mobile app

This separation ensures modularity, scalability, and easier maintenance.

🛠 Technologies Used

Android Studio

Java / Kotlin (depending on your implementation)

Gradle build system

Barcode scanning library

REST API integration

AI/ML logic implementation

Git & GitHub for version control
▶ How to Access and Run the Project
Download app-debug.apk from this repository.

1-Transfer it to an Android device.

2-Enable Install from Unknown Sources in device settings.

3-Install the APK.

4-Open AlerSense and explore the features.
