# Flex AI 💪🤖  
**AI-Powered Fitness Coach with Voice & Personalized Plans**  

[Live Demo](https://flex-ai-six.vercel.app/) | [GitHub](https://github.com/ryanhui30/flex-ai)  

---

## ✨ Key Features  
- **🎙️ Voice-Activated Health Screening**  
  Collects BMI, injury history, and fitness goals through natural Vapi voice conversations  
- **📊 AI-Generated Fitness Plans**  
  Gemini-powered workout routines and diet plans tailored to your body metrics  
- **🔒 Secure Authentication**  
  Clerk-managed signup with Google/GitHub + email/password  
- **⚡ Real-Time Data Sync**  
  Convex database stores user profiles and workout history  
- **🎨 Beautiful UI**  
  Shadcn components with dark/light mode toggle  

---

## 🛠️ Tech Stack  

### Frontend  
| Technology       | Use Case                     |
|------------------|------------------------------|
| Next.js 15       | App Router, RSC, SSR         |
| React 19         | Interactive UI Components    |
| TypeScript       | Type Safety                  |
| Tailwind CSS     | Styling                      |
| Shadcn/ui        | Accessible UI Components     |

### Backend  
| Technology       | Use Case                     |
|------------------|------------------------------|
| Convex           | Real-time Database           |
| Vapi             | Voice AI Agent               |
| Gemini API       | Fitness/Diet Recommendations |
| Clerk            | Authentication               |
| Webhooks         | Third-party integrations     |

---

## 🚀 Getting Started

### Prerequisites
- Node.js v18+
- Convex account
- Vapi & Gemini API keys
- Clerk application

### Installation
```bash
# Clone repository
git clone https://github.com/your-username/flex-ai.git
cd flex-ai

# Install dependencies
npm install

# Set up environment variables
cp .env.example .env.local
```

### Environment Variables
```bash
# Clerk Authentication
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=

# Vapi Voice AI
NEXT_PUBLIC_VAPI_API_KEY=

# Convex Database
NEXT_PUBLIC_CONVEX_URL=
CONVEX_DEPLOYMENT_KEY=

# Gemini AI
NEXT_PUBLIC_GEMINI_API_KEY=
```

### Running the App
```bash
# Start development server
npm run dev

# Set up Convex
npx convex dev
npx convex deploy
```

## **Need Help**?
📩 Contact: ryanhui30@gmail.com
