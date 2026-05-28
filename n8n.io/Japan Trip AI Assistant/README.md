# Japan Trip AI Assistant — n8n Version

## What It Does
No-code Agentic AI travel planning 
workflow built on n8n. User sends 
travel preferences via webhook — 
Groq AI generates a complete 
personalised day by day trip plan 
and delivers it automatically to Gmail.

## How It Works
1. User sends travel preferences
   via webhook (Hoppscotch)
2. Groq AI processes preferences
3. Complete trip plan generated:
   → Day by day itinerary
   → Flight recommendations
   → Hotel recommendations
   → Food recommendations
   → Budget breakdown
4. Full plan delivered to Gmail!

## Workflow
[Webhook] → [Basic LLM Chain] → [Gmail]
                  ↓
            [Groq Chat Model]

## Tools Used
- n8n (workflow automation)
- Groq AI (llama-3.3-70b-versatile)
- Gmail (email delivery)
- Hoppscotch (webhook testing)

## Sample Input
{
  "budget": "2000 euros",
  "duration": "7 days",
  "food": "chicken and eggs only",
  "walking": "2km per day",
  "interests": "peaceful places",
  "travellers": "2 adults"
}

## Key Difference from Make.com Version
→ Completely free — no credit limits
→ Groq AI instead of Make AI Toolkit
→ Better error handling
→ More control over workflow

## Demo Video
https://www.youtube.com/watch?v=K-jZ2Ytb66g

## Built By
Vamsi Krishna Gali
MSc Computing Science | Griffith College Dublin
Goal: AI Project Manager in Ireland
