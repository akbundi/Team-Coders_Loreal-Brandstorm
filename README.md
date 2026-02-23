
# Personal Scent DNA™ (Pulse) - L’Oréal Luxe Innovation Lab

Welcome to the future of fragrance. Pulse is a biometric-first application that decodes your olfactory identity without a single quiz.

## 🚀 Innovation Core: Sensor Fusion DNA
Pulse leverages high-frequency sensor data to build a real-time behavioral and biometric profile:
- **Biometric Phase**: On-device MediaPipe FaceMesh extracts geometry and micro-expressions to determine personality archetypes.
- **Environmental Phase**: Real-time geolocation + weather data (humidity, temp) optimizes scent projection.
- **Behavioral Phase**: Usage patterns (Time of day, activity level) dictate base/middle note ratios.

## 🛠 Tech Stack
- **Frontend**: Next.js 14, Tailwind CSS, Framer Motion.
- **AI Engine**: Google Gemini API (Pro and Flash).
- **Computer Vision**: Google Cloud Vision API for fragrance bottle recognition.
- **Persistence**: PostgreSQL + Prisma ORM.
- **Safety**: End-to-end type safety with tRPC and Zod.

## ⚖️ GDPR Compliance
- No raw images or voice recordings are stored. 
- All biometric analysis is performed locally via MediaPipe or ephemeral AI inference.
- Users have full control over data deletion in `/profile/settings`.

## 🧪 Deployment
Built for Vercel. Ensure all environment variables in `.env.example` are configured in your Vercel project dashboard.
