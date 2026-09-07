# AI Message Classifier (n8n + Gemini)

An automation workflow built in n8n that uses Google's Gemini AI to classify 
incoming customer messages as "Urgent" or "Normal" — designed to help support 
teams prioritize responses automatically.

## How it works
1. A trigger receives an incoming message
2. The message is sent to Gemini AI with a classification prompt
3. The AI returns a one-word classification (Urgent/Normal)

## Tools used
- n8n (workflow automation)
- Google Gemini API (AI classification)

## Status
Fully functional: receives live messages via webhook, classifies urgency using Gemini AI, 
and returns the result automatically.
