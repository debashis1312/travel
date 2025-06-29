# 🌍 Tourvism

Tourvism is an intelligent travel planning web application that uses **Gemini AI** to generate personalized travel packages and plans based on user preferences and purpose. It leverages cutting-edge technologies to offer a seamless and interactive travel planning experience.

---

## 🚀 Features

- 🧠 **AI-Powered Planning**: Uses Google Gemini to understand your requirements and create customized itineraries.
- 🏞️ **Purpose-Based Packages**: Tailors suggestions based on solo travel, honeymoon, family trips, adventure, or business.
- 📅 **Interactive UI**: Built using **Syncfusion** components for a responsive and engaging experience.
- 🔐 **Authentication & Backend**: Managed using **Appwrite** for secure and scalable app development.
- 🛠️ **Error Monitoring**: Integrated with **Sentry** for real-time performance monitoring and issue tracking.
- ⚡ **Modern Stack**: Built with **Next.js** and **TypeScript** for scalability and performance.

---

## 🧱 Tech Stack

- **Frontend**: Next.js, TypeScript, Syncfusion
- **AI Integration**: Google Gemini
- **Backend & Auth**: Appwrite
- **Monitoring**: Sentry

---

## 📦 Getting Started

### Prerequisites

- Node.js ≥ 18
- Appwrite self-hosted or cloud instance
- Google Gemini API Key
- Sentry DSN

### Installation

1. Clone the repository:

```bash
git clone https://github.com/your-username/tourvism.git
cd tourvism

2. Install dependencies:



npm install

3. Create a .env file:



cp .env.example .env

4. Configure your environment variables inside .env.


5. Run the development server:



npm run dev


---

🧪 Environment Variables (.env)

NEXT_PUBLIC_APPWRITE_ENDPOINT=https://cloud.appwrite.io/v1
NEXT_PUBLIC_APPWRITE_PROJECT_ID=your_project_id
NEXT_PUBLIC_GEMINI_API_KEY=your_gemini_api_key
NEXT_PUBLIC_SENTRY_DSN=your_sentry_dsn


---

📁 Folder Structure

/tourvism
├── components/         # Reusable UI components (Syncfusion)
├── pages/              # Next.js pages
├── lib/                # Helper functions and Gemini integration
├── appwrite/           # Appwrite config and services
├── public/             # Static files
├── styles/             # Global and modular styles
└── ...


---

🧠 AI Features

Context-aware travel planning using Gemini

Multilingual support (planned)

Budget estimation and smart suggestions (planned)



---

🛡️ Security & Monitoring

All API keys and sensitive info are kept out of source control.

Sentry tracks and alerts on performance issues and crashes.



---

📄 License

This project is licensed under the MIT License.
