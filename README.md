# GenAI in Military Decisions: Risks and Ethics Audit

## Overview
This project is an audit of Claude Sonnet 4.6 to test if it follows the Law of Armed Conflict (LOAC) in military scenarios. We tested the model using 66 custom prompts across use cases like autonomous drones and battle assistants.

## Files in this Repository
* `CSC 659 859 Spring 2026 - Team 4 – Team project final report.docx.pdf`: The final project report ("CSC 659 859 Spring 2026 - Team 4 – Team project final report.docx.pdf") with our complete findings.
* `prompts and response data.csv`: The data sheet (`prompts and response data.csv`) containing the prompts, model responses, and our manual scoring.

## Methodology & Results
We used a blind-test approach with a two-round evaluation process:
* **Round 1:** Claude Opus 4.7 acted as an automated LLM judge.
* **Round 2:** Human reviewers (our team) manually scored the responses to act as ground truth.
* We calculated F1 scores by counting the true positives, false positives, true negatives, and false negatives from the dataset. 
* **Results:** The model had a 19.7% safety-filter block rate without context. When it did give a substantive response, it had a 100% compliance rate. The LLM judge and human reviewers had perfect agreement (F1 score of 1.00).

## My Contributions
* Came up with the initial idea to evaluate GenAI in military applications.
* Researched and wrote the Motivation, Problem Description, and GenAI Application sections of the final report.
* Used Gemini Pro to engineer 15 of the testing prompts based on LOAC principles.
* Participated in the manual human evaluation phase to score the model's responses.
