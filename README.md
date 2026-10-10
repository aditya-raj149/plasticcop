♻️ EcoReport — Plastic Waste Reporting Platform

Report Plastic Waste. Support Cleaner Communities.

EcoReport is a web-based plastic waste reporting platform designed to help citizens report plastic waste in their surroundings and support better waste management. The platform provides a user interface for submitting reports, capturing photos, and supporting collaboration between citizens, municipal authorities, and recycling plants.

🌍 Overview

Plastic waste is a major environmental challenge. EcoReport explores how a digital platform can make waste reporting more accessible and help connect citizens with waste management stakeholders.

The application provides an interface for user authentication, profile registration, camera-based photo capture, and different account types for participating in waste management activities.

✨ Features

- ♻️ Plastic Waste Reporting: Interface designed for reporting plastic waste.
- 📸 Camera Integration: Capture photos directly from a device camera.
- 🖼️ Photo Preview: Review captured images before using them.
- 🔐 Authentication Interface: Email OTP and ID/password login options.
- 👤 User Profiles: Collect profile details such as name, phone number and city.
- 🏛️ Multiple User Roles: Citizen, Municipality Admin and Recycling Plant.
- 🔥 Firebase Integration: Firebase Authentication, Cloud Firestore and Cloud Storage libraries.
- 📱 Responsive UI: Mobile-oriented layout with interactive controls.
- 🔔 Toast Notifications: Visual feedback for success, error and information messages.
- 🎨 Modern Interface: Tailwind CSS styling and Font Awesome icons.

🛠️ Technologies Used

Technology| Purpose
HTML5| Application structure
CSS3| Custom styling, animations and camera overlays
JavaScript| Client-side interactions
Tailwind CSS| Utility-based styling
Firebase Authentication| Authentication integration
Cloud Firestore| Database integration
Firebase Storage| Potential storage for uploaded report images
Font Awesome| Icons
Browser Media APIs| Camera access and photo capture

👥 User Roles

1. Citizen

- Register and manage a profile.
- Capture photos of plastic waste.
- Participate in local waste reporting.

2. Municipality Admin

- Intended for municipal personnel involved in waste management.
- Designed to support the handling of citizen reports.

3. Recycling Plant

- Intended for recycling organisations.
- Designed to support participation in plastic waste collection and recycling.

Role-specific permissions and workflows require appropriate implementation and backend access controls.

📸 Camera and Photo Workflow

The interface provides a camera experience designed around the following steps:

1. Open the camera.
2. Capture a photo of the reported waste.
3. Preview the captured image.
4. Retake the photo or confirm it for use.

The browser may request camera permission. Camera access generally requires HTTPS or a localhost development environment.

🔐 Authentication

The application interface includes two login methods:

- Email OTP: Enter an email address and a six-digit verification code.
- ID & Password: Sign in using an account identifier and password.

Firebase Authentication libraries are included in the project. A production deployment must configure Firebase properly and implement secure verification, session handling, error handling and any required authentication provider setup.

🚀 Getting Started

Prerequisites

- A modern web browser.
- A code editor such as Visual Studio Code.
- A Firebase project if you want to enable Firebase-backed functionality.

Installation

1. Clone the repository:
   
   git clone https://github.com/aditya-raj149/plasticcop.git

2. Navigate to the project directory:
   
   cd plasticcop

3. Open the HTML file in Visual Studio Code.

4. Run the application through a local development server. For example:
   
   python -m http.server 8000

5. Open "http://localhost:8000" in your browser.

Note: Update the repository URL and HTML filename if your project uses a different repository or file structure.

🔥 Firebase Configuration

Before enabling Firebase features:

1. Create a Firebase project.
2. Register a web application in the Firebase console.
3. Configure the Firebase SDK using your project's configuration.
4. Enable the required authentication methods.
5. Configure Cloud Firestore and Firebase Storage.
6. Set secure Firestore and Storage rules.
7. Test authentication, report submission and image upload flows.

Never place Firebase Admin credentials or service account private keys in frontend code. Protect user data and validate permissions on the backend.

🔮 Future Enhancements

- 📍 GPS-based location tagging for waste reports.
- 🗺️ Map-based display of reported plastic waste.
- 🧠 AI-based plastic waste classification from uploaded images.
- 📊 Municipal dashboard for managing and verifying reports.
- 🚛 Waste collection status tracking.
- ♻️ Recycling plant coordination and collection records.
- 🔔 Notifications when report statuses change.
- 📈 Environmental impact statistics and reporting analytics.

⚠️ Project Status

EcoReport is a web application project with a frontend interface and Firebase SDK integration.

The availability of working authentication, persistent report storage, image uploads, role-based dashboards and waste collection workflows depends on the corresponding JavaScript logic, Firebase configuration and security rules being implemented.

👨‍💻 Author

Aditya Raj
B.Tech — Artificial Intelligence and Data Science, IIIT Manipur

- GitHub: "aditya-raj149" (https://github.com/aditya-raj149)

📄 License

Choose and add an open-source license to the repository if you intend to distribute the project publicly. The MIT License is one possible option.
