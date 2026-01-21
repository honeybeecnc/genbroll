<div align="center">

# 🎬 GenBroll - AI B-Roll Video Generator

**Transform text into stunning B-Roll videos with AI**

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![Next.js](https://img.shields.io/badge/Next.js-16-black)](https://nextjs.org/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5-blue)](https://www.typescriptlang.org/)
[![React](https://img.shields.io/badge/React-19-61dafb)](https://react.dev/)

[🌐 Live Demo](https://genbroll.com) • [📖 Documentation](https://genbroll.com/docs) • [💬 Discord](https://discord.gg/genbroll) • [🐛 Report Bug](https://github.com/honeybeecnc/genbroll/issues) • [✨ Request Feature](https://github.com/honeybeecnc/genbroll/issues)

</div>

---

## ✨ What is GenBroll?

**GenBroll** is an AI-powered SaaS platform that generates high-quality, commercial-ready B-Roll video footage from simple text descriptions. Perfect for content creators, marketers, and businesses who need professional video assets without the cost and time of traditional filming.

### 🎯 Core Value Proposition

> **"Describe It, Generate It."** — Turn your creative ideas into stunning B-Roll videos in seconds, not days.

### 🚀 Key Features

- 🎥 **Text-to-Video Generation** - Describe any scene, lighting, or camera movement in natural language
- 🎨 **Style Control** - Customize video duration, aspect ratio, and cinematic style
- 🌍 **Multi-language Support** - Generate videos with prompts in English or Chinese
- ⚡ **Async Processing** - Handle long video generation tasks with real-time status updates
- 💳 **Flexible Pricing** - Credit-based system with free tier to get started
- 📱 **Responsive Design** - Works seamlessly on desktop, tablet, and mobile
- 🔐 **Secure Authentication** - Built-in user management with OAuth support
- 📊 **Admin Dashboard** - Complete management system for users, tasks, and analytics

## 🎬 Use Cases

- **Content Creators** - Generate B-Roll footage for YouTube videos, vlogs, and social media
- **Marketing Teams** - Create promotional video assets without expensive production costs
- **Video Editors** - Quickly generate filler footage and transition clips
- **Small Studios** - Access professional video assets on-demand
- **E-commerce** - Generate product showcase backgrounds and lifestyle shots

## 🛠️ Tech Stack

Built with modern, production-ready technologies:

| Category | Technology |
|----------|-----------|
| **Framework** | Next.js 16, React 19 |
| **Language** | TypeScript |
| **Database** | PostgreSQL + Drizzle ORM |
| **Authentication** | Better Auth |
| **AI Integration** | Vercel AI SDK, Replicate, OpenRouter, Fal |
| **UI Components** | Radix UI, Tailwind CSS |
| **Payments** | Stripe |
| **Internationalization** | next-intl |

## 🚀 Quick Start

### Prerequisites

- Node.js 20+ 
- pnpm (recommended) or npm/yarn
- PostgreSQL database

### Installation

```bash
# Clone the repository
git clone https://github.com/honeybecnc/genbroll.git
cd genbroll

# Install dependencies
pnpm install

# Set up environment variables
cp .env.example .env.local
# Edit .env.local with your configuration

# Run database migrations
pnpm db:push

# Initialize RBAC
pnpm rbac:init

# Start development server
pnpm dev
```

Visit `http://localhost:3000` to see the app in action!

## 📸 Screenshots

> 💡 *Add screenshots of your application here*

## 🎯 How It Works

1. **Describe Your Scene** - Enter a text prompt describing the B-Roll footage you need
2. **AI Processing** - Our AI engine processes your request using state-of-the-art video generation models
3. **Get Your Video** - Download your generated B-Roll footage in seconds

### Example Prompts

```
"A calm city sunrise, cinematic camera movement"
"Busy coffee shop interior, warm lighting, shallow depth of field"
"Ocean waves crashing on rocky shore, golden hour, slow motion"
```

## 📚 Documentation

- [Getting Started Guide](#)
- [API Documentation](#)
- [Deployment Guide](#)
- [Contributing Guidelines](#)

## 🌟 Features in Detail

### AI Video Generation
- Support for multiple AI providers (Replicate, Fal, OpenRouter)
- Automatic fallback and load balancing
- Real-time task status updates
- High-quality video output

### User Management
- Secure authentication with Better Auth
- OAuth login (Google, GitHub)
- Role-based access control (RBAC)
- User profile management

### Credit System
- Flexible credit-based pricing
- Free tier with daily limits
- Subscription plans (Pro, Team)
- Transparent usage tracking

### Admin Dashboard
- User management and analytics
- Task monitoring and management
- Content management system (CMS)
- Payment and subscription management

## 🤝 Contributing

We welcome contributions! Please see our [Contributing Guide](CONTRIBUTING.md) for details.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📊 Project Status

- ✅ Core AI video generation
- ✅ User authentication & management
- ✅ Credit system & payments
- ✅ Admin dashboard
- ✅ Internationalization
- 🚧 Advanced video editing features
- 🚧 Batch generation
- 🚧 AI-powered video enhancement

## 🗺️ Roadmap

See our [Roadmap](ROADMAP.md) for planned features and improvements.

## 💡 Why GenBroll?

### Traditional B-Roll Production
- ❌ Expensive equipment and crew
- ❌ Time-consuming location scouting
- ❌ Weather and scheduling constraints
- ❌ Limited creative flexibility

### With GenBroll
- ✅ Generate videos in seconds
- ✅ No equipment or crew needed
- ✅ Unlimited creative possibilities
- ✅ Cost-effective pricing model

## 📈 SEO Keywords

This project is optimized for search engines and targets keywords like:
- AI video generator
- B-Roll generator
- Text to video AI
- Free B-Roll footage
- AI video creation tool
- Automated video generation
- Video content creation SaaS

## 🌍 Internationalization

GenBroll supports multiple languages:
- 🇺🇸 English
- 🇨🇳 中文 (Chinese)

More languages coming soon!

## 🔒 Security

- Secure authentication with Better Auth
- Encrypted data transmission
- Role-based access control
- Regular security updates

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.


## 📞 Support

- 📧 Email: support@genbroll.com
- 💬 Discord: [Join our community](https://discord.gg/genbroll)
- 🐛 Issues: [GitHub Issues](https://github.com/genbroll)


## ⭐ Star History

[![Star History Chart](https://api.star-history.com/svg?repos=yourusername/genbroll-com&type=Date)](https://star-history.com/#yourusername/genbroll-com&Date)

---

<div align="center">

**Made with ❤️ by the GenBroll team**

[Website](#) • [Documentation](#) • [Twitter](#) • [Discord](https://discord.gg/genbroll)

⭐ Star this repo if you find it helpful!

</div>
