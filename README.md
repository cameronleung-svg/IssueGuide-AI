# IssueGuide-AI

An intelligent, AI-powered GitHub automation bot designed to help open-source maintainers filter, triage, and response to GitHub Issues automatically using LLMs.

## 🚀 Key Features
- Duplicate Detection: Automatically scans existing issues and documentation to flag duplicates.
- Smart Triaging: Auto-labels incoming issues based on semantic analysis (e.g., bug, enhancement, `question`).
- Context-Aware Responses: Provides instant initial guidance to users, reducing maintainer overhead.

## 🛠️ Architecture
Built with Python, leveraging asynchronous webhooks to process live GitHub events and match them against repo context using vector embeddings.

## 🗺️ Roadmap
- [x] Initial core webhook handler structure
- [ ] Integrate vector database for full-text documentation matching
- [ ] Implement OpenAI Codex/GPT-4 API for context-dense triage (Pending API grant)

## 📄 License
MIT License
