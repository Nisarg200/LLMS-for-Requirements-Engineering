# 🚇 LLMs for Requirements Engineering – Metro Ticket Distributor System

## 📌 Overview
This project explores how **Large Language Models (LLMs)** can automate and enhance the **Requirements Engineering (RE)** process for a **Metro Ticket Distributor System**.  
By leveraging multiple LLMs (**LLaMA 3.2, Mistral, Gemini, DeepSeek**) integrated via **Ollama** and external APIs, we designed a pipeline to:

- 📝 Gather requirements from stakeholders  
- 📖 Generate **user stories** adhering to the **INVEST framework**  
- 📊 Prioritize requirements using the **MoSCoW method**  
- ⚖️ Resolve conflicts between functional and non-functional requirements  
- 🧪 Evaluate model outputs using the **RUST Questionnaire**  

---

## 🎯 Objectives
- 🤖 Automate **user story generation** with multiple LLMs  
- 🔍 Compare outputs from different LLMs for **readability, understandability, specificity, and technical accuracy**  
- 🛠️ Demonstrate how AI can assist in **elicitation techniques** and **requirements prioritization**  
- ⚡ Identify model limitations in **acceptance criteria** and **stakeholder analysis**  

---

## 🛠️ Tech Stack
- **LLMs Used**: LLaMA 3.2, Mistral, Gemini, DeepSeek  
- **Integration**: [Ollama](https://ollama.com/) + APIs  
- **Evaluation Frameworks**: INVEST, MoSCoW, RUST  

---

## 📂 Project Pipeline
1. **Requirement Elicitation** – Collect initial system requirements  
2. **User Story Generation** – LLMs generate INVEST-compliant user stories  
3. **Prioritization** – Apply MoSCoW to rank requirements  
4. **Conflict Resolution** – Handle trade-offs between functional & non-functional needs  
5. **Evaluation** – Assess LLM outputs using RUST Questionnaire  

---

## 📊 Example Outputs
- ✅ User Story (INVEST):
  > As a passenger, I want to purchase a ticket via QR code so that I can quickly access the metro without waiting in line.  

- 📌 Prioritization (MoSCoW):  
  - **Must Have**: Ticket purchase, Payment validation  
  - **Should Have**: Multi-language support  
  - **Could Have**: Personalized travel suggestions  
  - **Won’t Have (now)**: AI-powered travel recommendations  

---

## 🚀 Future Work
- 🔔 Add **automated evaluation metrics** beyond RUST  
- 🌐 Extend to **multi-stakeholder environments** (operators, passengers, regulators)  
- 📊 Incorporate **visual dashboards** for requirement traceability  
- 🤝 Compare against **traditional RE techniques** for benchmark accuracy  

---

## 📜 License
This project is released under the **MIT License**.  
Feel free to use, modify, and share with attribution.  

---

## 🙌 Acknowledgements
- Inspired by research in **LLMs for Requirements Engineering**  
- Open-source tools: Ollama, Hugging Face, and various LLM APIs  

