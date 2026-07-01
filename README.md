# 🧠 BrandBrain - SOP Content Manager

[![Live Demo](https://img.shields.io/badge/Live-brand--brain--one.vercel.app-success?style=for-the-badge&logo=vercel)](https://brand-brain-one.vercel.app)

**AI-Powered Brand Voice Analysis & Content Generation Platform**

BrandBrain is an intelligent content management system that analyzes brand voice, generates on-brand content, and manages Standard Operating Procedures (SOPs) with AI assistance.

## ✨ Features

### 🎨 Brand Voice Analysis
- **Tone Detection** - Automatically detect and analyze brand tone
- **Voice Consistency** - Ensure content matches your brand voice
- **Style Guidelines** - AI-generated style recommendations

### ✍️ AI Content Generation
- **Draft Generation** - Create content drafts with AI
- **Content Refinement** - Polish and improve existing content
- **Multi-format Support** - Generate various content types

### 📚 SOP Management
- **Centralized SOPs** - Manage all your SOPs in one place
- **Version Control** - Track changes and maintain history
- **Easy Access** - Quick search and retrieval

### 🤖 AI Integration
- **Groq AI** - Fast, efficient AI processing
- **Context-Aware** - Understands your brand context
- **Real-time Generation** - Instant content creation

## 🚀 Quick Start

### Prerequisites
- Node.js 18+
- Supabase account
- Groq API key

### Installation

#### Frontend
```bash
cd client
npm install
npm run dev
```

#### Backend (Supabase Functions)
```bash
cd supabase/functions
supabase functions deploy
```

### Environment Variables

**Client** (`.env.local`):
```env
VITE_SUPABASE_URL=your_supabase_url
VITE_SUPABASE_ANON_KEY=your_supabase_anon_key
```

**Supabase Functions**:
```env
GROQ_API_KEY=your_groq_api_key
```

## 🛠️ Tech Stack

### Frontend
- **React** - UI framework
- **Vite** - Build tool
- **TailwindCSS** - Styling
- **Supabase Client** - Backend integration

### Backend
- **Supabase** - Backend platform
- **Edge Functions** - Serverless functions
- **PostgreSQL** - Database
- **Groq AI** - AI content generation

### AI & Processing
- **Groq API** - Fast LLM inference
- **Tone Detection** - Natural language processing
- **Content Analysis** - Brand voice matching

## 📁 Project Structure

```
Brand Brain/
├── SOP Content Manager/
│   ├── client/           # React frontend
│   │   ├── src/
│   │   │   ├── BrandBrain.jsx
│   │   │   ├── data.js
│   │   │   └── lib/
│   │   └── package.json
│   └── supabase/         # Backend functions
│       └── functions/
│           ├── detect-tone/
│           ├── generate-draft/
│           ├── fix-draft/
│           └── generate-embeddings/
└── supabase/             # Supabase config
```

## 🎯 Key Features Explained

### 1. Tone Detection
Analyzes text to identify:
- Formality level
- Emotional tone
- Brand alignment
- Writing style

### 2. Draft Generation
Creates content based on:
- Brand voice guidelines
- Context and requirements
- Target audience
- Content type

### 3. Content Refinement
Improves existing content:
- Grammar and clarity
- Tone consistency
- Brand voice matching
- Style improvements

### 4. Instagram Integration (via Apify)
- Fetch Instagram posts
- Analyze brand presence
- Content inspiration
- Competitor analysis

## 🚀 Deployment

### Frontend (Vercel)
```bash
cd client
vercel deploy
```

### Backend (Supabase)
```bash
supabase link --project-ref your-project-ref
supabase functions deploy
```

## 📊 Database Schema

Key tables:
- `sops` - SOP documents
- `content_drafts` - AI-generated drafts
- `brand_voices` - Brand voice profiles
- `tone_analysis` - Historical tone data

## 🔒 Authentication

Uses Supabase Auth:
- Email/password authentication
- Protected routes
- Role-based access control

## 🤝 Contributing

Contributions welcome! Please:
1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Push and create a PR

## 📧 Contact

**Ravi Bhatt**
- Email: ravihbhatt05@gmail.com
- GitHub: [@Ravi-H-Bhatt](https://github.com/Ravi-H-Bhatt)

## 📄 License

MIT License

---

<p align="center">
  <b>Building intelligent content systems 🚀</b>
</p>
