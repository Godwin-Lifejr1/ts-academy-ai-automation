# Module 1 — Topic 5: Overview of Automation Platforms

## What is an automation platform?
Software that helps connect applications and services and orchestrate automated workflows.

It can manage triggers, actions, logic, data movement, integrations, authentication, scheduling, transformations, and execution.

Basic architecture:
Trigger → Processing → Logic → Action → Result

## Platform comparison

| Platform | Style | Strengths | Watch out for |
|---|---|---|---|
| Zapier | No-code | Easy start, large app library, quick simple workflows | Cost can increase as volume grows |
| Make | No-code, visual canvas | Strong branching and data control, often economical at volume | More to learn initially |
| n8n | Low-code, fair-code license | Self-host or cloud, APIs, custom logic, AI/agent capabilities | Requires more technical comfort, especially when self-hosted |
| Power Automate | Microsoft ecosystem | Natural fit for Microsoft 365 organisations | Less appealing outside Microsoft-heavy environments |
| UiPath | Enterprise RPA | Software robots, desktop and legacy-system automation at scale | Heavier setup and aimed more at large organisations |

## Mental models
- Zapier → quick, simple app connections
- Make → visual control over more complex workflows
- n8n → visual automation plus technical control
- Power Automate → Microsoft ecosystem automation
- UiPath → enterprise software robots/RPA

## No-code vs low-code
No-code: workflows are intended to be built without writing code.
Low-code: workflows can be built visually, with code available when custom or advanced behaviour is needed.

## Key principle
Choose a platform based on the problem, requirements, complexity, ecosystem, cost, scalability, and technical needs — not simply because a platform is popular.

## Practical example
A fictional e-commerce company, SwiftCart:
New order → check payment → if successful notify warehouse → if failed notify customer.

This deterministic workflow does not require AI.

## Checkpoint
Passed — 9/10. User correctly explained automation platforms, why businesses use them, the Zapier/Make/n8n distinction, no-code vs low-code, AI's role, and why a simple payment-routing workflow does not require AI.
