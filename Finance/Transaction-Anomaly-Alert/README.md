# Transaction Anomaly Alert System — AML Screening

## What It Does
An AI-powered Anti-Money Laundering (AML)
transaction screening prototype built on n8n.

## Workflow
[Manual Trigger] → [Google Sheets] →
[Groq AI - AML Analysis] → [Google Sheets Update]

## Red Flags Detected
- Large transaction amounts (EUR 50k+)
- High-risk jurisdictions
- Very new accounts (under 30 days)
- High transaction frequency
- New account + large amount combination

## AI Output
- Risk Level: LOW / MEDIUM / HIGH
- Reason: clear explanation per transaction

## Tools Used
- n8n | Groq AI | Google Sheets

## Industry Relevance
Demonstrates AI-supported financial compliance,
relevant to banking, fintech, and AML teams
in Ireland's financial services sector.

## 📋 Product Requirements Document

This project includes a full PRD covering 
problem statement, objectives, user personas, 
functional and non-functional requirements, 
risks, EU AI Act compliance, and success criteria.

📥 [Read the PRD (PDF)](./AML_PRD_Vamsi_Krishna.pdf)

## Demo Video
[Watch Live Demo](https://youtu.be/PvuzUavQc8c)

## Built By
Vamsi Krishna Gali
MSc Computing Science | Griffith College Dublin
