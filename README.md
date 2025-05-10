
# 🌍 DestinAItion

DestinAItion is an AI-powered travel app designed to provide dynamic, personalized travel itineraries with live GPS navigation support. Starting with Kerala tourism as a pilot region, DestinAItion merges real-time location data, AI recommendations, and hyperlocal guidance to deliver a seamless and intelligent travel experience.

---

## ✨ Features

- 🤖 AI-generated daily travel itineraries using Gemini API
- 🗺️ Real-time Google Maps integration with location tracking
- 🧭 Day-wise dynamic itinerary updates
- 🧠 Contextual suggestions for nearby places and transport options
- 📱 Interactive collapsible panels for itinerary and details
- 🛺 Kerala-special: ferry, rickshaw, and cultural tips

---

## 📲 Screens

- 🧭 Live GPS Companion: Dynamic map with AI overlay
- 🧾 AI Itinerary Panel: Draggable bottom sheet UI with daily activities
- 📍 Context Cards: Clickable cards with sub-activities and map linking (planned)

---

## 🚀 Getting Started

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/DestinAItion.git
   cd DestinAItion
   ```

2. Install dependencies:

   ```bash
   flutter pub get
   ```

3. Setup APIs:

   - Enable and configure:
     - Google Maps API
     - Google Places API (optional for future features)
     - Gemini API from Google AI Studio

   - Add your API keys in the designated Dart files:

     ```dart
     const String geminiApiKey = "YOUR_GEMINI_API_KEY";
     ```

4. Run the app:

   ```bash
   flutter run
   ```

---

## 📦 Dependencies

| Package                 | Purpose                                      |
|--------------------------|----------------------------------------------|
| flutter/material.dart    | UI Framework                                 |
| google_maps_flutter      | Map & navigation                             |
| geolocator               | Current GPS location                         |
| http                     | API calls to Gemini                          |
| intl                     | Date formatting for itinerary fetch          |

---

## 🛠️ Tech Stack

| Layer                 | Stack                                     |
|----------------------|-------------------------------------------|
| Frontend             | Flutter (Dart)                            |
| Map & GPS            | Google Maps API, Geolocator               |
| AI Engine            | Gemini API (Generative Language by Google)|
| Backend (Optional)   | Firebase or Supabase                      |
| Analytics            | Firebase Analytics, Sentry (optional)     |

---

## 🧩 Architecture

- Draggable Scrollable Sheet over Map for AI itinerary
- Stateless Google Maps live map + dynamic state updates
- Gemini-generated bullet point data parsed into card layouts
- Auto-refreshes based on the current date

---

## 💡 Roadmap

- [x] AI Itinerary Fetch (Day-wise)
- [x] Live GPS Companion UI
- [ ] Tap to navigate to AI-recommended spots
- [ ] Real-time transit & ETA integration
- [ ] User sign-in and preferences
- [ ] Expand to international destinations

---

## 🧠 Unique Selling Points (USP)

- Personal AI travel assistant experience
- Kerala-first focus with local travel wisdom
- Day-aware itinerary refresh
- Easily scalable to global markets

---

## 🤝 Contributing

We welcome contributors! Please fork the repository and create a pull request with your changes.

---

## 📄 License

This project is licensed under the MIT License.
