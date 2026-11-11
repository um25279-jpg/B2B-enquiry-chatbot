# B2B-enquiry-chatbot
A  RAG-powered B2B customer enquiry and lead qualification chatbot built using Dify.
# AI-Powered B2B Enquiry Qualification Chatbot

A no-code, RAG-powered B2B customer enquiry and lead qualification chatbot built using Dify.

## 1. Project Overview

This project demonstrates how Generative AI and Retrieval-Augmented Generation (RAG) can be used to automate initial B2B customer interactions.

The chatbot answers customer enquiries using a predefined company knowledge base, understands business requirements, and identifies potential sales opportunities.

## 2. Business Problem

B2B sales teams spend considerable time handling repetitive customer enquiries, answering product-related questions, and identifying qualified leads.

This solution aims to:
- Automate responses to common customer enquiries.
- Provide knowledge-based and context-aware answers.
- Understand customer business requirements.
- Identify and qualify potential B2B leads.

## 3. Technology Stack

| Technology | Purpose |
|---|---|
| Dify | No-code AI workflow development |
| GPT-5 | Language model |
| RAG | Knowledge-based information retrieval |
| Vector Database | Knowledge retrieval |
| Prompt Engineering | Response generation and lead qualification |

## 4. Workflow Architecture

The chatbot follows a Chatflow architecture:

1. **User Input:** Captures customer questions and enquiries.
2. **Knowledge Retrieval:** Searches the uploaded company knowledge base for relevant information.
3. **LLM:** Generates contextual responses using retrieved information.
4. **Answer:** Displays the response to the customer.

## 5. Key Features

- RAG-based customer enquiry handling.
- Knowledge-base-powered responses.
- Context-aware response generation.
- B2B lead qualification using the FIT-NAT framework.
- Follow-up questions to understand customer requirements.
- Avoidance of unsupported company claims and fabricated information.

## 6. Lead Qualification Framework

The chatbot uses FIT-NAT:

- **Fit:** Does the requirement match the company's capabilities?
- **Need:** What problem is the customer trying to solve?
- **Authority:** Is the customer a decision-maker?
- **Timing:** When does the customer need the solution?
- **Ability:** Does the customer have the ability to proceed?

## 7. Testing

The chatbot can be evaluated using scenarios such as:

- Product and service enquiries.
- Pricing-related questions.
- Bulk procurement requirements.
- Unknown questions not covered in the knowledge base.
- Potential B2B business opportunities.

## 8. Future Enhancements

- Automated lead scoring.
- CRM integration.
- Sales team notifications.
- Lead tracking and analytics.
- Integration with business communication platforms.

## 9. Project Files

- `NORTHSTAR BUSINESS SYSTEMS.ifpkg` – Exported Dify application workflow.

## 10. Disclaimer

Northstar Business Systems is a fictional company used for this demonstration project. The knowledge base and chatbot are intended for educational and portfolio purposes.

---

**Built using Dify, GPT-5 and Retrieval-Augmented Generation (RAG).**
