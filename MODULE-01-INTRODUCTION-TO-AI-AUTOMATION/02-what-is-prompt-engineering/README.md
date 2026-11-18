# Module 1 — Topic 2: What is Prompt Engineering?

## Definition
A prompt is the instruction or input given to an AI system to produce a desired result.

Prompt engineering is the process of designing and refining AI instructions so the output is useful, accurate, consistent, and appropriate for the task.

## Good prompt anatomy
- Role — what the AI should act as
- Task — what it must do
- Context — information it needs
- Constraints — what it must or must not do
- Output format — how the result should be returned

## Example
Real-estate enquiry extraction:
You are a real estate inquiry extraction assistant. Read the customer message and extract location, area, budget, date of inspection, inspection request, number of plots and amount. If information does not exist, return null. Do not invent information.

A stronger automation-ready version can require exact JSON fields:
- location
- area
- budget
- amount
- number_of_plots
- inspection_request
- inspection_date
- inspection_time

## AI + automation
AI output should be structured before downstream automation uses it.

Input → Prompt → AI → Structured JSON → Validation → IF/SWITCH → CRM/Sheets/Email/WhatsApp/API

## Key lesson
AI output is not automatically reliable. Real workflows should validate important AI-generated data before acting on it.

## Checkpoint
Passed — user demonstrated understanding by designing a prompt for extracting structured property enquiry information.
