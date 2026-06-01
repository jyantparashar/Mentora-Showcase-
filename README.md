<div align="center">

# 🎓 MENTORA AI

### Production-Grade, Low-Latency Gamified AI Career Copilot & Technical Preparation Suite

<a href="https://github.com/jyantparashar/Mentora">
  <img src="https://readme-typing-svg.herokuapp.com?font=Inter&weight=800&size=24&pause=1500&color=6366F1&center=true&vCenter=true&width=800&height=60&lines=Your+Personalized+AI+Career+Copilot...;Mock+Interviews+with+Voice+AI...;Ace+Your+Next+DSA+Interview...;Level+Up+Your+Career+Today+🚀" alt="Typing SVG" />
</a>

[![TypeScript](https://img.shields.io/badge/TypeScript-5.8-3178C6?style=for-the-badge&logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![React](https://img.shields.io/badge/React-19-61DAFB?style=for-the-badge&logo=react&logoColor=black)](https://react.dev/)
[![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)](https://firebase.google.com/)
[![Groq](https://img.shields.io/badge/Groq-Llama3.3-f55?style=for-the-badge&logo=fastapi&logoColor=white)](https://groq.com/)
[![Gemini](https://img.shields.io/badge/Gemini-1.5%20Flash-4285F4?style=for-the-badge&logo=google&logoColor=white)](https://ai.google.dev/)
[![ThreeJS](https://img.shields.io/badge/Three.js-WebGL-000000?style=for-the-badge&logo=three.js&logoColor=white)](https://threejs.org/)
[![Vercel](https://img.shields.io/badge/Vercel-Deployment-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://vercel.com/)

<br/>

> **Mentora AI** is an advanced, edge-optimized, and gamified AI career ecosystem designed to bridge the gap between academic preparation and elite industry employment. Featuring an ultra-low-latency, real-time voice synthesis loop, WebGL holographic canvas rendering, computer-vision proctoring systems, fully isolated compiler sandboxing (via Judge0), and AST-optimized resume intelligence, Mentora AI provides candidates with an immersive FAANG-fidelity preparation arena.

### 🌐 [Launch Mentora AI Live on Vercel](https://mentora-mu-pearl.vercel.app)

---

</div>

## 🛑 REPOSITORY NOTICE
> [!NOTE]
> **Proprietary Source Code:** The core implementation files, custom prompts, and trained browser vision weights for Mentora AI remain under a private repository structure to protect intellectual property. This public-facing repository acts as a **system architecture blueprint, production documentation showcase, and deployment anchor** for technical recruiters and engineering panels.

---

## 🎯 EXECUTIVE OVERVIEW

### The Problem
Traditional technical interview preparation is highly fragmented. Candidates bounce between static coding platforms, expensive voice coaching software, and isolated resume optimization tools. Furthermore, mock environments lack the stress testing of real-time behavioral surveillance and immediate runtime profiling, leading to a gap between artificial practice and real interview high-pressure performance.

### The Solution
**Mentora AI** unifies these preparation vectors into a high-performance, single-page client interface. By processing computational telemetry natively on the user's edge hardware (video, audio analytics, and UI layout resolution) and routing heavy code execution and linguistic mapping through low-latency inference pipelines, Mentora AI offers a zero-lag, highly responsive arena.

---

## 🏗️ 1. SYSTEM ARCHITECTURE FLOW

Mentora AI is architected with a decoupled, high-performance multi-tier pipeline. Client-side workloads leverage edge processing (using MediaPipe Web workers for video inference and browser Web Speech APIs), while computationally intensive compiles and AI operations flow through specialized external execution engines and low-latency API routers.

```mermaid
graph TD
    %% Styling Definitions
    classDef client fill:#1e1e3f,stroke:#6366f1,stroke-width:2px,color:#e0e7ff;
    classDef gateway fill:#2d1b4e,stroke:#a855f7,stroke-width:2px,color:#f3e8ff;
    classDef database fill:#143a28,stroke:#22c55e,stroke-width:2px,color:#d1fae5;
    classDef aiservice fill:#1c2d42,stroke:#3b82f6,stroke-width:2px,color:#dbeafe;
    classDef executor fill:#3b1e1e,stroke:#ef4444,stroke-width:2px,color:#fee2e2;
    classDef actor fill:#0f172a,stroke:#475569,stroke-width:2px,color:#f8fafc;

    %% Nodes & Connections
    User(("👤 User / Candidate")):::actor
    
    subgraph Client_Edge_Layer ["⚛️ CLIENT EDGE LAYER (React 19 SPA)"]
        FE["🖥️ React 19 / Vite App"]:::client
        Monaco["💻 Monaco Code IDE"]:::client
        Webcam["📷 Webcam Capture Core"]:::client
        Audio["🎙️ Web Speech API Loop"]:::client
    end

    subgraph Auth_Gateways ["🔐 ORCHESTRATION & GATEWAYS"]
        Auth["🔥 Firebase Auth (JWT Tokens)"]:::gateway
        VercelEdge["⚡ Vercel Edge Serverless Rules"]:::gateway
    end

    subgraph RealTime_Data ["🔥 REAL-TIME DATA TIER"]
        Firestore[("🗄️ Cloud Firestore DB")]:::database
    end

    subgraph Intelligence_Execution ["🧠 INTELLIGENCE & SANDBOX RUNTIMES"]
        Groq["⚡ Groq API (Llama 3.3 70B / 3.1 8B)"]:::aiservice
        Gemini["🧠 Gemini 1.5 Flash (RAG & Roadmaps)"]:::aiservice
        Judge0["🛡️ Judge0 Sandbox API"]:::executor
        MediaPipe["🧬 MediaPipe + face-api.js Edge Models"]:::client
        Telemetry["📊 Live Telemetry & Growth Engine"]:::database
    end

    %% Flow Vectors
    User -->|Interacts| FE
    FE <-->|Code Buffers| Monaco
    FE <-->|Frame Stream| Webcam
    FE <-->|Audio Stream| Audio
    
    FE <-->|Token Exchange| Auth
    FE <-->|Route Resolution| VercelEdge
    
    FE <-->|Dynamic Streaks & Analytics Sync| Firestore
    
    %% Internal Connections & Deep Pipelines
    Webcam -->|Real-time Frames| MediaPipe
    MediaPipe -->|Face Expression & Gaze Vectors| Telemetry
    Telemetry -->|Upsert Live Session States| Firestore
    
    Monaco -->|Isolated Remote Compilation| Judge0
    Audio -->|Speech Input Transcriptions| Groq
    FE -->|RAG Ingestion & Career Vectors| Gemini
    Groq -->|Real-Time Speech Synthesis Response| FE
    Gemini -->|Dynamic SVG Roadmap Canvas| FE

    %% Link to Vercel Deployment
    VercelEdge -.->|Hosts Client SPA Assets| FE

graph TD
    %% Styling Definitions
    classDef startEnd fill:#0f172a,stroke:#3b82f6,stroke-width:2px,color:#f8fafc,rx:15px,ry:15px;
    classDef step fill:#1e1e3f,stroke:#6366f1,stroke-width:2px,color:#e0e7ff;
    classDef decision fill:#2d1b4e,stroke:#a855f7,stroke-width:2px,color:#f3e8ff;
    classDef database fill:#143a28,stroke:#22c55e,stroke-width:2px,color:#d1fae5;

    Start(["🔑 User Login (Google/Email Auth)"]):::startEnd
    Dash["🎛️ Personalized Dashboard (Active Streaks & Progress)"]:::step
    FeatureSelect{"🎯 Feature Selection Hub"}:::decision
    
    %% Branching Features
    DSA["💻 Coding Interview (Monaco Editor + Live Proctoring)"]:::step
    Mock["🎙️ Mock Interview (Voice AI Coach + Three.js Avatar)"]:::step
    Career["🤖 Career Guidance (Aria Copilot & Roadmaps)"]:::step
    Resume["📄 Resume Analysis (ATS Ingestion & Optimization)"]:::step
    
    %% Core pipelines and loops
    ProctorCheck["🛡️ Edge Proctoring & Attention Analysis"]:::step
    ExecutionLoop["⚙️ Code Execution Sandbox (Judge0)"]:::step
    AIFeedback["🧠 AI Synthesis & Complexity Scoring"]:::step
    
    DBUpdate[("🔥 Firestore Persistence (Rank & Telemetry Update)")]:::database
    EndChart(["📊 Live Analytics Engine & Growth Charts"]):::startEnd

    %% Connection Logic
    Start --> Dash
    Dash --> FeatureSelect
    
    FeatureSelect -->|DSA Arena| DSA
    FeatureSelect -->|Voice Interview| Mock
    FeatureSelect -->|Career Copilot| Career
    FeatureSelect -->|Resume Ingestion| Resume
    
    %% Coding interview loop
    DSA --> ProctorCheck
    DSA --> ExecutionLoop
    ExecutionLoop --> AIFeedback
    
    %% Mock interview loop
    Mock --> ProctorCheck
    ProctorCheck --> AIFeedback
    
    %% Career & Resume outcomes
    Career --> AIFeedback
    Resume --> AIFeedback
    
    AIFeedback --> DBUpdate
    DBUpdate --> EndChart
    EndChart -->|Return to Main Workspace| Dash

graph TD
    %% Styling Definitions
    classDef step fill:#1e1e3f,stroke:#6366f1,stroke-width:2px,color:#e0e7ff;
    classDef process fill:#2d1b4e,stroke:#a855f7,stroke-width:2px,color:#f3e8ff;
    classDef external fill:#3b1e1e,stroke:#ef4444,stroke-width:2px,color:#fee2e2;
    classDef db fill:#143a28,stroke:#22c55e,stroke-width:2px,color:#d1fae5;

    QLoad["📂 Question Loaded (Firestore Problem Set)"]:::step
    Boilerplate["⚙️ Active Language Selection & Boilerplate Setup"]:::process
    MonacoIDE["💻 Monaco Split-Screen Editor Workspace"]:::step
    
    UserInteract{"User Action"}:::process
    TriggerRun["▶️ Run Code / Dry Run"]:::process
    VoiceSpeak["🗣️ Explain Logic (VAD Audio Waveform)"]:::process
    
    SandboxJudge["🛡️ Remote Judge0 Sandboxed Execution Environment"]:::external
    LocalFallback["⚙️ Client JS/Python Sandboxed Dry-Run Fallback"]:::step
    
    ValidCheck["🔍 Test Case Output Verification & Execution Metrics"]:::process
    TelemetrySync[("📊 Telemetry Metrics Sync (Rank & Streak Score)")]:::db
    AIEval["🧠 AI Feedback Loop (Time/Space Complexity, Code Optimization)"]:::step

    %% Flow Vectors
    QLoad --> Boilerplate
    Boilerplate --> MonacoIDE
    MonacoIDE --> UserInteract
    
    UserInteract -->|Trigger Compilation| TriggerRun
    UserInteract -->|Engage Audio Pipeline| VoiceSpeak
    
    TriggerRun -->|API Push| SandboxJudge
    TriggerRun -.->|Offline Mode| LocalFallback
    
    SandboxJudge --> ValidCheck
    LocalFallback --> ValidCheck
    
    VoiceSpeak --> AIEval
    ValidCheck --> TelemetrySync
    TelemetrySync --> AIEval
    AIEval -->|Render UI Recommendations & Output Cards| MonacoIDE
graph TD
    %% Styling Definitions
    classDef client fill:#1e1e3f,stroke:#6366f1,stroke-width:2px,color:#e0e7ff;
    classDef process fill:#2d1b4e,stroke:#a855f7,stroke-width:2px,color:#f3e8ff;
    classDef ai fill:#1c2d42,stroke:#3b82f6,stroke-width:2px,color:#dbeafe;
    classDef storage fill:#143a28,stroke:#22c55e,stroke-width:2px,color:#d1fae5;

    Query["💬 User Query / Input (Voice or Chat Prompt)"]:::client
    RAGInject["📄 RAG Segment Injection (Local Resume/Context PDF Parser)"]:::process
    Prompter["🏗️ Prompt Processing & System Context Assembly"]:::process
    
    EngineSelect{"🧠 Routing Optimization Engine"}:::process
    
    GroqLLM["⚡ Groq API (Llama 3.3 70B - Ultra Low Latency Conversation)"]:::ai
    GeminiLLM["🧠 Gemini 1.5 Flash (Complex JSON Maps & Large RAG Context)"]:::ai
    
    Response["📜 Raw AI Response Generation"]:::process
    Parser["🧩 JSON Stream Validation & Schema Correction"]:::process
    Context["🧬 Context Layer (Session Memory & Local Cache Update)"]:::storage
    UIRender["🎨 Dynamic UI Render Loop (Roadmap Nodes, Avatar Animation)"]:::client

    %% Connections
    Query --> Prompter
    RAGInject --> Prompter
    Prompter --> EngineSelect
    
    EngineSelect -->|Technical Interview / Active Chat| GroqLLM
    EngineSelect -->|Roadmap Canvas / Resume AST Analysis| GeminiLLM
    
    GroqLLM --> Response
    GeminiLLM --> Response
    
    Response --> Parser
    Parser --> Context
    Context --> UIRender

graph TD
    %% Styling Definitions
    classDef input fill:#0f172a,stroke:#3b82f6,stroke-width:2px,color:#f8fafc;
    classDef model fill:#1c2d42,stroke:#3b82f6,stroke-width:2px,color:#dbeafe;
    classDef tracker fill:#2d1b4e,stroke:#a855f7,stroke-width:2px,color:#f3e8ff;
    classDef score fill:#1e1e3f,stroke:#6366f1,stroke-width:2px,color:#e0e7ff;
    classDef danger fill:#3b1e1e,stroke:#ef4444,stroke-width:2px,color:#fee2e2;

    Cam["📷 Webcam Frame Capture (60 FPS Callback Reference Loop)"]:::input
    
    subgraph Edge_Analysis_Models ["🧬 EDGE COMPUTER VISION LAYER"]
        MediaPipeLib["🧬 MediaPipe Face Mesh"]:::model
        FaceApiLib["🧬 face-api.js Core Models"]:::model
    end
    
    subgraph Tracking_Telemetry ["📊 REAL-TIME TRACKING SUITE"]
        Gaze["👀 Attention & Gaze Calibration Tracking"]:::tracker
        Expression["🎭 Micro-Expression & Confidence Tracking"]:::tracker
        Focus["🧠 Focal center deviation computation"]:::tracker
    end

    Confidence{"⚖️ Confidence & Integrity Scoring Engine"}:::score
    
    subgraph Security_Enforcement ["🛡️ SYSTEM SECURITY & PROCTORING PIPELINE"]
        FocusHUD["📊 Live Proctoring Telemetry Overlay"]:::score
        VisibilityCheck["🚨 Visibility API (Tab-Switch / Focus Monitoring)"]:::tracker
        WarningEngine{"⚠️ Strike Threshold Warning Engine"}:::danger
        Terminator["❌ Forced Session Termination (3 Strikes)"]:::danger
    end

    CloudAnalytics[("📈 Cloud Firestore & Real-Time Growth Analytics")]:::model

    %% Flow Paths
    Cam --> MediaPipeLib
    Cam --> FaceApiLib
    
    MediaPipeLib --> Gaze
    FaceApiLib --> Expression
    Gaze --> Focus
    
    Focus --> Confidence
    Expression --> Confidence
    
    Confidence --> FocusHUD
    Confidence --> WarningEngine
    VisibilityCheck --> WarningEngine
    
    WarningEngine -->|Integrity Score Valid| CloudAnalytics
    WarningEngine -->|Distraction Detected / Multi-Tab Switch| Terminator

graph TD
    %% Styling Definitions
    classDef vcs fill:#0f172a,stroke:#475569,stroke-width:2px,color:#f8fafc;
    classDef build fill:#2d1b4e,stroke:#a855f7,stroke-width:2px,color:#f3e8ff;
    classDef deploy fill:#143a28,stroke:#22c55e,stroke-width:2px,color:#d1fae5;
    classDef config fill:#1e1e3f,stroke:#6366f1,stroke-width:2px,color:#e0e7ff;

    GitLocal["💻 Local Repository Workstation"]:::vcs
    PrePush{"🚨 Pre-Push Verification"}:::config
    
    TSCheck["🔧 TypeScript Compilation & Strict Linting"]:::config
    ViteBuild["📦 Vite Production Bundle Build Optimization"]:::config
    
    GitPush["🐙 Git Push to Repository (GitHub Origin/Main)"]:::vcs
    GitHubHook["🔌 GitHub Webhook Trigger Event"]:::vcs
    
    subgraph Vercel_Build_Cloud ["⚡ VERCEL EDGE RUNTIME LAYER"]
        VercelBuild["⚡ Edge Serverless Compilation & Compression"]:::build
        RouteMap["🗺️ vercel.json SPA Router Rule Mapping"]:::build
    end
    
    ProdDeploy["🚀 Production Deployment Live Server (mentora-mu-pearl.vercel.app)"]:::deploy
    EdgeCDN["⚡ Global Edge CDN Propagation (Ultra-Low Latency Asset Delivery)"]:::deploy

    %% Routing
    GitLocal --> PrePush
    PrePush -->|Perform Lint check| TSCheck
    PrePush -->|Verify Bundler compatibility| ViteBuild
    
    TSCheck & ViteBuild -->|Successful Build Validation| GitPush
    GitPush --> GitHubHook
    GitHubHook --> VercelBuild
    VercelBuild --> RouteMap
    RouteMap --> ProdDeploy
    ProdDeploy --> EdgeCDN

graph TD
    classDef client fill:#1e1e3f,stroke:#6366f1,stroke-width:2px,color:#e0e7ff;
    classDef security fill:#2d1b4e,stroke:#a855f7,stroke-width:2px,color:#f3e8ff;
    classDef database fill:#3b1e1e,stroke:#ef4444,stroke-width:2px,color:#fee2e2;

    Trigger["🔴 User Initiates Deletion in UI"]:::client
    Reauth{"🔐 Identity Safety Validation<br/>reauthenticateWithCredential"}:::security
    
    subgraph Parallel_Cloud_Data_Purge ["🗑️ CASCADING CLOUD PARALLEL CLEANUP"]
        WipeLogs["Wipe Compilation Analytics Logs"]:::database
        WipeRoadmaps["Purge Extracted SVG Roadmaps"]:::database
        WipeInterviews["Clear Historical Audio Session Logs"]:::database
    end
    
    WipeAuth["🔥 Terminate Firebase Core Authentication Profile"]:::security
    UIRefresh["🔄 Destructive Interface Lock & Route Redirect"]:::client

    Trigger --> Reauth
    Reauth -->|Credential Match Success| WipeLogs & WipeRoadmaps & WipeInterviews
    WipeLogs & WipeRoadmaps & WipeInterviews --> WipeAuth
    WipeAuth --> UIRefresh

Mentora/
├── public/                       # Global static assets, face models, Three.js shaders
├── src/
│   ├── react-app/
│   │   ├── components/
│   │   │   ├── counselor/        # Aria Chat elements, Suggested action nodes
│   │   │   ├── dashboard/        # WelcomeHero, Streak modules, progression panels
│   │   │   ├── interview/        # Three.js holographic engine, Face-API video loops
│   │   │   ├── layout/           # Expandable SaaS Sidebar, Mobile bottom navigation
│   │   │   └── ui/               # RAG PDF upload modules, AIGreeting dynamic toast, micro-interaction wrappers
│   │   ├── lib/
│   │   │   ├── auth.tsx          # Firebase authentication session contexts
│   │   │   ├── counselor.ts      # Multi-stage custom prompts & system directives
│   │   │   ├── db.ts             # Cloud Firestore read/write operations
│   │   │   ├── gemini.ts         # LLM streams, response validation parsing
│   │   │   ├── jobsearch.ts      # Live aggregator API routes (LinkedIn/Glassdoor)
│   │   │   ├── notifications.tsx # Customized glassmorphic toast notification modules
│   │   │   ├── rag.ts            # Text chunk tokenizers and local vector helpers
│   │   │   ├── realtime.ts       # Telemetry calculators & database synchronization
│   │   │   └── theme.tsx         # Sleek dark mode / theme-switching controls
│   │   ├── pages/
│   │   │   ├── Auth.tsx          # Animated authentication drawer & social sign-in
│   │   │   ├── CareerCounselor.ts# Aria Copilot, Mobile Layout switcher, Job Finder
│   │   │   ├── Copilot.tsx       # Lazy-loaded page wrapper
│   │   │   ├── DSAMentor.tsx     # 3-Column Monaco Workspace & Sandboxed compiler
│   │   │   ├── Home.tsx          # Unified student metrics & action center
│   │   │   ├── Profile.tsx       # Developer skills, years of prep & rank status
│   │   │   └── Progress.tsx      # SVG chart reports, learning speed analysis
│   │   ├── index.css             # Vanilla CSS core design system tokens & keyframes
│   │   └── main.tsx              # Main system bootstrapping index
├── vercel.json                   # SPA edge routing and cache policy directives
├── vite.config.ts                # Hot Module Replacement & production bundle configs
└── package.json                  # Strict dependencies registry

git clone [https://github.com/jyantparashar/Mentora.git](https://github.com/jyantparashar/Mentora.git)
cd Mentora
npm install

VITE_FIREBASE_API_KEY=your_firebase_api_key
VITE_FIREBASE_AUTH_DOMAIN=your_firebase_auth_domain
VITE_FIREBASE_PROJECT_ID=your_firebase_project_id
VITE_FIREBASE_STORAGE_BUCKET=your_firebase_storage_bucket
VITE_FIREBASE_MESSAGING_SENDER_ID=your_firebase_messaging_sender_id
VITE_FIREBASE_APP_ID=your_firebase_app_id
VITE_FIREBASE_MEASUREMENT_ID=your_firebase_measurement_id
VITE_GROQ_API_KEY=your_groq_api_key
VITE_GEMINI_API_KEY=your_gemini_api_key


npm run dev

vercel --prod
