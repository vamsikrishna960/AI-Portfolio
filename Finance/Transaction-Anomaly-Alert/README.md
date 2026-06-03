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

## Demo Video
[Watch Live Demo](YOUR YOUTUBE URL)

## Built By
Vamsi Krishna Gali
MSc Computing Science | Griffith College Dublin
