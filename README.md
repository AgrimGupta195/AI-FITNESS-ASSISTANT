# FitnessAI 🏋️‍♂️

FitnessAI transforms personal training through AI-powered voice conversations, creating custom workout and diet plans tailored to your goals. This modern platform makes fitness guidance accessible and personalized for everyone.

## ✨ Features

- 🎯 **Personalized Fitness Plans** - AI-generated workout routines based on your goals
- 🗣️ **Voice Interaction** - Natural conversations with AI fitness coach
- 🍎 **Custom Diet Plans** - Nutrition guidance tailored to your needs
- 👥 **Community Gallery** - Browse other users' fitness programs
- 🔐 **User Authentication** - Secure login and profile management
- ⚡ **Real-time Interaction** - Live voice feedback and program generation

## 🛠️ Tech Stack

- **Frontend:** Next.js, TypeScript, TailwindCSS
- **Authentication:** Clerk
- **Voice Integration:** VAPI
- **Styling:** Tailwind CSS with custom UI components
- **State Management:** React Hooks
- **Deployment:** Vercel (recommended)

## 🚀 Getting Started

1. **Clone the repository**
```bash
git https://github.com/AgrimGupta195/AI-FITNESS-ASSISTANT.git
cd AI-FITNESS-ASSISTANT
```

2. **Install dependencies**
```bash
npm install
# or
yarn install
```

3. **Set up environment variables**
```env
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
CLERK_SECRET_KEY=your_clerk_secret_key
NEXT_PUBLIC_VAPI_WORKFLOW_ID=your_vapi_workflow_id
```

4. **Run the development server**
```bash
npm run dev
# or
yarn dev
```

5. Open [http://localhost:3000](http://localhost:3000) in your browser

## 📱 Core Functionality

- **Voice-Based Program Generation**: Talk to the AI assistant to create your personalized fitness plan
- **Real-time Interaction**: Get immediate feedback and adjustments during your conversation
- **Profile Management**: Track your fitness journey and access your personalized programs
- **Program Gallery**: Explore AI-generated programs from other users for inspiration

## 🔒 Environment Variables

Required environment variables:
- `NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY`: Clerk authentication public key
- `CLERK_SECRET_KEY`: Clerk authentication secret key
- `NEXT_PUBLIC_VAPI_WORKFLOW_ID`: VAPI workflow ID for voice integration

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.


## 🙏 Acknowledgments

- Built with [Next.js](https://nextjs.org/)
- Authentication by [Clerk](https://clerk.dev/)
- Voice integration by [VAPI](https://vapi.ai/)
- UI components inspired by modern design principles

---
Made with ❤️ by Agrim Gupta
