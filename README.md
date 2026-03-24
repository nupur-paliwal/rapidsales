# RapidSales.ai

## Deliverables

| Task | Document | Live Link |
|------|----------|-----------|
| S-1: Chatbot System Prompt (EzeeChatBot / Furniture Retail) | [View HTML](./furniture_chatbot_system_prompt.html) | [Live](https://nupur-paliwal.github.io/rapidsales/furniture_chatbot_system_prompt.html) |
| S-2: Voice Agent Brain (Solar B2C Cold Calls) | [View HTML](./rapidsales_voice_agent_brain.html) | [Live](https://nupur-paliwal.github.io/rapidsales/rapidsales_voice_agent_brain.html) |
| S-3: LLM Evaluation Framework | [View HTML](./rapidsales_eval_framework.html) | [Live](https://nupur-paliwal.github.io/rapidsales/rapidsales_eval_framework.html) |

## Approach

**S-1 (Chatbot):** Structured the system prompt into 6 independently maintainable blocks — persona, scope, tone, constraints, workflows, and escalation. Designed 3 contextually distinct greetings and a 10-message test set including 2 adversarial inputs targeting jailbreak and identity spoofing.

**S-2 (Voice Agent):** Designed the full conversational brain for outbound solar cold calls — two opening script variants, 5 objection branches with exact spoken scripts, a 6-outcome intent detection layer with production signal definitions, a warm handoff protocol with structured CRM context packet, and 3 production failure modes grounded in live voice AI behaviour.

**S-3 (Eval Framework):** Built a 12-metric evaluation framework treating each channel as a distinct system. Designed 3 adversarial synthetic test cases (not happy paths), and a 3-layer drift detection pipeline operable by a lean team with no subjective human bottlenecks in the daily monitoring loop.
