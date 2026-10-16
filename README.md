🏙️ Explore City — Pune Edition
Less Survival Mode. More Adventure.

Your city is more than a place you pass through. It's a place to discover.

Explore City is an AI-powered urban exploration companion built around Pune, India. Discover iconic landmarks, uncover local food spots, build personalized adventures, talk to an AI assistant in English, Hindi, or Marathi, and keep track of everyday civic issues — all in one experience.

<p align="center">
<img src="public/hero.jpg" alt="Explore City — Pune Edition" width="100%" />
</p>

<p align="center">
<strong>Discover smarter. Explore deeper. Experience Pune differently.</strong>
</p>

<p align="center">
<img src="https://img.shields.io/badge/React-19-61DAFB?logo=react&logoColor=white" alt="React" />
<img src="https://img.shields.io/badge/TypeScript-Ready-3178C6?logo=typescript&logoColor=white" alt="TypeScript" />
<img src="https://img.shields.io/badge/AI-Gemini-8E75B2" alt="Gemini AI" />
<img src="https://img.shields.io/badge/Maps-Leaflet-199900?logo=leaflet&logoColor=white" alt="Leaflet" />
<img src="https://img.shields.io/badge/Weather-Open--Meteo-4A90D9" alt="Open-Meteo" />
<img src="https://img.shields.io/badge/License-MIT-yellow.svg" alt="MIT License" />
</p>

🌆 The Vision

Cities are full of extraordinary places, hidden experiences, everyday challenges, and stories that traditional maps rarely capture together.

Explore City brings urban discovery and practical city intelligence into one interface.

Whether you're planning a spontaneous café crawl, exploring Pune's heritage, looking for a weather-friendly afternoon adventure, or documenting a pothole on your daily route, the goal is simple:

Spend less time figuring out the city. Spend more time experiencing it.

⚡ What Makes Explore City Different?
Experience	What you can do
🗺️ Discover	Explore Pune's landmarks, cafés, heritage sites, parks, and places to stay on an interactive map.
🤖 Ask AI	Chat with a multilingual assistant that helps you navigate the application's exploration features.
🧭 Plan	Create personalized itineraries around your budget, available time, mobility preferences, and interests.
🎙️ Speak	Use browser-supported voice input and spoken responses in English, Hindi, and Marathi.
⚖️ Compare	Compare destinations using available ratings, costs, accessibility information, and other supported metrics.
🛡️ Report	Record local civic issues and use AI-assisted summaries and severity classifications.
✨ Explore the Experience
01 — A Living Map of Pune

Explore a curated collection of Pune destinations through a map-first interface.

Interactive mapping powered by Leaflet and OpenStreetMap.
Search destinations by name, category, tags, and available descriptions.
Discover heritage sites, iconic cafés, bakeries, restaurants, parks, and hotels.
Open location details and external directions links.
Gracefully handle unavailable map tiles and missing location information.

Featured destinations include Shaniwar Wada, Aga Khan Palace, Pataleshwar Cave Temple, Raja Dinkar Kelkar Museum, Kayani Bakery, Goodluck Cafe, and more.

02 — Your Personal AI Adventure Planner

Turn a few preferences into a structured city itinerary.

Plan outings around budgets expressed in Indian rupees.
Choose an exploration duration between 2 and 12 hours.
Customize travel preferences and accessibility needs.
Generate schedules with estimated costs and suggested stop durations.
Incorporate available weather information into recommendations.
Review an itinerary before saving it to local browser storage.

AI-generated costs, travel estimates, and recommendations are suggestions, not guaranteed real-world measurements.

03 — A City Assistant That Speaks Your Language

Interact with the Explore City assistant using text and supported browser voice features.

Supported languages

English — en-IN
Hindi — hi-IN
Marathi — mr-IN

Depending on browser capabilities, you can use speech recognition, edit a voice transcript before sending it, and listen to responses using browser speech synthesis.

The assistant can also help with supported application actions, such as navigating sections, filtering destinations, searching for places, and preparing civic report drafts.

04 — Citizen Reports & Local Watch

Give everyday urban observations a structured place in your exploration workflow.

Record issues such as potholes, waterlogging, and broken streetlights.
Attach relevant categories, descriptions, and coordinates when available.
Use Gemini-assisted summaries and severity classifications.
Review AI suggestions before accepting them.
Keep saved reports in browser-local storage.

Transparency matters: reports stored locally are not automatically submitted to municipal authorities or shared with other users. AI analysis may send submitted text to Google's Gemini service through the backend, so avoid including sensitive personal information.

05 — Weather-Aware Exploration

Use weather information to make more informed plans.

Retrieve available current conditions and forecasts through Open-Meteo.
Consider outdoor conditions when choosing activities.
Use weather context to help inform itinerary suggestions.

Weather availability and forecast coverage depend on the upstream service.

06 — Compare Before You Go

Evaluate two or three destinations side by side using the metrics supported by the application.

Available ratings and price information.
Safety-related indicators, where supported by data.
Walkability, accessibility, and cleanliness metrics, where available.
Clear handling of missing information.

Explore City distinguishes available data from estimates and AI-generated suggestions. A comparison score should never be interpreted as a guarantee of personal safety.

