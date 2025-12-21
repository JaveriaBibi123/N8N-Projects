HR Recruitment Automation using n8n
Overview

This project automates the HR recruitment process using n8n, integrating AI to parse and evaluate resumes received via email. The workflow streamlines candidate screening by automatically filtering applicants, sending email responses, and maintaining structured candidate data in Google Sheets.

Key Features

Automated Gmail Trigger: Detects incoming emails with attachments labeled as “CV” or “Resume.”

AI-Powered Resume Parsing: Uses OpenAI to extract and analyze candidate details such as name, email, education, skills, and experience.

OpenAI Embeddings + Pinecone Integration: Converts resume text into vector embeddings and stores them in Pinecone for efficient text handling.

Qualification Filtering: Automatically checks if candidates meet education and experience requirements.

Automated Email Response: Sends acceptance or rejection emails based on AI evaluation results.

Google Sheets Logging: Stores all extracted data and decision status for HR reference.

Workflow Steps

Trigger: Gmail node monitors the HR inbox for new emails containing “CV” or “Resume.”

Resume Processing: The email and attachment are sent to Pinecone Vector Store for text vectorization.

AI Evaluation: OpenAI analyzes the resume and checks:

Education: Bachelor’s in Software Engineering or any Finance degree

Experience: Minimum 1 year

Decision:

Application sent for further processing — if requirements are met

Rejected — if requirements are not met

Automated Email: Sends an acceptance or rejection message to the candidate.

Data Logging: Candidate details and status are appended to Google Sheets for HR tracking.

Tech Stack

n8n – Workflow Automation Platform

OpenAI API – Resume parsing and qualification logic

Pinecone Vector Store – Text embedding and storage

Gmail API – Email monitoring and communication

Google Sheets API – Data logging and visualization

Skills & Tools Used

n8n Workflow Automation

OpenAI Embeddings

Pinecone Vector Database

Google Sheets Integration

Gmail Automation

HR Process Optimization

Outcome

This automation streamlines the entire hiring process — from email detection to candidate evaluation and response — saving HR teams time, minimizing manual errors, and improving hiring efficiency.