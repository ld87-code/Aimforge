# AimForge: NIH Specific Aims Architect

AimForge is a specialized prompt-engineering workstation designed for biomedical researchers and engineers. It streamlines the creation of NIH Specific Aims pages by transforming technical project details into high-fidelity prompts optimized for Large Language Models (LLMs).

## 🚀 Purpose
With the **May 2026 NIH Common Form** transition (NOT-OD-26-079), grant compliance has become significantly more rigorous. AimForge helps researchers maintain scientific rigor and formatting standards without requiring expensive API subscriptions or compromising data privacy.

## 🛠 Key Features
- **Prompt Architect:** Converts raw data (Significance, Innovation, Aims) into a structured "Mega-Prompt" for use in free AI chats.
- **NIH Compliance Audit:** Built-in logic checks for:
    - **SABV (Sex as a Biological Variable):** Ensures sex-disaggregated data is mentioned.
    - **Interdependency:** Flags "Domino Aims" where Aim 2 depends entirely on Aim 1 success.
    - **Rigor & Transparency:** Prompts for power analysis, randomization, and blinding.
- **Live Preview:** Displays a real-time visualization of the document in Arial 11pt with 0.5-inch margins to ensure 1-page fit.
- **Privacy-First:** Local-first architecture. Your research data (e.g., FRANKIE or QUADROBOT projects) never leaves your browser.

## 📋 Usage
1. Open `index.html` in any modern web browser.
2. Fill in your project metadata and technical objectives.
3. Click **"Get Prompt"**.
4. Copy the generated prompt and paste it into an AI like Claude or ChatGPT.

## ⚖️ License
MIT License - Created for the academic and biotech community.
