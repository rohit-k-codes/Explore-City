🏙️ Explore City — Pune Edition
Less Survival Mode. More Pune.

Your city. Your culture. Your next adventure.

Pune isn't just a destination. It's Peshwa-era heritage, legendary misal pav, conversations over chai, peaceful tekdis, buzzing college streets, hidden cafés, and neighborhoods with stories of their own.

Explore City is an AI-powered urban discovery and exploration platform built around Pune, Maharashtra. It brings local discoveries, personalized itineraries, multilingual AI assistance, weather-aware planning, and civic issue reporting into one experience.

Discover Pune beyond the usual routes. Plan smarter outings. Experience the city on your own terms.

<p align="center">
<img src="public/hero.jpg" alt="Explore City — Pune Edition" width="100%" />
</p>

<p align="center">
<strong>Discover Pune. Plan Your Adventure. Experience More.</strong>
</p>

<p align="center">
<img src="https://img.shields.io/badge/React-19-61DAFB?logo=react&logoColor=white" alt="React" />
<img src="https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white" alt="TypeScript" />
<img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?logo=tailwindcss&logoColor=white" alt="Tailwind CSS" />
<img src="https://img.shields.io/badge/AI-Google_Gemini-8E75B2" alt="Google Gemini" />
<img src="https://img.shields.io/badge/Maps-Leaflet-199900?logo=leaflet&logoColor=white" alt="Leaflet" />
<img src="https://img.shields.io/badge/Weather-Open--Meteo-4A90D9" alt="Open-Meteo" />
<img src="https://img.shields.io/badge/License-MIT-yellow.svg" alt="MIT License" />
</p>

🌆 The Vision: A Better Way to Experience Pune

Pune is a city of contrasts: centuries-old Maratha heritage alongside modern technology hubs, iconic eateries alongside independent cafés, lively commercial districts alongside quiet green spaces.

Yet discovering the right places, planning an outing around your budget, and making informed decisions about where to go can involve switching between multiple applications.

Explore City brings these experiences together in one Pune-focused platform.

Whether you're a student looking for a café near your college, a resident planning a weekend outing, a visitor exploring historic landmarks, or someone documenting a pothole on their daily route, Explore City helps you interact with the city in a more informed and personalized way.

Built around Pune. Designed for everyday exploration.
🏛️ Discover Pune's heritage and cultural landmarks.
🍜 Explore local food, cafés, bakeries, and neighborhood favorites.
🗺️ Find destinations through an interactive city map.
🤖 Generate personalized adventures with Gemini AI.
🎙️ Interact through multilingual text and browser-supported voice features.
🌦️ Consider weather conditions when planning outdoor activities.
🛡️ Record local civic issues and organize observations.
✨ Features
1. 🗺️ Pune City Explorer

Explore a curated collection of destinations across Pune through an interactive map-based interface.

What you can do

Browse categorized destinations on a Leaflet map.
Search places by name, category, tags, and available descriptions.
Filter destinations by supported categories.
View location details and available destination information.
Open external map links for navigation.
Handle missing coordinates and unavailable map tiles gracefully.

Featured Pune destinations

Shaniwar Wada
Aga Khan Palace
Pataleshwar Cave Temple
Raja Dinkar Kelkar Museum
Osho Teerth Park
Goodluck Cafe
Vaishali
Vohuman Cafe
Bedekar Misal
Kayani Bakery
The Ritz-Carlton, Pune
Conrad Pune

The curated collection is intended to help users discover a mix of heritage, food, culture, green spaces, and hospitality.

2. 🍜 Discover Pune's Food & Neighborhood Culture

Explore the different experiences that make Pune distinctive.

Discover destinations and experiences associated with areas such as:

Deccan and FC Road: Cafés, student hangouts, shopping, and local food.
Koregaon Park: Cafés, restaurants, gardens, and lifestyle destinations.
Camp: Historic streets, bakeries, and established local eateries.
Kothrud: Residential neighborhoods and everyday food discoveries.
Baner: Modern cafés, restaurants, and growing urban districts.

These neighborhoods provide a useful framework for future destination expansion. Actual results depend on the places included in the application's data.

3. 🤖 Multilingual Explore City AI Assistant

Get help exploring Pune through an AI-powered conversational interface.

Supported languages

English — en-IN
Hindi — hi-IN
Marathi — mr-IN

Assistant capabilities

Answer questions about supported destinations and application features.
Help users discover places and plan outings.
Support natural-language search and category filtering.
Assist with itinerary planning.
Prepare civic report drafts through supported application actions.
Offer voice input and spoken responses where browser capabilities permit.

Voice interaction

Browser speech recognition for voice input.
Editable transcripts before submission.
Browser-native speech synthesis for spoken responses.
Speak, stop, and mute controls.
No automatic voice playback by default.