🧠 Under the Hood

Explore City combines a modern web interface with a server-side AI integration and lightweight, local-first storage.

┌─────────────────────────────────┐
│       React + TypeScript        │
│                                 │
│ Map · Discovery · Planner · Chat │
└────────────────┬────────────────┘
                 │
                 ▼
┌─────────────────────────────────┐
│       Express Backend           │
│                                 │
│ Validation · API Routes         │
│ Rate Limiting · Error Handling  │
└────────┬────────────────┬───────┘
         │                │
         ▼                ▼
┌────────────────┐  ┌────────────────┐
│   Gemini API   │  │   Open-Meteo    │
│                │  │                │
│ Chat & Planning│  │ Weather Data   │
└────────────────┘  └────────────────┘

Additional services:
Leaflet + OpenStreetMap · Browser Speech APIs
Versioned localStorage · External map directions


Architecture overview; confirm that the implemented routes and integrations match this diagram.

🛠️ Technology Stack
Layer	Technology
Frontend	React 19, TypeScript, Vite
Styling	Tailwind CSS
Backend	Node.js, Express, dotenv
AI	Google Gemini API, @google/genai
Maps	Leaflet, OpenStreetMap
Weather	Open-Meteo
Voice	Web Speech API, browser speech synthesis
Local persistence	Versioned browser localStorage
Testing	Project-configured test framework
🔐 Security & Privacy by Design

Security should be part of the architecture, not just a line in the README.

Server-side credentials: store GEMINI_API_KEY in the backend environment, never in frontend VITE_ variables.
Environment protection: keep .env out of version control and provide .env.example with placeholders.
Request validation: validate client inputs before processing them.
Abuse prevention: configure rate limits and appropriate request timeouts.
Minimal persistence: use browser-local storage for features designed to remain local.
Transparent AI: treat generated plans and classifications as suggestions, not verified facts.
External service awareness: disclose relevant data processing by third-party AI and weather providers.

These protections must be verified against the actual implementation and deployment configuration.

🚀 Get Started
Prerequisites
Node.js 20 or later, compatible with your project dependencies.
npm.
A Google Gemini API key from Google AI Studio.
1. Clone the repository
git clone <YOUR_GITHUB_REPOSITORY_URL>
cd <YOUR_REPOSITORY_DIRECTORY>
npm install


Replace the placeholders with your actual repository URL and directory name.

2. Configure environment variables

Create a local .env file in the project root:

GEMINI_API_KEY=your_actual_api_key
GEMINI_MODEL=your_supported_gemini_model
PORT=3001


Use a model identifier supported by the Gemini API and your installed SDK.

Never commit your actual .env file or publish your API key.

3. Start the backend
npm run server


The expected local backend address is http://localhost:3001, assuming the server uses the configured port.

4. Start the frontend

Open a second terminal:

npm run dev


Open the development URL printed by Vite, typically http://localhost:5173.

5. Run tests and build
npm test
npm run build


Run these commands to check the test suite and production build. The exact results depend on the current code and project scripts.

🔌 Backend API

The following endpoints describe the intended application interface; verify their availability and HTTP methods against the server implementation.

Endpoint	Method	Purpose
/api/health	GET	Backend health check
/api/config-status	GET	Non-secret configuration status
/api/places/search	GET	Search available destinations
/api/places/details	GET	Retrieve destination details
/api/routes/compute	POST	Compute supported route information
/api/weather/current	GET	Retrieve current weather
/api/weather/forecast	GET	Retrieve a weather forecast
/api/ai/plan	POST	Generate an itinerary
/api/ai/analyze-report	POST	Analyze a civic report
/api/ai/chat	POST	Process assistant conversations

Never expose secrets through health checks, configuration endpoints, logs, or client-facing error messages.

🧪 Quality & Verification

Before releasing a version, verify:

The frontend builds successfully.
The backend starts with the documented environment variables.
Gemini requests work without exposing the API key.
Invalid and oversized requests are rejected appropriately.
Rate limits and error handling behave as expected.
Local storage and civic report behavior match the privacy documentation.
Voice functionality degrades gracefully on unsupported browsers.
🗺️ Roadmap

Potential directions for future development:

Expand verified Pune destination coverage.
Add clearer data provenance and freshness indicators.
Improve accessibility-aware itinerary planning.
Add optional, consent-based report sharing.
Introduce automated accessibility and security checks in CI.
Publish a live demo with documented deployment architecture.

Roadmap items are ideas for future work, not promises of existing functionality.

🤝 Contributing

Contributions, bug reports, and ideas are welcome.

Fork the repository.
Create a feature branch.
Make your changes and run relevant tests.
Submit a pull request with a clear description.

Never include API keys, personal information, or other secrets in issues, commits, screenshots, or pull requests.

📄 License

This project is intended to use the MIT License. See the repository's LICENSE file for the applicable terms.

<p align="center">
<strong>Built for curious minds and people who want to experience Pune beyond the usual routes.</strong>
<br />
<em>Less Survival Mode. More Adventure.</em>
</p>

<p align="center">
Explore City · Pune, Maharashtra, India
</p>
