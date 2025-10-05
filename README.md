# AI SQL Query Generator 🤖

A natural language to SQL query converter built with Next.js and AI capabilities.

## 🚀 Live Demo
(https://vercel.com/umme-kalsooms-projects/sql-ai-query-generator)

## ✨ Features

- **🤖 AI-Powered Queries** - Convert natural language to SQL automatically
- **🔍 Smart Search & Filters** - Find data by name, email, city with real-time filtering
- **💬 Interactive Chat Interface** - Talk to your database like a conversation
- **📊 Live Data Display** - Beautiful table visualization with Tailwind CSS
- **📱 Fully Responsive** - Works perfectly on desktop and mobile

## 🛠️ Tech Stack

- **Frontend:** Next.js 14, React, Tailwind CSS
- **AI Integration:** Groq Cloud, CopilotKit
- **Database:** REST API Integration
- **Deployment:** Vercel
- **Styling:** ShadCN Components

## 🏃‍♂️ Quick Start

### Prerequisites
- Node.js 18+ 
- npm or yarn

### Installation

1. **Clone the repository**
```bash
git clone https://github.com/UmmeKalsoom584/SQL-AI-Query-Generator.git
cd SQL-AI-Query-Generator
Install dependencies

bash
npm install
Set up environment variables

bash
# Create .env file and add:
NEXT_PUBLIC_COPILOTKIT_BACKEND_URL=/api/copilotkit
NEXT_PUBLIC_GROQ_CLOUD_API_KEY=your_groq_api_key
NEXT_PUBLIC_RESTDB_API_KEY=your_restdb_api_key
NEXT_PUBLIC_RESTDB_BASE_URL=your_restdb_url
Run development server

bash
npm run dev
Open http://localhost:3000 in your browser

🎯 Usage Examples
Try asking:

"Show me all users from New York"

"What is John Doe's email?"

"Find users with Gmail addresses"

"How many users are in the database?"

📁 Project Structure
text
sql-ai-chatbot/
├── app/                 # Next.js app router
│   ├── api/            # Backend API routes
│   ├── layout.js       # Root layout
│   └── page.js         # Home page
├── components/         # React components
│   └── ui/            # UI components
├── public/            # Static assets
└── package.json       # Dependencies
