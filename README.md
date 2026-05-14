# Chemistry Learning Assistant Chatbot

A **ChatGPT-style AI chatbot** designed to help **college students learn chemistry**.  
Built with **Next.js**, **TailwindCSS**, and the **OpenAI API**, this assistant provides **step-by-step explanations**, **context-aware chat**, and **streaming responses** in real time.

---

## 🌟 Features

- Face-to-face chat interface like ChatGPT
- Streaming responses for live typing effect
- Context-aware: remembers conversation history per session
- Supports **dark mode toggle**
- Automatic scroll to latest message
- User questions on the right, AI answers on the left
- Avatars for user (👤) and AI (🤖)

---

## 🛠 Technology Stack

- **Frontend**: Next.js (App Router) + React
- **Backend**: Native Next.js API routes
- **Styling**: TailwindCSS
- **AI**: OpenAI Chat Completion API (gpt-4o-mini)
- **Markdown Support**: `react-markdown` for rich text formatting

---

## ⚡ Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/your-username/chemistry-assistant.git
cd chemistry-assistant
```

### 2. Install dependencies

```baxh
npm install
```

### 3. Create .env.local file

Create a file in the project root:
```
OPENAI_API_KEY=your_openai_api_key_here
```
You can get an API key from OpenAI

### 4. Run the development server

```bash
npm run dev
```
Open your browser at http://localhost:3000

