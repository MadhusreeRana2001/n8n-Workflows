# n8n Workflows Collection

This repository contains a set of practical n8n workflows demonstrating automation using Google Sheets, Gmail, LLMs, and custom logic with Python nodes.

---

## Workflows Included

### 1. Advanced Nodes

* Trigger: Manual
* Fetches data from Google Sheets
* Uses Python Code nodes to:

  * Calculate total values
  * Generate descriptive fields
* Demonstrates parallel execution and data transformation

---

### 2. Chatbot

* Trigger: Chat message
* Uses Google Gemini model
* Maintains short-term memory (context window)
* Responds in both English and Bengali

---

### 3. Gmail Draft Creator

* Trigger: New email in Gmail
* Uses AI Agent to:

  * Analyze incoming email
  * Generate a contextual reply
* Automatically creates a draft in the same thread

---

### 4. Google Sheets Workflow

* Trigger: Manual
* Reads data from multiple Google Sheets
* Applies:

  * Filters and conditional logic (If nodes)
  * Data transformation (Set nodes)
  * Merge operations (Merge Nodes: Append & Combine)
* Demonstrates complex data pipelines

---

### 5. n8n Form Trigger Workflow

* Trigger: Form submission
* Processes comma-separated URLs
* Steps:

  * Cleans and splits input
  * Extracts company names using Python
  * Appends structured data into Google Sheets

---

## Requirements

* n8n (self-hosted or cloud)
* Google Sheets OAuth credentials
* Gmail OAuth credentials
* Google Gemini API key (for AI workflows)

---

## Steps

1. Import the JSON workflow files into n8n
2. Configure credentials (Google Sheets, Gmail, Gemini)
3. Activate the workflows
4. Test using manual execution or triggers

---

## Key Concepts Demonstrated

* AI-powered automation using Google Gemini model
* Data transformation using Set and Code nodes
* Workflow branching using If and Filter nodes
* Data merging and aggregation
* Trigger-based automation (Manual, Chat, Gmail, Form)

---

## Notes

* Ensure all credentials are properly configured before running workflows
* Modify sheet names and field mappings
* AI outputs may vary depending on prompt and model behavior

---

- *Version: 1.0*
- *Last updated: April 2026*
