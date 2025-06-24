# 🧬 BioCryptor - Genetic Encryption AI Platform

![License](https://img.shields.io/badge/License-MIT-blue.svg)
![Version](https://img.shields.io/badge/version-1.0.0-brightgreen)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)

A modern, full-stack application featuring genetic encryption algorithms powered by AI. BioCryptor transforms data into DNA-like sequences using a sophisticated quaternary base system, providing next-generation cryptographic security with a biomimetic approach.

## ✨ Features

- **🧬 Genetic Encryption** - DNA-inspired encryption using quaternary base system (A, C, G, T nucleotides)
- **🔐 Advanced Security** - Multi-layer encryption with biomimetic approach
- **⚡ Real-time Processing** - Fast and efficient encryption/decryption operations
- **🎨 Modern UI/UX** - Built with Shadcn/UI and Tailwind CSS
- **🤖 AI Integration** - Advanced language model integration
- **🌍 Multi-language** - Full support for English and Turkish
- **🔄 Session Management** - Secure conversation context handling
- **📱 Responsive Design** - Optimized for all devices

## 🛠️ Tech Stack

- **Frontend**: React 18, TypeScript, Vite
- **Backend**: Express.js, TypeScript
- **Styling**: Tailwind CSS, Shadcn/UI
- **State Management**: React Query
- **Security**: Helmet, CORS, Rate Limiting
- **Logging**: Winston, Morgan
- **Build Tools**: Vite, TypeScript Compiler
- **Testing**: Vitest

## 🚀 Getting Started

### Prerequisites

- Node.js 18.0 or later
- npm 7.0 or later (for workspaces support)
- Git

### Installation

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd biocryptor
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Environment Setup**
   Create `.env` files in both frontend and backend directories:

   **Frontend (.env):**
   ```env
   VITE_API_BASE_URL=http://localhost:3001/api/v1
   VITE_API_TIMEOUT=30000
   VITE_DEV_MODE=true
   ```

   **Backend (.env):**
   ```env
   PORT=3001
   NODE_ENV=development
   API_PREFIX=/api/v1
   FRONTEND_URL=http://localhost:5173
   ```

4. **Start development servers**
   ```bash
   # Start both frontend and backend
   npm run dev

   # Or start individually
   npm run dev:frontend  # Frontend only (port 5173)
   npm run dev:backend   # Backend only (port 3001)
   ```

## 📁 Project Structure

```
packages/
├── frontend/                # React + TypeScript frontend
│   ├── src/
│   │   ├── components/     # Reusable UI components
│   │   ├── hooks/         # Custom React hooks
│   │   ├── lib/           # Utility functions
│   │   ├── pages/         # Page components
│   │   └── types/         # TypeScript types
│   └── public/            # Static assets
└── backend/               # Express.js + TypeScript backend
    ├── src/
    │   ├── controllers/   # Request handlers
    │   ├── services/      # Business logic
    │   ├── routes/        # API routes
    │   ├── middleware/    # Express middleware
    │   └── utils/         # Utility functions
    └── tests/            # Backend tests
```

## 🔌 API Integration

### Available Endpoints

#### Chat Operations
- `POST /api/v1/chat/message` - Send encrypted message
- `GET /api/v1/chat/session/:sessionId/history` - Get session history
- `POST /api/v1/chat/session` - Create new session

#### System Health
- `GET /api/v1/health` - Health check
- `GET /api/v1/health/ready` - Readiness probe

## 🧪 Encryption Algorithm

BioCryptor's genetic encryption process follows these steps:

1. **ASCII Conversion**
   - Input text → ASCII decimal values
   - Preparation for numerical processing

2. **Temporal Integration**
   - Combines system timestamps with ASCII values
   - Adds time-based complexity layer

3. **Base-4 Transformation**
   - Converts to quaternary representation
   - Ensures consistent 4-digit format

4. **Genetic Mapping**
   - Maps quaternary digits to DNA nucleotides
   - Creates biologically-inspired sequences

5. **Codon Formation**
   - Segments into 3-nucleotide codons
   - Mimics genetic triplet codes

6. **XOR Encryption**
   - Final encryption with genetic keys
   - Uses random initialization vectors

## 🐛 Debugging

1. **Development Tools**
   - React DevTools for component inspection
   - Backend logging with Winston
   - API testing with Postman/Insomnia

2. **Common Issues**
   - Verify environment variables
   - Check API connectivity
   - Validate encryption parameters
   - Monitor rate limiting

## 🔒 Security Features

- **🛡️ Helmet.js** - Security headers configuration
- **🚫 CORS** - Configured for specific origins
- **🚦 Rate Limiting** - Prevents abuse
- **✅ Input Validation** - Request validation
- **📝 Logging** - Secure error logging
- **🔐 Encryption** - Genetic algorithm security

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 📬 Contact

For questions, feedback, or support:
- Open an issue on GitHub
- Include steps to reproduce bugs
- Provide environment details

## 🌟 Acknowledgments

- Genetic algorithm research community
- Open source cryptography projects
- React and TypeScript ecosystem
- All contributors and supporters

---
Made with 💖 by the BioCryptor Team