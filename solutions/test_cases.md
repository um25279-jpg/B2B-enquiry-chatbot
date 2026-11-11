# Chatbot Testing & Validation

## Objective

Test the chatbot's ability to retrieve company information, generate accurate responses, understand customer requirements, and qualify potential B2B leads.

## Test Case 1: Product Knowledge Retrieval

**Input:**

What is the difference between Jamf and Scalefusion?

**Expected Behaviour:**
- Retrieve relevant information from the company knowledge base.
- Explain the key differences accurately.
- Avoid unsupported product claims.

**Purpose:** Test RAG retrieval and response accuracy.

## Test Case 2: B2B Enquiry Qualification

**Input:**

We are a company with 200 employees looking to manage our company-owned devices using MDM. How can Northstar Business Systems help us?

**Expected Behaviour:**
- Understand the customer's MDM requirements.
- Explain relevant solutions using the knowledge base.
- Ask relevant follow-up questions.
- Avoid inventing pricing or service commitments.

**Purpose:** Test customer understanding and lead qualification.

## Evaluation Criteria

- Relevance of responses.
- Accuracy of retrieved information.
- Grounding in the knowledge base.
- Understanding of customer requirements.
- Quality of follow-up questions.

## Project Limitations

- Uses a fictional company knowledge base.
- No live CRM integration.
- Does not generate actual quotations.
- Does not confirm real-time product availability.
