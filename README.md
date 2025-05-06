<div align="center">
  <img src="https://github.com/user-attachments/assets/044f01e2-efb9-43fe-9556-102d83ac5dc5" alt="TitanAiCore Logo" width="200" height="200">

  <h1>TitanAiCore</h1>
  <p><strong>The Next-Generation AI-Powered Development Platform</strong></p>

  <p>
    <a href="#installation"><strong>Installation</strong></a> •
    <a href="#features"><strong>Features</strong></a> •
    <a href="#quickstart-guide"><strong>Quickstart</strong></a> •
    <a href="#configuration"><strong>Configuration</strong></a> •
    <a href="#community"><strong>Community</strong></a> •
    <a href="#contributing"><strong>Contributing</strong></a>
  </p>

  <h3>✨ <a href="https://titanaicore.pages.dev">Try TitanAiCore Live!</a> ✨</h3>
</div>

# 🚀 Revolutionizing Development with AI

**TitanAiCore** is an open-source, browser-based development platform that brings together powerful AI models and full-stack execution in one seamless interface. Build, test, and deploy apps faster—with real-time collaboration, smart code generation, and zero local setup.

🔗 **Live Platform**: [titanaicore.pages.dev](https://titanaicore.pages.dev/)

## 🛠️ Installation

### 🚀 Quick Download

* **Download the [latest release](https://github.com/techTenzen/TitanAiCore/releases/latest)**
* Extract the ZIP file
* Follow the installation instructions in the included README

### 📋 Prerequisites

Before you begin, you'll need to install:

* **Node.js** (LTS version recommended)
* **pnpm** package manager

**Install Node.js:**
* Visit the [Node.js Download Page](https://nodejs.org/)
* Download the "LTS" version for your OS
* Run the installer and accept the default settings

**Verify Node.js Installation:**
* **Windows:**
  Press `Windows + R`, type `sysdm.cpl`, press Enter.
  Go to "Advanced" → "Environment Variables" and check if Node.js appears in the "Path" variable.
* **Mac/Linux:**
  Open Terminal, run:
  ```sh
  echo $PATH
  ```
  Look for `/usr/local/bin` in the output.

### 🔧 Local Installation

Install pnpm if you don't have it:
```sh
npm install -g pnpm
```

Clone the repository:
```sh
git clone https://github.com/techTenzen/TitanAiCore.git
cd TitanAiCore
```

Install dependencies:
```sh
pnpm install
```

Launch development server:
```sh
pnpm run dev
```

### 🐳 Docker Installation

Build the TitanAiCore image:
```sh
docker build . --target titanaicore-development
```

Launch containers with development profile:
```sh
docker compose --profile development up
```

## ✨ Features

### 🧠 Multi-Model Intelligence
Harness the cognitive power of industry-leading LLMs including OpenAI, Claude, Gemini, Groq, Mistral, and more.

### 💻 WebContainer-Powered Development
Execute Node.js full-stack applications **entirely within your browser**.

### 🔍 Intelligent Error Recovery
TitanAiCore analyzes runtime logs and exceptions in real-time, suggesting potential fixes.

### 🧾 Natural Language Programming
Transform plain-language descriptions into complete, functioning codebases.

### 🛠️ Integrated Terminal & Live Preview
Experience the convenience of an embedded command-line interface with real-time execution feedback.

### 🗂️ Advanced File System
Navigate a persistent, intuitive file structure with comprehensive file management capabilities.

### 🔁 Version Control & History
Track every significant code change. Effortlessly revert to previous states.

### 🌐 Collaborative Development (Coming Soon)
Work simultaneously with team members on shared projects.

### 📊 Advanced Analytics Dashboard
Monitor your projects with comprehensive analytics, performance metrics, and AI usage insights.

### 🗺️ Roadmap & Feature Progress
Below is a live checklist of requested features, integrations, and enhancements-showing what’s shipped and what’s planned. Community contributions are welcome!

## 🟩 Completed

✅ OpenRouter Integration (@coleam00)

✅ Gemini Integration (@jonathands)

✅ Autogenerate Ollama models from what is downloaded (@yunatamos)

✅ Filter models by provider (@jasonm23)

✅ Download project as ZIP (@fabwaseem)

✅ Improvements to the main bolt.new prompt (@kofi-bhr)

✅ DeepSeek API Integration (@zenith110)

✅ Mistral API Integration (@ArulGandhi)

✅ "Open AI Like" API Integration (@ZerxZ)

✅ One-way file sync to local folder (@muzafferkadir)

✅ Docker containerization for easy install (@aaronbolton)

✅ Publish projects directly to GitHub (@goncaloalves)

✅ Enter API keys in the UI (@ali00209)

✅ xAI Grok Beta Integration (@milutinke)

✅ LM Studio Integration (@karrot0)

✅ HuggingFace Integration (@ahsan3219)

✅ Bolt terminal for LLM run output (@thecodacus)

✅ Streaming code output (@thecodacus)

✅ Revert code to earlier version (@wonderwhy-er)

✅ Chat history backup and restore (@sidbetatester)

✅ Cohere Integration (@hasanraiyan)

✅ Dynamic model max token length (@hasanraiyan)

✅ Prompt enhancements & caching (@SujalXplores)

✅ Load local projects into app (@wonderwhy-er)

✅ Together Integration (@mouimet-infinisoft)

✅ Mobile friendly (@qwikode)

✅ Attach images to prompts (@atrokhym, @stijnus)

✅ Git Clone & Import from URL (@thecodacus)

✅ PromptLibrary for use-case variations (@thecodacus)

✅ Auto install & preview for folder/git import (@wonderwhy-er)

✅ Selection tool for visual changes (@emcconnell)

✅ Error detection & auto-fix (terminal/preview) (@thecodacus, @wonderwhy-er)

✅ Starter Template Options (@thecodacus)

✅ Perplexity Integration (@meetpateltech)

✅ AWS Bedrock Integration (@kunjabijukchhe)

✅ Diff View for changes (@toddyclipsgg)

✅ Deploy directly to Netlify (@xKevIsDev)

✅ Popout Window for Web Container & resize (@stijnus)

## 🟨 In Progress / High Priority

🧠 Prevent bolt from rewriting files as often (file locking and diffs)

🧠 Better prompting for smaller LLMs (code window stability)

🧠 Run agents in the backend (not just single model calls)

## ⬜ Planned / Requested

⬜ Supabase Integration

⬜ LLM project planning in Markdown

⬜ VSCode Integration with git-like confirmations

⬜ Upload documents for knowledge (UI, codebase, etc.)

⬜ Voice prompting

⬜ Azure Open AI API Integration

⬜ Vertex AI Integration

⬜ Granite Integration

## 🏃‍♀️ Quickstart Guide

See the [Installation](#installation) section above for setup instructions.



## ⚙️ Configuration

### 🔑 Adding API Keys

1. Open the TitanAiCore dashboard
2. Select your preferred model provider from the dropdown
3. Click the ✏️ icon to edit settings
4. Securely input your API credentials

### 🌐 Configuring Custom Base URLs

For providers that support custom endpoints (like Ollama or LM Studio):

1. Access ⚙️ > Providers from the main menu
2. Locate your provider
3. Enter your custom endpoint URL (e.g., `http://localhost:11434`)
4. Save and verify connection

### Supported Providers
* Ollama
* LM Studio
* OpenAILike

### 💡 Tips for Best Results
For best results, use a sophisticated provider/model like Anthropic Claude Sonnet 3.x. The system prompt currently implemented works better with some models than others. A future plugin/extensions library is planned to provide different system prompts for different models.

## 🧑‍💻 Developer Setup (Using Git)

This method is for those who want to contribute, stay updated with the latest changes, or create custom modifications.

**Prerequisites:**
Install [Git](https://git-scm.com/downloads)

**Initial Setup:**
```sh
git clone -b stable https://github.com/techTenzen/TitanAiCore.git
cd TitanAiCore
pnpm install
pnpm run dev
```

*(Optional)* Switch to the main branch for pre-release features:
```sh
git checkout main
pnpm install
pnpm run dev
```

Open the Web UI (Default: [http://localhost:5173](http://localhost:5173))

### 🔄 Staying Updated

To get the latest changes:
```sh
git stash          # Save your local changes
git pull           # Pull latest updates
pnpm install       # Update dependencies
git stash pop      # Restore your changes
```

### Troubleshooting Git Setup:
```sh
rm -rf node_modules pnpm-lock.yaml
pnpm store prune
pnpm install
git reset --hard origin/main

# Or for stable branch
git reset --hard origin/stable
```



## 🚀 TitanAiCore vs Other AI Code Generators

TitanAiCore stands out in the competitive landscape of AI-powered development platforms. Our community-driven benchmarks show significant advantages in key areas:


## 📜 Available Scripts

| Script | Description |
|--------|-------------|
| `pnpm run dev` | Starts the development server |
| `pnpm run build` | Builds the project |
| `pnpm run start` | Runs the built app locally with Wrangler Pages |
| `pnpm run preview` | Builds and runs the production build locally |
| `pnpm test` | Runs the test suite using Vitest |
| `pnpm run typecheck` | Runs TypeScript type checking |
| `pnpm run typegen` | Generates TypeScript types using Wrangler |
| `pnpm run deploy` | Deploys the project to Cloudflare Pages |
| `pnpm run lint:fix` | Automatically fixes linting issues |

## 🌍 Community

Explore our vibrant ecosystem - your comprehensive space to:

### 🚀 Project Showcase
* Share your TitanAiCore creations
* Discover innovative implementations
* Receive peer feedback and recognition

### 💬 Dynamic Forums
* Submit feature requests and shape product direction
* Get specialized technical assistance
* Exchange development strategies and best practices
* Report issues and collaborate on solutions

### 👥 Developer Network
* Create detailed developer profiles
* Connect with like-minded innovators
* Form collaboration teams
* Participate in community challenges

<div align="center">
  <h3><a href="https://github.com/techTenzen/TitanAiCore/discussions">🌐 Join TitanAiCore Community Today!</a></h3>
  
  <img src="https://via.placeholder.com/800x200?text=Community+Activity+Heatmap" alt="Community Activity" width="80%">
</div>

## 👨‍💻 Contributing

We enthusiastically welcome contributions of all types - whether you're improving code, enhancing design, expanding documentation, or building community!

### 🛠 Technical Contributions

Standard workflow: Fork → Branch → Commit → PR
```sh
git checkout -b feature/your-innovative-feature
git commit -m "Added: Groundbreaking new capability"
git push origin feature/your-innovative-feature
```

### 🌍 Community Contributions
* Join the GitHub discussions
* Share tutorials, workflow tips, or use cases
* Participate in discussions and feature planning
* Report bugs or suggest enhancements


## 📝 License

TitanAiCore is released under the MIT License.

⚠️ **Important**: The platform leverages WebContainers by StackBlitz, which may require commercial licensing for production deployment in commercial applications.

<div align="center">
  <p><strong>Built with ⚡ technical innovation and 🧠 collective intelligence by the TitanAiCore team and our vibrant open-source community</strong></p>
  <h3><a href="https://titanaicore.pages.dev">🌐 Experience TitanAiCore Today!</a></h3>
</div>
