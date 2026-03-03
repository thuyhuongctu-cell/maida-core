M-AIDA Core System v7.0 🚀Automated Statistical Extraction for Meta-Analysis research.📑 Project OverviewM-AIDA (Meta-Analysis Intelligent Data Assistant) is an institutional-grade AI system designed to solve the critical challenge of manual data extraction in Meta-Analysis. It leverages LLMs to parse unstructured academic PDF files and extract statistical parameters ($N, r, t, \beta, df$) with a "Human-in-the-loop" verification workflow.Developed at the School of Economics, Can Tho University (CTU), this project ensures Computational Reproducibility and scientific integrity.🏗️ Technical Architecture (Hybrid Framework)The system is built on a high-performance multi-layer architecture:MAIDA-PROJECT/
├── maida-backend/         # AI BRAIN (Python Layer)
│   ├── server.py          # FastAPI Engine & Google Gemini API Integration
│   └── requirements.txt   # Backend dependency declarations
└── maida-frontend/        # DASHBOARD (Node.js Layer)
    ├── src/
    │   └── App.js         # React 18 UI & Interaction Logic
    └── package.json       # Frontend environment configuration
🛡️ Key Features for Scientific IntegrityVerified Extraction: Data extracted by AI must be manually verified by the researcher before final storage.Institutional Security: Integrated with Notion Database API for secure, centralized knowledge management.Hybrid Validation: Combines Python's mathematical precision with the interactive real-time capabilities of Node.js.🚀 Getting Started1. Activating the AI Brain (Backend)cd maida-backend
pip install -r requirements.txt
python server.py
2. Launching the Dashboard (Frontend)cd maida-frontend
npm install
npm start
👥 Authorship & CopyrightNCS. Đỗ Thùy Hương - Lead Researcher (School of Economics, CTU)PGS.TS. Phan Anh Tú - Research Supervisor (School of Economics, CTU)Copyright © 2026 Do Thuy Huong and Phan Anh Tu. All rights reserved.
Established at School of Economics, Can Tho University (CTU), Vietnam.
