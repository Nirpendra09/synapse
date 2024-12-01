# 🎨 Synapse - Collaborative Design Platform

## 📝 Project Description

Synapse is an innovative, web-based collaborative design platform that enables designers to create, share, and collaborate in real-time. Built with modern web technologies, Synapse aims to revolutionize digital design collaboration.

## 🚀 Features (Planned/In Development)

- 👤 User Authentication
  - Email/Password Login
  - OAuth (Google, GitHub)
- 🎨 Advanced Design Workspace
  - Infinite Canvas
  - Multiple Drawing Tools
  - Layer Management
- 🤝 Real-time Collaboration
  - Live Cursor Tracking
  - In-canvas Chat
  - Simultaneous Editing
- 📦 Design System Management
  - Component Library
  - Color Palette Creation
  - Typography Controls

## 💻 Tech Stack

- **Frontend**: Next.js 15+
- **Language**: TypeScript
- **Styling**: Tailwind CSS
- **State Management**: Zustand
- **Authentication**: NextAuth.js
- **Real-time**: Socket.io
- **Rendering**: Fabric.js

## 🔧 Prerequisites

- Node.js (v18+ recommended)
- npm or yarn
- Git

## 🏗️ Local Setup

### 1. Clone the Repository
```bash
git clone https://github.com/Nirpendra09/synapse.git
cd synapse
```

### 2. Install Dependencies
```bash
npm install
# or
yarn install
```

### 3. Environment Configuration
Create a `.env.local` file in the project root:
```
# Authentication
NEXTAUTH_SECRET=your_nextauth_secret
GOOGLE_CLIENT_ID=your_google_client_id
GOOGLE_CLIENT_SECRET=your_google_client_secret
GITHUB_CLIENT_ID=your_github_client_id
GITHUB_CLIENT_SECRET=your_github_client_secret

# Database
DATABASE_URL=your_database_connection_string
```

### 4. Run Development Server
```bash
npm run dev
# or
yarn dev
```

## 🔒 Authentication Setup

1. Configure OAuth applications:
   - Google Developer Console
   - GitHub Developer Settings
2. Add callback URLs
3. Generate client credentials

## 📦 Build for Production
```bash
npm run build
npm start
```

## 🧪 Testing
```bash
npm run test
# or
yarn test
```

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📋 Project Roadmap

- [x] Project Setup
- [x] Authentication System
- [ ] Basic Design Workspace
- [ ] Collaboration Features
- [ ] Advanced Design Tools
- [ ] Performance Optimization


## 🙏 Acknowledgements

- Next.js
- Tailwind CSS
- NextAuth.js
- Socket.io