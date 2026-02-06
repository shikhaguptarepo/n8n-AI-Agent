# n8n-AI-Agent
Beginner's level: Creation of AI agent using n8n

**Tool Requirements**
Most of the hands-on work will happen in n8n, but we’ll rely on a few additional tools to power the agent and let it interact with a few other services.

Here’s a quick overview of what you’ll need:

n8n: Our main tool
This is where we’ll build the chatbot workflows—no coding required. You can use either the hosted (cloud) version or run it locally on-premises.

If you’re new to n8n, I recommend starting with the hosted version, which comes with a free 14-day trial.

Sign up: https://app.n8n.cloud/register

Large language model (LLM)
The LLM powers both responses and vector embedding generation. n8n supports several LLMs out of the box. You’ll need an API key to connect one.

If you don’t have an API key yet, I recommend Gemini. It’s easy to set up, doesn’t require a credit card, and offers a generous free tier.

Gemini: https://aistudio.google.com/apikey 
Examples of other supported LLMs:

OpenAI: Get API key, minimal charges to use it.
Claude (Anthropic): Console 
Ollama (local models): Download

Gmail
To enable your agent to draft and send emails, you’ll need to connect it to an email service provider. You can either use a custom SMTP server or simply connect it to one of the email integrations supported by n8n, such as Gmail—which is the option I demonstrate in the course.

If you choose Gmail, I strongly recommend creating a separate Google account for this purpose. That way, you’ll avoid any interference with your personal or work emails and keep everything isolated and secure while learning.
