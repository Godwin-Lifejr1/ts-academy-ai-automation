# Module 1 — Topic 1: What is AI?

## Status
In progress

## What is AI?
Artificial Intelligence (AI) is the field of building computer systems that can perform tasks that normally require forms of human intelligence, such as recognizing patterns, understanding language, making predictions, classifying information, generating content, and supporting decisions.

AI is broader than ChatGPT. ChatGPT is one example of a generative AI system.

## Why AI matters in Automation
Traditional automation follows rules that humans explicitly define.

Example:
- If a form is submitted → save the information to Google Sheets.
- If payment is received → send a confirmation email.

AI adds the ability to handle less-structured information and make classifications, predictions, or generate responses.

Example:
Customer message → AI identifies the customer's intent → automation routes the request → response/action is performed.

## AI vs Traditional Automation

| Traditional Automation | AI-powered Automation |
|---|---|
| Mainly follows predefined rules | Can interpret patterns and unstructured inputs |
| Best with predictable processes | Useful when inputs vary |
| Example: copy form data to Sheets | Example: classify a customer's message |
| Logic is explicitly defined | Some behavior comes from a trained model |

## High-level AI pipeline
Data → Learning/Algorithmic Process → Model → Input → Processing → Output

The exact pipeline differs by AI system, but this gives a useful beginner mental model.

## Major AI areas
- Machine Learning
- Deep Learning
- Natural Language Processing (NLP)
- Computer Vision
- Generative AI
- AI Agents

## Important limitation
AI does not automatically mean perfect reasoning or human-like understanding. AI systems can produce incorrect outputs. In automation, outputs should therefore be validated and workflows should include testing, error handling, and appropriate human oversight.

## Practical example: AWAP property enquiry
A customer sends:
"I need a plot of land in Abuja around ₦20 million. Can I inspect it this weekend?"

Possible AI tasks:
1. Identify the customer's intent.
2. Extract location: Abuja.
3. Extract approximate budget: ₦20 million.
4. Identify inspection interest.
5. Return structured information to the automation.

Possible automation tasks:
1. Receive the message.
2. Send the message to the AI service.
3. Store extracted information.
4. Search or route the enquiry.
5. Notify the appropriate realtor.
6. Send a response to the customer.

## Checkpoint
Answer these in your own words:

1. What is AI?
2. What is the difference between AI and traditional automation?
3. Customer form → Google Sheets → email: AI, automation, or both? Why?
4. Customer message → AI classifies → automation executes → response: what is the role of AI and what is the role of automation?

Do not move to Topic 2 until these are answered and reviewed.
