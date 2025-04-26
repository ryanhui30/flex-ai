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
| Clerk            | Auth & User Profiles         |
| Webhooks         | Third-party Integrations     |

---

## 🚀 Getting Started

### Prerequisites
- Node.js v18+
- Convex account
- Vapi & Gemini API keys
- Clerk application

## **Development Setup**  
1. **Clone the repo**:  
  ```bash
   git clone https://github.com/ryanhui30/flex-ai.git
   cd flex-ai
  ```

2. **Install dependencies**:
  ```bash
  npm install
  ```

3. **Configure environment variables**:
- Duplicate .env.example as .env.local
- Add your credentials:
  ```bash
  # Clerk Authentication
  NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=your_publishable_key
  CLERK_SECRET_KEY=your_secret_key
  
  # Vapi Voice AI
  NEXT_PUBLIC_VAPI_API_KEY=your_vapi_key
  
  # Convex Database
  NEXT_PUBLIC_CONVEX_URL=your_convex_url
  CONVEX_DEPLOYMENT_KEY=your_deployment_key
  
  # Gemini AI
  NEXT_PUBLIC_GEMINI_API_KEY=your_gemini_key
  ```
  
4. **Database Setup**:
  ```bash
  npx convex dev
  npx convex deploy
  ```

5. **Run locally**:
  ```bash
  npm run dev          # Start dev server
  npx convex dev       # Launch Convex
  ```

## **Need Help**?
📩 Contact: ryanhui30@gmail.com
