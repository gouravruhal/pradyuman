# pradyuman
project by team chaos.exe for hackathon on KR Mangalam University


🛡️ PRADYUMAN: Shield-as-a-Service (ShaaS)
Autonomous GRC Compliance & Neural Vulnerability Orchestration Enclave.

PRADYUMAN is a next-generation cybersecurity platform designed for Small-to-Medium Businesses (SMBs). It automates complex security audits, generates enterprise-grade policies via Llama-70B, and calculates a real-time risk posture index, all while keeping sensitive metadata under AES-256 crypto-seals.

🌟 Core Vision
Cybersecurity compliance (ISO 27001, NIST, SOC2) is often too expensive for SMBs. PRADYUMAN democratizes high-end security by providing an autonomous "Neural Auditor" that identifies gaps and synthesizes remediation strategies in real-time.

🛠️ Technology Enclave
Frontend (Cyber-Enclave UI)
Core: React 18, Vite, TypeScript.

Design: Tailwind CSS, Framer Motion (Neural/Glassmorphism theme).

Intelligence: Recharts for Dynamic Risk Trajectory (2.0x Scaling Logic).

Backend (Neural Engine)
Framework: FastAPI (Python).

AI Strategy (Groq Hybrid): * llama-3.1-8b-instant: Fast vulnerability explanations and fix suggestions.

llama-3.3-70b-versatile: Deep reasoning for GRC audits and Policy Forge.

Scanning: OWASP ZAP-based active/passive probing.

Data & Security
Database/Auth: Firebase Firestore & Auth (RBAC implemented).

Crypto: AES-256-GCM for sealing scan manifests and sensitive organization metadata.

Vault: Local backend filesystem storage for PDF policies (No binary data in Firestore).

🚀 Key Features
1. Neural Vulnerability Audit
Real-time surface mapping and vulnerability probes. Each finding is processed by the AI to provide a "Manager-level" explanation and a "Developer-level" code fix.

2. Policy Forge & Auditor
Auditor: Upload existing PDF policies to identify compliance gaps against ISO 27001 or NIST CSF.

Forge: Describe your company context, and the 70B model synthesizes a custom, professional security artifact.

3. GRC Posture Index
A unique 0-10 risk score calculated using a logistic decay model. It fuses technical vulnerabilities with compliance maturity to give a single source of truth for organization health.

🔧 Installation & Setup
Backend Configuration
Navigate to /backend.

Install dependencies:

Bash
pip install fastapi uvicorn groq PyPDF2 python-dotenv reportlab
Setup your .env file:

Code snippet
GROQ_API_KEY=your_gsk_key
Run the enclave:

Bash
python main.py
Frontend Configuration
Navigate to /frontend.

Install dependencies:

Bash
npm install
Initialize the UI:

Bash
npm run dev
🔒 Security Protocol
PRADYUMAN operates on a Privacy-First architecture:

Zero-Inference: AI models never see PII; data is anonymized before neural uplink.

Crypto-Sealing: All scan results are encrypted before storage. Only the authorized workspace owner can "Open the Vault".

👥 The Enclave Team
Rohit - Lead & Cyber-Security 1st Year.

Gourav, Khushi, Vansh - Developers & Cyber-Security 2nd Year.

Institution: Panipat Institute of Engineering and Technology (PIET).

PRADYUMAN: Shielding the digital future, one node at a time.