Voice functionality varies by browser, operating system, language support, and permissions.

4. 🧭 AI-Powered Pune Adventure Planner

Turn your available time and preferences into a structured outing.

Personalization options

Budget in Indian rupees.
Exploration duration from 2 to 12 hours.
Travel preferences.
Accessibility requirements.
Interests and destination preferences supported by the application.

Planning features

Structured itineraries with suggested stops.
Estimated durations and costs.
Local destination recommendations.
Weather-aware suggestions when weather information is available.
Practical planning and navigation tips.
Review and confirmation before saving an itinerary.

The planner uses Google Gemini through the application's AI integration.

Generated itineraries, travel durations, and prices are estimates. They should be checked against current local conditions before travel.

5. 🌦️ Weather-Aware Exploration

Pune's weather can influence outdoor plans, particularly during the monsoon and hotter months.

Explore City uses Open-Meteo for supported weather information.

Retrieve current weather conditions where available.
Retrieve supported forecast information.
Incorporate weather context into planning.
Help users consider outdoor and indoor alternatives.

Weather data availability depends on the upstream service. Suggestions are not a substitute for official weather warnings.

6. ⚖️ Destination Comparison

Compare supported destinations side by side before choosing where to go.

Depending on available data, comparisons may include:

Ratings.
Price information.
Accessibility and walkability indicators.
Cleanliness indicators.
Safety-related information.

Missing information should be displayed transparently instead of being presented as a verified measurement.

AI-generated estimates and community observations must not be treated as official safety certifications.

7. 🛡️ Citizen Reports & Local Watch

Document everyday urban issues that affect the experience of navigating Pune.

Supported reporting workflows may include:

Potholes and damaged roads.
Waterlogging.
Broken streetlights.
Other supported local civic observations.

Users can record descriptions, categories, and coordinates when available. Gemini can assist with summarization and severity classification.

Reports stored in browser localStorage remain local to that browser unless a separate sharing or submission mechanism is implemented.

Important: Local reports are not automatically delivered to Pune Municipal Corporation or other authorities. AI classifications may be inaccurate and should be reviewed before use.

🧠 System Architecture

Explore City combines a React frontend, an Express backend, a Gemini integration, external weather data, interactive mapping, and local browser persistence.

                    EXPLORE CITY
                   PUNE EDITION
                         |
                         v
              React + TypeScript
                         |
          +--------------+--------------+
          |              |              |
          v              v              v
       Discovery       AI Planner      Assistant
       & Mapping       & Itineraries   & Voice
          |              |              |
          +--------------+--------------+
                         |
                         v
                 Express Backend
                         |
              +----------+----------+
              |                     |
              v                     v
         Google Gemini          Open-Meteo
         AI Features            Weather Data

       Additional integrations:
       Leaflet + OpenStreetMap
       Browser Speech APIs
       Versioned browser localStorage


This is a conceptual overview. Confirm the actual request paths and service responsibilities against the current implementation.

🔐 Single Gemini API Key Architecture

The application is designed to use a server-side Gemini API key rather than exposing a secret in frontend code.

Environment variables
Variable	Purpose
GEMINI_API_KEY	Server-side Gemini API credential
GEMINI_MODEL	Gemini model identifier used by the backend
PORT	Express server port
Security principles
Keep GEMINI_API_KEY in the backend environment.
Never embed a private API key in frontend source code.
Never expose a secret through a VITE_ environment variable.
Exclude .env from version control.
Use .env.example to document required configuration without real credentials.
Validate incoming API requests.
Configure suitable request limits and timeouts.
Avoid returning secrets or sensitive server errors to clients.
Configure production CORS rules for the intended frontend origins.

These are required security practices, not a guarantee that every control is already implemented.

Mapping and weather
Mapping: Leaflet and OpenStreetMap provide the mapping experience without requiring a Google Maps JavaScript API key.
Weather: Open-Meteo provides supported weather information without requiring a conventional API key for its standard public service.

External map directions may still open Google Maps or another mapping service.

Local-first storage

The application uses browser localStorage for supported locally saved information.

This means local data is generally specific to the browser and device profile. It is not automatically synchronized across devices or shared with other users.

🛠️ Technology Stack
Component	Technology	Purpose
Frontend	React 19	Interactive user interface
Language	TypeScript	Typed application development
Build tooling	Vite	Development server and production builds
Styling	Tailwind CSS	Responsive visual design
Icons	Lucide React	Interface icons
Backend	Node.js and Express	API endpoints and server-side processing
AI integration	Google Gemini API, @google/genai	Chat, planning, and report analysis
Mapping	Leaflet	Interactive maps
Map data	OpenStreetMap	Map tiles and geographic context
Weather	Open-Meteo	Weather information
Voice	Web Speech API	Browser-supported speech recognition
Speech output	Speech synthesis API	Spoken responses
Persistence	Browser localStorage	Local saved information
Configuration	dotenv	Backend environment configuration

