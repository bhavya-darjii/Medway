# Medway

<div align="center">

**Comprehensive Telemedicine, Doctor Booking & Healthcare Mobile Suite**

[![Private & Proprietary](https://img.shields.io/badge/Status-Private%20%26%20Proprietary-red?style=for-the-badge)](LICENSE)
[![Flutter](https://img.shields.io/badge/Flutter-Mobile_Suite-02569B?style=for-the-badge&logo=flutter&logoColor=white)](https://flutter.dev)
[![Dart](https://img.shields.io/badge/Dart-3.x-0175C2?style=for-the-badge&logo=dart&logoColor=white)](https://dart.dev)
[![Firebase](https://img.shields.io/badge/Firebase-Storage%20%26%20Core-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)](https://firebase.google.com)
[![Google Maps](https://img.shields.io/badge/Google_Maps-Healthcare_Locations-4285F4?style=for-the-badge&logo=googlemaps&logoColor=white)](https://developers.google.com/maps)

</div>

---

## Overview

**Medway** is an integrated mobile healthcare platform engineered to provide patients with an all-in-one medical companion. It connects users directly with certified healthcare professionals, provides a full pharmaceutical delivery store, offers vital biometric health telemetry tracking, and delivers preventive medical insights.

The platform unifies physician appointment booking, doctor profile evaluations, interactive medical center maps, e-pharmacy orders, vital heartbeat monitoring, and personal health record management.

---

## Features

- **Doctor Directory & Consultation Scheduling**: Search medical specialists by specialty (Cardiology, Dermatology, General Practice, Pediatrics) and schedule appointments.
- **Biometric Vitals & Heartbeat Monitoring**: Track personal health vitals with real-time pulse and heartbeat measurement utilities.
- **Integrated E-Pharmacy**: Browse medications, manage shopping carts, upload prescriptions, and confirm order checkouts.
- **Healthcare Facility Geo-Mapping**: Interactive clinic, diagnostic lab, and pharmacy locator powered by Google Maps.
- **Health Knowledgebase & Medical Articles**: Curated health education guides, wellness articles, and clinical FAQs.
- **Personal Health Records**: Digital patient health information records storing medical history, emergency contacts, and vital statistics.

---

## Tech Stack

| Layer | Technologies |
|---|---|
| Framework | Flutter SDK (Multi-project modular suite) |
| Language | Dart |
| Cloud Services | Firebase Core, Firebase Storage |
| Mapping & Location | Google Maps Flutter SDK |
| State Management | Provider |
| Target Platforms | Android & iOS |

---

## Getting Started

### Prerequisites

- Flutter SDK (version 3.5.0 or higher)
- Dart SDK (version 3.0.0 or higher)
- Android Studio / Xcode
- Google Maps API Key & Firebase project credentials

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/bhavya-darjii/Medway.git
   cd Medway
   ```

2. **Navigate to the core application module:**
   ```bash
   cd flutter_final
   flutter pub get
   ```

3. **Configure API Credentials:**
   - Add Google Maps API keys to `android/app/src/main/AndroidManifest.xml`
   - Configure Firebase credentials if cloud sync is enabled

### Running the Application

```bash
# Run the main healthcare application
flutter run
```

---

## Project Structure

```
Medway/
├── flutter_final/          # Main patient application module
│   ├── lib/
│   │   ├── Screens/        # Welcome, Onboarding, Checkout screens
│   │   ├── articles.dart   # Healthcare articles and wellness guides
│   │   ├── cart.dart       # Medication cart state management
│   │   ├── doctor_data.dart # Physician specialty models
│   │   ├── doctor_list.dart # Doctor directory and profile views
│   │   ├── faqs_page.dart  # Clinical FAQs
│   │   ├── health_info_form.dart # Patient health profile form
│   │   ├── maps.dart       # Clinic and hospital mapping view
│   │   ├── pharmacy.dart   # Integrated pharmacy catalog
│   │   └── main.dart       # Application initialization
│   └── pubspec.yaml
├── flutter_application_1/  # Biometric vital telemetry module (Heartbeat tracker)
│   ├── lib/
│   │   ├── heartbeat.dart  # Pulse and vital tracking algorithm
│   │   └── main.dart
│   └── pubspec.yaml
└── flutter_application_2/  # Secondary prototype and patient home navigation
    ├── lib/
    │   ├── home_page.dart
    │   └── main.dart
    └── pubspec.yaml
```

---

## License

**Copyright © 2026 Bhavya Darji. All Rights Reserved.**

This project and its underlying source code are **confidential, private, and proprietary**. Unauthorized copying, modification, distribution, public display, or commercial use of this software, via any medium, is strictly prohibited without explicit prior written authorization from the copyright holder.

---

## Author & Contact

**Bhavya Darji**  
- **Portfolio:** [bhavya-darji.vercel.app](https://bhavya-darji.vercel.app/)  
- **GitHub:** [@bhavya-darjii](https://github.com/bhavya-darjii)  
- **LinkedIn:** [Bhavya Darji](https://www.linkedin.com/in/bhavya-darji-181573242/)  
- **Email:** [bhavyadarji462@gmail.com](mailto:bhavyadarji462@gmail.com)

---

<p align="center">Made with ❤️ by <a href="https://bhavya-darji.vercel.app/" target="_blank" rel="noopener noreferrer"><strong>Bhavya Darji</strong></a></p>
