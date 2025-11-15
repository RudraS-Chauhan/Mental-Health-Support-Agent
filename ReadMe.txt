# Mental Health Support Agent

**An empathetic AI agent system that offers emotional support, coping strategies, and mental health resource guidance for users experiencing stress, anxiety, or loneliness.**

---

## Problem Statement

Mental health challenges such as anxiety, stress, and loneliness affect millions globally. Unfortunately, timely access to support and resources can be limited due to stigma, lack of awareness, or insufficient healthcare infrastructure.

Our AI agent system aims to bridge this gap by providing empathetic conversational support, offering coping mechanisms, and guiding users to professional help when needed — all through a safe, multi-agent collaboration framework.

---

## Why Agents?

Mental health support requires understanding nuanced emotional cues, reasoning about user needs, and dynamically providing appropriate guidance or resources.  

Using multiple specialized agents allows us to:  
- Detect emotional tone and sentiment effectively.  
- Plan personalized coping strategies based on user context.  
- Safely recommend resources and ensure responses respect ethical guardrails.  

This modular approach increases flexibility, safety, and transparency, making AI agents the ideal solution.

---

## What We Created

Our system architecture includes:  

- **Supervisor Agent:** Oversees user interaction, breaks down tasks, and routes to sub-agents.  
- **Sentiment Analysis Agent:** Detects emotional tone and severity of distress.  
- **Coping Strategy Agent:** Provides personalized mental wellness tips and exercises.  
- **Resource Recommendation Agent:** Suggests professional helplines, websites, and emergency contacts.  
- **Safety Validator Agent:** Ensures safe and responsible responses, avoiding harmful advice.  

![Architecture Diagram](./docs/architecture.png)  
*(Diagram shows data flow between agents and user interaction)*

---

## Demo

**Example Interaction:**  

User: "I'm feeling really anxious and overwhelmed lately."  
Agent Flow:  
- Supervisor routes input to Sentiment Analysis Agent → detects high anxiety.  
- Coping Strategy Agent recommends breathing exercises and mindfulness.  
- Resource Recommendation Agent provides links to trusted mental health helplines.  
- Safety Validator ensures all suggestions are appropriate and empathetic.  

Output:  
*"I’m sorry you’re feeling this way. Have you tried deep breathing exercises? Here are some resources that might help: [links]. Remember, you’re not alone."*

---

## The Build

- **Language:** Python  
- **Models:** Gemini (main model powering agents)  
- **Frameworks:** LangChain for multi-agent orchestration  
- **Tools:** Sentiment analysis APIs, web search for resources, schema validation  
- **Deployment:** (Optional) Agent Engine or Cloud Run (deployment steps documented)  

Key concepts applied:  
- Multi-agent orchestration  
- Sentiment detection and reasoning  
- Tool usage (web search, API calls)  
- Safety guardrails and output validation  

---

## Setup & Run Instructions

1. Clone repo:  
   ```bash
   git clone https://github.com/yourusername/mental-health-support-agent.git
   cd mental-health-support-agent
