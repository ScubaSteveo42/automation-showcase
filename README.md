# Automation showcase

Real builds from my work on small-business automation, cleaned up for public viewing (demo data, placeholders instead of credentials).

| Folder | What it is |
|---|---|
| [`n8n-lead-followup/`](n8n-lead-followup/) | n8n workflow: a signed post-conversation webhook from a website AI assistant → lead filter → Discord alert → automatic confirmation email → Gmail draft for the personal follow-up |
| [`roi-calculator/`](roi-calculator/) | Single-page calculator that turns a business's own numbers into the yearly cost of slow follow-up and manual admin |
| [`ai-website-assistant/`](ai-website-assistant/) | How a voice + text website assistant is designed: knowledge base, discovery flow, guardrails, and the hand-off to automation |

## How I build
- Around the tools a business already uses (Google Workspace, CRMs, Calendly, Stripe, Discord, Slack).
- Secrets never in code or shared docs; signed webhooks; least-privilege access.
- A test mode before anything is sent to real customers; backups before every change.
- Short screen recordings at each milestone and a written handover.

Steven Girgash · co-founder, Juvra
