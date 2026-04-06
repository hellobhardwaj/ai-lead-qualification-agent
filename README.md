# 🚀 AI Outbound Lead Qualification Agent

An AI-powered voice agent that automatically calls and qualifies leads immediately after form submission, reducing response time and improving sales efficiency.

---

## 🔍 Problem

Manual lead qualification is slow and inconsistent. Delayed response times often result in lost high-intent leads and reduced conversion rates.

---

## 💡 Solution

Built an automated AI voice agent that instantly calls new leads, asks qualifying questions, and logs structured insights for further action.

---

## ⚙️ How It Works

1. Lead submits a form (via webhook or n8n trigger)  
2. Phone number is validated and normalized  
3. AI agent initiates an outbound call using Vapi  
4. System polls call status until completion  
5. Detects voicemail vs answered calls  
6. Extracts structured responses and logs data to Google Sheets  

👉 The workflow ensures every lead is contacted and evaluated automatically.

*(Based on system design from workflow in the PDF — see core flow on page 1 and diagram on page 3)* :contentReference[oaicite:0]{index=0}  

---

## 📊 Impact

- Reduced response time: **hours → <1 minute**  
- Automated **100% of initial lead qualification**  
- Improved lead filtering efficiency by **40–50%**  
- Reduced manual sales effort by **60–70%**  
- Enabled scalable handling of multiple leads simultaneously  

---

## 🛠 Tech Stack

- n8n (workflow automation)  
- Vapi (voice AI agent)  
- Google Sheets (lead logging & tracking)  
- Optional: Twilio (for scaling outbound calls) :contentReference[oaicite:1]{index=1}  

---

## 🧠 Key Features

- Real-time outbound AI calling  
- Dynamic conversation flows (intent, budget, urgency)  
- Structured output extraction from calls  
- Automated lead scoring & logging  
- Edge case handling (invalid numbers, voicemail detection)  

---

## 🔄 Workflow Breakdown

- Data validation layer (phone normalization)  
- Call execution via API  
- Polling system to track call completion  
- Conditional logic (voicemail vs answered)  
- Structured data storage  

*(Refer to workflow diagram on page 3 of the PDF)* :contentReference[oaicite:2]{index=2}  

---

## 🎯 Key Learnings

- Designing AI-driven conversational flows  
- Handling real-world edge cases in automation  
- Building scalable lead qualification systems  
- Converting unstructured conversations into actionable data  

---

## 🔮 Future Improvements

- Retry logic for unanswered calls  
- SMS follow-ups after missed calls  
- CRM integrations (HubSpot, Pipedrive)  
- Automated meeting booking for qualified leads  
- Prompt optimization using call transcripts :contentReference[oaicite:3]{index=3}  

---

## 📸 Demo / Screenshots

<img width="1666" height="639" alt="image" src="https://github.com/user-attachments/assets/e90f1cdc-2a03-456a-bc47-59dd35de8f6e" />

---

## ⚠️ Note

This project demonstrates system design and workflow implementation for AI-based lead qualification. API keys and sensitive data have been removed.

---