Verify dependency versions against package.json before publishing the README.

🚀 Quick Start & Setup
Prerequisites
Node.js 20 or a compatible supported version.
npm.
A Gemini API key from Google AI Studio.
1. Clone the repository

Replace the placeholders with your actual GitHub repository URL and directory name.

git clone <YOUR_GITHUB_REPOSITORY_URL>
cd <YOUR_REPOSITORY_DIRECTORY>
npm install

2. Configure environment variables

Create a .env file in the project root.

GEMINI_API_KEY=your_actual_gemini_api_key
GEMINI_MODEL=your_supported_gemini_model
PORT=3001


Replace the model placeholder with a Gemini model identifier supported by your API and SDK.

Keep this file local. Do not commit it to GitHub.

The committed .env.example should contain the same variable names with blank or placeholder values.

3. Start the backend

In your first terminal, run:

npm run server


The backend is expected to run at:

http://localhost:3001

This assumes the server script and port configuration match the project setup.

4. Start the frontend

Open a second terminal and run:

npm run dev


Open the local URL printed by Vite, typically:

http://localhost:5173

5. Run tests
npm test

6. Build the application
npm run build


Run these commands to check the test suite and production build. The result depends on the current implementation and available environment configuration.

🔌 Backend API Reference

The following table documents the intended application API. Confirm the endpoint paths and HTTP methods against the Express server before treating this as a complete API contract.

Endpoint	Method	Purpose
/api/health	GET	Backend health check
/api/config-status	GET	Non-secret configuration status
/api/places/search	GET	Search supported destinations
/api/places/details	GET	Retrieve destination details
/api/routes/compute	POST	Compute supported route information
/api/weather/current	GET	Retrieve current weather
/api/weather/forecast	GET	Retrieve forecast information
/api/ai/plan	POST	Generate a personalized itinerary
/api/ai/analyze-report	POST	Analyze a civic report
/api/ai/chat	POST	Process assistant conversations
API security
Validate request parameters and payloads.
Reject invalid or oversized requests.
Rate-limit AI-powered endpoints.
Apply request timeouts.
Return appropriate HTTP status codes.
Keep API credentials and internal error details out of client responses.
🧪 Testing & Quality Assurance

Before publishing a release, verify the following:

The frontend builds successfully.
The backend starts with the documented environment variables.
The Gemini API integration works using the server-side key.
AI requests fail gracefully when the API is unavailable.
Invalid requests are rejected appropriately.
Rate limits and timeouts behave as expected.
Map interactions and destination searches work.
Weather failures do not break the entire application.
Local storage behaves as documented.
Voice features degrade gracefully in unsupported browsers.
No secrets appear in the frontend bundle or Git history.

Only publish specific test counts after confirming them against the actual test suite.

🔒 Privacy & Responsible AI

Explore City is intended to help people discover places and organize local observations without overstating what its data can prove.

Data transparency
Locally saved reports are not automatically shared with other users.
Browser-local data is not automatically submitted to municipal authorities.
Gemini requests may transmit submitted content to Google's service for processing.
AI-generated recommendations may be inaccurate or outdated.
Safety-related scores or classifications are not guarantees of personal safety.
Weather and destination information should be checked against reliable current sources when important.

Avoid entering sensitive personal information into AI prompts or civic reports.

🗺️ Pune-Focused Roadmap

Potential future improvements include:

Expand curated destination coverage across Pune.
Add richer neighborhood-specific discovery.
Improve data source attribution and freshness indicators.
Add more accessibility-aware itinerary options.
Improve Marathi localization and conversational quality.
Add optional civic report sharing with explicit consent.
Introduce automated build and security checks.
Publish a hosted demo with documented deployment requirements.

Roadmap items describe potential future work and should not be interpreted as existing features.

🤝 Contributing

Contributions and suggestions are welcome.

Fork the repository.
Create a feature branch.
Make your changes.
Run the relevant tests and build.
Submit a pull request describing the change.

Please do not include API keys, private information, or other secrets in commits, screenshots, issues, or pull requests.

📄 License

This project is intended to be distributed under the MIT License.

See the repository's LICENSE file for the applicable terms.

<p align="center">
<strong>Made for the curious, the explorers, and everyone who calls Pune home.</strong>
</p>

<p align="center">
<em>Less Survival Mode. More Pune.</em>
</p>

<p align="center">
Explore City — Pune Edition · Pune, Maharashtra, India
</p>
