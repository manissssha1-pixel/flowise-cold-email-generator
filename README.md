# AI Cold Email Generator for Job Applications

**AI Cold Email Generator** is an intelligent Flowise-based project that automates the creation of professional emails for job applications. By leveraging Large Language Models (LLMs) and structured prompts, the system generates personalized, context-aware emails at scale, saving time for job seekers and recruiters alike.

---

## Features

- Automatically generate professional email drafts for job applications
- Load and process multiple input files (job descriptions, resumes, or templates)
- Customizable prompts to match tone, style, and format requirements
- Outputs structured JSON for easy integration with email clients or automation tools
- Supports batch processing with LLM-powered recommendations

---

## Flowise Project Architecture

This project uses **five key Flowise nodes**:

1. **File Loader** – Loads resumes, job descriptions, or email templates  
2. **ChatOpenAI** – Generates AI-powered email content  
3. **LLMChain** – Chains prompts for sequential reasoning and output refinement  
4. **Prompt Template** – Structures prompts to ensure professional, consistent outputs  
5. **Structured Output Parser** – Converts AI output to structured JSON  

---

## How It Works

1. **File Loader** ingests input data (resumes, job descriptions, templates)  
2. **Prompt Template** formats inputs for the AI  
3. **LLMChain** processes prompts and generates outputs  
4. **ChatOpenAI** creates professional, human-readable emails  
5. **Structured Output Parser** outputs JSON with metadata like recipient, subject, and body  

---

## Tech Stack

- **Flowise** – Node-based workflow orchestration  
- **OpenAI / ChatGPT** – LLM for AI email generation  
- **Structured Output Parser** – Converts AI outputs to JSON  
- **Prompt Engineering** – Ensures consistency, personalization, and tone  

---

## Installation & Setup

Follow these steps to set up and run the project:

1. **Clone the repository:**

```bash
git clone https://github.com/manissssha1-pixel/flowise-cold-email-generator.git
