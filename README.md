# NaloxNow – Combating the Opioid Crisis with Real-Time Naloxone Access and AI-Powered Response

<img src="./images/NaloxNow.png" alt="NaloxNow Logo" width="200"/>

NaloxNow is a life-saving mobile application designed to address Canada’s opioid crisis by providing real-time access to naloxone kits, emergency navigation, and AI-powered overdose response guidance. The app empowers individuals and communities to take immediate action during overdose emergencies, reducing harm and saving lives.

## Features

### 1. Real-Time Naloxone Kit Mapping
*   Locate the nearest naloxone kits using an interactive map powered by Google Maps.
*   **Community-driven updates:** Users can upload photos and locations of naloxone kits to keep the database accurate and up-to-date.
*   **Life-saving potential:** By sharing the location of a naloxone kit, users can help someone in need access life-saving resources during an overdose emergency.

### 2. Emergency Navigation
*   Quickly find and navigate to the nearest naloxone kit using step-by-step directions.
*   Seamless integration with Google Maps for real-time navigation.

### 3. AI-Powered Overdose Response
*   Real-time, step-by-step instructions on how to administer naloxone and perform basic first aid during an overdose.
*   AI chatbot provides immediate guidance, ensuring users know exactly what to do while waiting for emergency services.

### 4. Emergency Alert System
*   **"Need Help Now" Button:** Users can trigger an emergency alert with a single tap. The app automatically:
    *   Retrieves the user’s live GPS location.
    *   Sends an alert to pre-saved emergency contacts via SMS and email, including a live location link.
    *   Automatically calls 911 and shares the user’s location with emergency responders.
*   **On-Screen Guidance:** The app displays overdose response instructions, ensuring users or bystanders can take immediate action.

### 5. Community-Driven Impact
*   NaloxNow relies on community participation to keep its database accurate and up-to-date.
*   By uploading photos and locations of naloxone kits, users contribute to a life-saving network that can help anyone in need.

## Why NaloxNow?

The opioid crisis is one of Canada’s most pressing public health challenges, with thousands of lives lost each year due to overdoses. NaloxNow addresses this crisis by:

*   Providing rapid access to naloxone kits, the life-saving medication that can reverse opioid overdoses.
*   Offering real-time guidance and support during emergencies, reducing response times and improving outcomes.
*   Empowering communities to take action and save lives through a simple, user-friendly platform.

## How It Works

**Find a Naloxone Kit:**

*   Users can search for the nearest naloxone kit using the app’s interactive map.

**Upload a Kit:**

*   If a user finds a naloxone kit, they can take a photo and upload its location to the app, ensuring the database remains current.

**Emergency Response:**

*   In an overdose emergency, users can trigger the "Need Help Now" button to:
    *   Alert emergency contacts.
    *   Call 911.
    *   Receive on-screen instructions for administering naloxone and first aid.

## Get Involved

NaloxNow is more than just an app—it’s a movement. By downloading the app, uploading naloxone kit locations, and spreading awareness, you can help save lives and make a tangible difference in your community.

## Technical Details

### Tech Stack

*   **Frontend:** React Native (iOS and Android)
*   **Backend:** Google Cloud Functions, Firebase
*   **Mapping:** Google Maps API
*   **AI Chatbot:** OpenAI GPT or similar AI model
*   **Emergency Workflow:** Google Workflows, Twilio (for SMS/email alerts)

### Setup Instructions

1.  Clone the repository:

    ```
    git clone https://github.com/SathvikHaridasu/NaloxoneNow
    ```

2.  Install dependencies:

    ```
    cd NaloxNow
    npm install
    ```

3.  Set up environment variables:

    *   Create a `.env` file in the root directory.
    *   Add the required API keys and credentials (e.g., Google Maps API key, Twilio credentials).

4.  Run the app:

    ```
    npm start
    ```

## Contributing

We welcome contributions from the community! If you’d like to contribute to NaloxNow, please follow these steps:

1.  Fork the repository.
2.  Create a new branch for your feature or bug fix.
3.  Submit a pull request with a detailed description of your changes.
