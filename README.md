<div align="center">
  <img src="https://github.com/user-attachments/assets/044f01e2-efb9-43fe-9556-102d83ac5dc5" alt="Titan AI Logo" width="200" height="200">
  
  <p><strong>The Next-Generation AI-Powered Development Platform with an Integrated Community Hub</strong></p>

  <p>
    <a href="#installation"><strong>Installation</strong></a> •
    <a href="#features"><strong>Features</strong></a> •
    <a href="#quickstart"><strong>Quickstart</strong></a> •
    <a href="#configuration"><strong>Configuration</strong></a> •
    <a href="#community-hub"><strong>Community</strong></a> •
    <a href="#contributing"><strong>Contributing</strong></a>
  </p>
  
  <h3>✨ <a href="https://titan1.pages.dev">Try Titan AI Live!</a> ✨</h3>
</div>

# 🚀 Revolutionizing Development with AI

**Titan AI** is an open-source, browser-based development platform that brings together powerful AI models and full-stack execution in one seamless interface. Build, test, and deploy apps faster—with real-time collaboration, smart code generation, and zero local setup.

🔗 **Live Platform**: [titan1.pages.dev](https://titan1.pages.dev/)

# ✨ Core Features

## 🧠 Multi-Model Intelligence
Harness the cognitive power of industry-leading LLMs including OpenAI, Claude, Gemini, Groq, Mistral, and more. Dynamically switch between models to optimize for specific tasks—whether you need deep reasoning capabilities, extended context generation, or lightning-fast execution.

## 💻 WebContainer-Powered Development
Execute Node.js full-stack applications **entirely within your browser**. Install npm packages, run terminal commands, and instantly preview your applications—all without a single local installation.

## 🔍 Intelligent Error Recovery
Titan's AI analyzes runtime logs and exceptions in real-time, suggesting potential fixes or implementing solutions automatically—drastically reducing debugging time and accelerating your development workflow.

## 🧾 Natural Language Programming
Transform plain-language descriptions into complete, functioning codebases. Titan AI intelligently structures project directories, creates necessary files, configures dependencies, and implements business logic from simple prompts.

## 🛠️ Integrated Terminal & Live Preview
Experience the convenience of an embedded command-line interface with real-time execution feedback and application preview—mirroring the functionality of VS Code but accessible from any browser.

## 🗂️ Advanced File System
Navigate a persistent, intuitive file structure with comprehensive file management capabilities—create, edit, rename, and reorganize with familiar drag-and-drop functionality.

## 🔁 Version Control & History
Track every significant code change. Effortlessly revert to previous states, fork alternative implementations, or restore specific versions without manual backups.

## 📦 DevOps Integration
Seamlessly interface with Git repositories, commit changes, and even execute operations within containerized environments—all directly from your browser window.

## 🌍 One-Click Deployment
Export projects as ZIP archives, push directly to GitHub, or deploy instantly to platforms like Netlify, Vercel, and more—turning ideas into live applications in minutes.

## 🌐 Collaborative Development (Coming Soon)
Work simultaneously with team members on shared projects, featuring integrated chat, visual diff comparisons, and synchronized previews—making remote collaboration effortless.

# 🔥 Live Demo

Experience Titan AI yourself - no installation required:  
👉 **[https://titan1.pages.dev](https://titan1.pages.dev)**

<div align="center">
  <img src="https://example.com/titan-demo.gif" alt="Titan AI Demo" width="700">
</div>

⚠️ This is our open-source preview — some experimental features may still be in beta.

# 📦 Supported AI Providers

Titan AI supports a wide range of AI providers, allowing you to choose the right model for each specific task:

- ✅ **OpenAI** (GPT-4, GPT-4o, GPT-3.5 Turbo)
- ✅ **Anthropic** (Claude 3 Opus, Sonnet, Haiku)
- ✅ **Google** (Gemini Pro, Gemini Ultra)
- ✅ **Groq** (LPU Mixtral, LPU Llama)
- ✅ **Mistral AI** (Mistral Large, Medium, Small)
- ✅ **xAI** (Grok)
- ✅ **OpenRouter** (Access to multiple models)
- ✅ **Ollama** (Run local models)
- ✅ **LM Studio** (Custom local models)
- ✅ **HuggingFace** (Open models)
- ✅ **DeepSeek** (DeepSeek Coder)
- ✅ **Together AI** (Various models)
- ✅ **Perplexity** (pplx models)
- ✅ **AWS Bedrock** (Amazon's model ecosystem)

...and more! The platform is designed to be easily extended with additional model providers.

# ⚡ Quickstart Guide

## 🔧 Local Installation

**Prerequisites:**
- Node.js (LTS version recommended)
- pnpm package manager

```bash
# Install pnpm if you don't have it
npm install -g pnpm

# Clone the repository
git clone https://github.com/titan-ai/titan.git
cd titan

# Install dependencies
pnpm install

# Launch development server
pnpm run dev
```

## 🐳 Docker Installation

```bash
# Build the Titan AI image
docker build . --target titan-ai-development

# Launch containers with development profile
docker compose --profile development up
```

## 📦 Quick Download
For the latest stable release:
1. Download the [latest release](https://github.com/titan-ai/titan/releases/latest)
2. Extract the ZIP file
3. Follow the installation instructions in the included README

# ⚙️ Configuration

## 🔑 Adding API Keys

1. Open the Titan AI dashboard
2. Select your preferred model provider from the dropdown
3. Click the ✏️ icon to edit settings
4. Securely input your API credentials

## 🌐 Configuring Custom Base URLs

For providers that support custom endpoints (like Ollama or LM Studio):

1. Access ⚙️ > Providers from the main menu
2. Locate your provider 
3. Enter your custom endpoint URL (e.g., `http://localhost:11434`)
4. Save and verify connection

# 🛠️ Available Scripts

- `pnpm run dev`: Starts the development server
- `pnpm run build`: Builds the project
- `pnpm run preview`: Runs the production build locally
- `pnpm test`: Runs the test suite
- `pnpm run lint:fix`: Automatically fixes linting issues
- `pnpm run typecheck`: Runs TypeScript type checking
- `pnpm run deploy`: Deploys to hosting platform

# ✅ Implemented Features

- ✅ Comprehensive multi-model AI integration
- ✅ WebContainer Node.js execution environment
- ✅ Streaming terminal output with interactive feedback
- ✅ Project export (ZIP) and GitHub synchronization
- ✅ Persistent, browser-based file system
- ✅ Responsive design for all device formats
- ✅ Multimodal input (text + images)
- ✅ Selection tool to target changes visually
- ✅ Git Clone and Git Import functionality
- ✅ Intelligent error detection and fixing
- ✅ Starter template library
- ✅ Diff View to see changes
- ✅ One-click deployment to Netlify
- ✅ Chat history backup and restore
- ✅ Detachable preview window

# 🧠 Upcoming Features

- 🧠 Real-time collaborative editing
- 🧠 SQLite and PostgreSQL database integration
- 🧠 Supabase ecosystem integration
- 🧠 VS Code extension for hybrid workflows
- 🧠 Voice command processing
- 🧠 Advanced project planning with Markdown
- 🧠 Custom AI agents for specialized tasks
- 🧠 Upload documents for knowledge reference

# 🌍 Titan Nexus: Community Hub

Explore our vibrant ecosystem at the Titan Nexus — your comprehensive space to:

## 🚀 Project Showcase
- Share your Titan AI creations
- Discover innovative implementations
- Receive peer feedback and recognition

## 💬 Dynamic Forums
- 🛠️ Submit feature requests and shape product direction
- 🧩 Get specialized technical assistance
- 💡 Exchange development strategies and best practices
- 🐞 Report issues and collaborate on solutions

## 👥 Developer Network
- Create detailed developer profiles
- Connect with like-minded innovators
- Form collaboration teams
- Participate in community challenges

<div align="center"><h3><a href="https://titannexus-production.up.railway.app/">🌐 Join Titan Nexus Today!</a></h3></div>

# 🤝 Contributing

We enthusiastically welcome contributions of all types — whether you're improving code, enhancing design, expanding documentation, or building community!

## 🛠 Technical Contributions
```bash
# Standard workflow: Fork → Branch → Commit → PR

git checkout -b feature/your-innovative-feature
git commit -m "Added: Groundbreaking new capability"
git push origin feature/your-innovative-feature
```

## 🌍 Community Contributions
- Join the Titan Nexus community platform
- Share tutorials, workflow tips, or use cases
- Participate in discussions and feature planning
- Report bugs or suggest enhancements

# 📜 License

Titan AI is released under the MIT License.

⚠️ **Important**: The platform leverages WebContainers by StackBlitz, which may require commercial licensing for production deployment in commercial applications. Who needs a commercial WebContainer API license?

Titan AI source code is distributed as MIT, but it uses WebContainers API that requires licensing for production usage in a commercial, for-profit setting. (Prototypes or POCs do not require a commercial license.) If you're using the API to meet the needs of your customers, prospective customers, and/or employees, you need a license to ensure compliance with Terms of Service.

<div align="center">
  <strong>Built with ⚡ technical innovation and 🧠 collective intelligence by the Titan AI team and our vibrant open-source community</strong><br/>
  <h3><a href="https://titan1.pages.dev">🌐 Experience Titan AI Today!</a></h3>
</div>
