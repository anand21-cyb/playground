# AI Multi-Modal Playground

This is a Next.js app featuring AI-powered tools including:

- Conversation Analysis (audio transcription)
- Image Analysis (image description)
- Document/URL Summarization

The app uses OpenAI API for AI tasks and Clerk for user authentication.

---

## Features

- Sign up / Sign in with Clerk
- Upload audio for transcription
- Upload images for AI description
- Upload PDF/DOC files or enter URLs for content summarization
- Responsive UI with simple styling

---

## Setup Instructions

### Prerequisites

- Node.js (v18+ recommended)
- npm or yarn
- OpenAI API key (You need to create one at https://platform.openai.com/)
- Clerk account and API keys for authentication (https://clerk.com/)

### Installation

1. Clone the repo:

```bash

npm install
# or
yarn install

OPENAI_API_KEY=your_openai_api_key_here
NEXT_PUBLIC_CLERK_FRONTEND_API=your_clerk_frontend_api
CLERK_API_KEY=your_clerk_api_key
CLERK_JWT_KEY=your_clerk_jwt_key


npm run dev
# or
yarn dev

git clone https://github.com/your-username/your-repo.git
cd your-repo
