# ChatGPT Clone using Gemini API (Assistant-UI)

This is a simple AI-powered chat application built using [Assistant-UI](https://www.assistant-ui.com/docs/getting-started), integrated with **Google's Gemini API (gemini-pro)**. I followed the setup to learn how to use AI SDKs, manage environment variables, and deploy full-stack apps with **Next.js** and **Vercel**.

---

## Demo

🔗 [Live Site](https://gem-gpt-one.vercel.app/)

---

## What I Learned

- Setting up a Next.js project using `npx assistant-ui@latest create`
- Installing and using the `@ai-sdk/google` for Gemini integration
- Creating API routes in Next.js (`route.ts`)
- Managing API keys securely via `.env.local`
- Running and building the project locally
- Deploying the project to **Vercel** via **GitHub**

---

## Tech Stack

- Next.js
- TypeScript
- Tailwind CSS (via Assistant-UI)
- Vercel (Deployment)
- Google Gemini API
- AI SDK (`@ai-sdk/google`, `@assistant-ui/react-ai-sdk`, `ai`)

---

## Installation Steps

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/chatgpt-gemini-clone.git
cd chatgpt-gemini-clone
2. Install Dependencies
bash
Copy
Edit
npm install
3. Add Your API Key
Create a .env.local file in the root directory and add:

env
Copy
Edit
GOOGLE_GENERATIVE_AI_API_KEY="your_api_key"
4. Run the Development Server
bash
Copy
Edit
npm run dev
Visit http://localhost:3000 in your browser.

5. Build for Production
bash
Copy
Edit
npm run build

```

 ## Deployment
I deployed the app using Vercel:

Pushed the project to GitHub

Connected the GitHub repo to Vercel

Selected the my-app folder and framework as Next.js

Added the environment variable (GOOGLE_GENERATIVE_AI_API_KEY)

Deployed 🎉

🙋‍♂️ About Me
I'm currently exploring full-stack development and modern AI tools. This project was a great opportunity to learn how to work with external APIs, use AI SDKs, and deploy real-world applications.

Feel free to check out my GitHub for more!
