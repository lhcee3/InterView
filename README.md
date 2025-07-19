# InterView

Interview Buddy is a website project designed to help you prepare for job interviews by integrating AI models. The platform offers a sleek and modern experience, allowing you to practice with AI-driven mock interviews.

##  Tech Stack

* Next.js
* Firebase
* Tailwind CSS
* Vapi AI
* shadcn/ui
* Google Gemini
* Zod

##  Features

*  Authentication: Sign Up and Sign In using password/email authentication handled by Firebase.
*  Create Interviews: Easily generate job interviews with the help of Vapi voice assistants and Google Gemini.
*  Get feedback from AI: Take the interview with an AI voice agent, and receive instant feedback based on your conversation.
*  Modern UI/UX: A sleek and user-friendly interface designed for a great experience.
*  Interview Page: Conduct AI-driven interviews with real-time feedback and detailed transcripts.
*  Dashboard:  Manage and track all your interviews with easy navigation.
*  Responsiveness: Fully responsive design that works seamlessly across devices.
*  And many more, including clean code architecture and reusability.

##  Quick Start

Follow these steps to set up the project locally on your machine.

### Prerequisites

Make sure you have the following installed on your machine:

* Git
* Node.js
* npm (Node Package Manager)

### Cloning the Repository

```
git clone [https://github.com/adrianhajdin/ai_mock_interviews.git](https://github.com/adrianhajdin/ai_mock_interviews.git)
cd ai_mock_interviews
```

### Installation

Install the project dependencies using npm:

```
npm install
```

### Set Up Environment Variables

Create a new file named `.env.local` in the root of your project and add the following content:

```
NEXT_PUBLIC_VAPI_WEB_TOKEN=
NEXT_PUBLIC_VAPI_WORKFLOW_ID=
GOOGLE_GENERATIVE_AI_API_KEY=
NEXT_PUBLIC_BASE_URL=
NEXT_PUBLIC_FIREBASE_API_KEY=
NEXT_PUBLIC_FIREBASE_AUTH_DOMAIN=
NEXT_PUBLIC_FIREBASE_PROJECT_ID=
NEXT_PUBLIC_FIREBASE_STORAGE_BUCKET=
NEXT_PUBLIC_FIREBASE_MESSAGING_SENDER_ID=
NEXT_PUBLIC_FIREBASE_APP_ID=
FIREBASE_PROJECT_ID=
FIREBASE_CLIENT_EMAIL=
FIREBASE_PRIVATE_KEY=
```

Replace the placeholder values with your actual Firebase and Vapi credentials.

### Running the Project

```
npm run dev
```

Open `http://localhost:3000` in your browser to view the project.
