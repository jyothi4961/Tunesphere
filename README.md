Music Discovery Web App
A modern React + TypeScript web application designed for smooth user interaction, onboarding, and music discovery.
Built with React Router, TanStack Query, and ShadCN UI components, this app ensures a fast, interactive, and elegant experience.
Features
authentication Page – Secure user login/signup flow.
Onboarding Flow – Smooth onboarding process for new users.
Discover Page – Explore trending or recommended music.
profile Page – Manage user details and preferences.
Global State Management – Powered by @tanstack/react-query.
Beautiful UI – Built with ShadCN and modern design principles.
Tooltips & Toasts – Smart UX notifications and hints.

Tech Stack
TechnologyDescriptionReact + TypeScriptFrontend framework with type safetyReact Router DOMFor routing between pagesTanStack React QueryServer state management and cachingShadCN/UIModern UI componentsTailwind CSSUtility-first CSS stylingVite or Next.js (depending on setup)Fast build and dev environment

 Project Structure
src/
├── components/
│   └── ui/
│       ├── toaster.tsx
│       ├── sonner.tsx
│       └── tooltip.tsx
├── pages/
│   ├── Index.tsx
│   ├── Auth.tsx
│   ├── Onboarding.tsx
│   ├── Discover.tsx
│   ├── Profile.tsx
│   └── NotFound.tsx
└── App.tsx


 Getting Started
1️⃣ Clone the Repository
cd music-discovery-app
2️⃣ Install Dependencies
npm install
3️⃣ Run the App
npm run dev

UI Components Used
Toaster – for toast notifications
Sonner – for enhanced toast/alert handling
TooltipProvider – for contextual hints
Future Enhancements
Integration with Spotify API
Chat or community feed
Recommendation engine for personalized discovery
Dark mode toggle



