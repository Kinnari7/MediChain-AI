# AI-Agents-for-Medical-Diagnostics

A Python project that creates specialized **LLM-based AI agents** to analyze complex medical cases.  
The system integrates insights from different medical specialists to provide comprehensive assessments  
and suggested treatment directions, demonstrating the potential of AI in multidisciplinary medicine.

---

## 🚀 How It Works

I use **three AI agents (GPT-5)**, each specializing in a different aspect of medical analysis.  
A medical report is passed to all agents, which run **in parallel (threading)** and return their findings.  
The outputs are then combined and summarized into **three possible health issues** with reasoning.

### AI Agents

**1. Cardiologist Agent**  
- *Focus*: Detect cardiac issues such as arrhythmias or structural abnormalities.  
- *Recommendations*: Cardiovascular testing, monitoring, and management strategies.  

**2. Psychologist Agent**  
- *Focus*: Identify psychological conditions (e.g., panic disorder, anxiety).  
- *Recommendations*: Therapy, stress management, or medication adjustments.  

**3. Pulmonologist Agent**  
- *Focus*: Assess respiratory causes for symptoms (e.g., asthma, breathing disorders).  
- *Recommendations*: Lung function tests, breathing exercises, respiratory treatments.  

---

## 🔮 Future Enhancements

Planned improvements for upcoming versions include:

- **Specialist Expansion**: Add new agents for Neurology, Endocrinology, Immunology, and other fields.  
- **Live Data Tools**: Incorporate LLM-based tools for **real-time search** and querying structured **medical datasets**.  
- **Advanced Parsing**: Improve handling of complex medical reports with structured outputs (e.g., JSON schema validation).  
- **Automated Testing**: Add evaluation pipelines and smoke-test CI with mocked LLM calls for reproducibility.  
---

