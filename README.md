### Hi, I'm Luiz

Computer Engineering student in Brazil. I build AI automation with n8n and LLMs, and I'm working toward AI security: how LLM systems fail, and how to test them.

#### Projects

**[AI Ticket Triage with n8n](https://github.com/LuizStocco520/n8n-ai-ticket-triage)**: classifies IT support tickets with an LLM, logs them to Google Sheets, emails an alert for high-urgency tickets and reports its own failures. Built with n8n, Groq (gpt-oss-120b), Google Sheets and Gmail.

- Evaluated on 20 labeled tickets, 3 runs per prompt version. Final prompt: category right in 60 of 60 answers, urgency in 58 of 60.
- Security rules in the prompt: phishing is high urgency even if nobody clicked, and replies to access requests may not promise an unlock before identity is confirmed. A person reviews every reply, and the test set includes a prompt-injection ticket.

#### Courses

n8n Academy, Foundations track (October 2026):
- N8N101 Essentials: Your First Workflows
- N8N102 Integrations: APIs & Connected Workflows
- N8N103 In Practice: AI, Testing & Best Practices

#### Languages

Portuguese (native) · English (fluent)
