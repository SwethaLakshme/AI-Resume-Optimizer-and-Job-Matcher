# AI Resume Optimizer & Job Matcher

🚀 **Live App Demo:** [Launch on AWS PartyRock](https://partyrock.aws/u/SwethaLakshme/3cATC4hSK/AI-Resume-Optimizer-and-Job-Matcher)  
✍️ **Project Case Study:** [Read on AWS Builder Center](https://builder.aws.com/content/3JZpGg0ncCstKOxhtWQpnkGHeb2/building-an-ai-resume-optimizer-and-job-matcher-with-aws-partyrock)

---

## 📌 Project Overview
Landing a target job requires communicating relevant experience clearly and aligning it with the distinct nuances of a job description. **AI Resume Optimizer & Job Matcher** is an intelligent career assistant engineered on **AWS PartyRock** and powered by foundational large language models (LLMs) via **Amazon Bedrock**. 

Instead of blindly inflating text to beat Applicant Tracking Systems (ATS), this application streamlines the resume tailoring process. It delivers an evidence-based compatibility report and highly contextual optimization strategies while maintaining complete factual integrity.

---

## 📊 Core Workflow & Architecture

The application relies on interconnected AI widgets that pipeline data through distinct, modular stages:

1. **Information Extraction:** Parses user resumes and targeted job postings to isolate tech stacks, functional metrics, and specific requirements.
2. **ATS Compatibility Engine:** Compares parsed content to extract missing keywords, compute an overall alignment score, and highlight structural challenges.
3. **Tailored Copy Generation:** Provides actionable, role-specific content revisions across core resume blocks without fabricating experiences.

---

## 💡 Engineered AI Widgets & Prompts

The system relies on chained prompt logistics to keep outputs grounded and structured:

### 1. Resume & Job Description Analyzer
* **Purpose:** Cleanses text and isolates essential data points.
* **Prompt Strategy:** Structured formatting cues that command the model to parse technical competencies, methodologies, and leadership metrics into clear arrays.

### 2. Match Score & Gap Identification
* **Purpose:** Calculates the compatibility index and discovers critical domain gaps.
* **Prompt Strategy:** Comparative prompt criteria instructing the underlying Amazon Bedrock model to flag necessary hard skills, tools, and acronyms absent from the candidate profile.

### 3. Bullet-Point & Professional Summary Optimizer
* **Purpose:** Rewrites weak professional content into targeted, metrics-oriented phrasing.
* **Prompt Strategy:** Enforces strict adherence to formatting structures (e.g., using the Google X-Y-Z formula: *"Accomplished [X] as measured by [Y], by doing [Z]"*) while preventing the model from hallucinating false metrics or fake history.

---

## ✨ Key Features
* **Granular Extraction:** Extracts precise skills, experience, credentials, and core responsibilities from text or supported document uploads.
* **Detailed Gap Analysis:** Provides a clear breakdown of compatibility alongside keyword match evaluation.
* **Tailored AI Adjustments:** Offers targeted revisions for professional summaries, technical skills matrix formats, and experience bullet points.
* **Interactive Editing Interface:** Allows job seekers to test out alternative text variations dynamically in the app workspace.

---

## 🛠️ Tech Stack & Foundations
* **Platform:** [AWS PartyRock](https://partyrock.aws) (No-code generative AI playground)
* **AI Orchestration Framework:** [Amazon Bedrock Foundation Models](https://amazon.com)
* **Core Paradigms:** Prompt Engineering, One-Shot/Few-Shot Conditioning, Multi-Agent Chained Workflows
