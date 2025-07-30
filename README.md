# AI-Chatbot-for-Admission-process-using-cloud-technology

# Admission_Assistant: College Admission Chatbot using IBM Watson Assistant

**Admission_Assistant** is an AI-powered, interactive chatbot built with IBM Watson Assistant on IBM Cloud. Designed to help prospective students, it provides instant answers to common admission queries, lists available courses, checks eligibility, and facilitates admission lead capture — all through a conversational web interface.

## 🚀 Features

- **Conversational AI Interface:** Natural, friendly Q&A with users about admissions.
- **Course Listings:** Dynamically provides available course names and descriptions.
- **Eligibility Checks:** Converses with candidates to check if they meet enrollment criteria.
- **Admission Lead Capture:** Collects applicant details for admissions follow-up.

## 🛠️ Tech Stack

- IBM Watson Assistant (Lite Plan)
- IBM Cloud
- **Frontend:** IBM Watson Webchat UI

## 📝 Implementation Steps

1. **Set up Watson Assistant**: Provisioned the Assistant on IBM Cloud (Lite plan).
2. **Build Conversation Actions**: Made dialog flows for greetings, queries, and eligibility checks.
3. **Define Actions and Variables**: Captured fields like name, chosen course, contact number.
4. **Create Course Info Flow**: Listed courses (e.g., Data Science, Cloud Computing, Cyber Security, Web Development).
5. **Enrollment Flow**: Checked eligibility, requested contact info, confirmed admissions callback.
6. **Test in Watson Preview**: Ensured smooth, correct conversational interactions.
7. **Lead Management Automation**: Collected and stored application leads for follow-up.

## 💬 Sample Conversation

```
User: Hi
Bot: Hello! Welcome to Admission_Assistant. How may I assist you today?

User: What courses are available?
Bot: We offer Data Science, Cloud Computing, Cyber Security, and Web Development. Please select a course to know more.

User: I want to enroll in Data Science
Bot: Certainly! Here are the eligibility criteria...
   - High school diploma or equivalent
   - Minimum GPA: 3.0 (on a 4.0 scale)
   - Personal statement, etc.

User: Yes
Bot: Great! Please provide your contact number.

User: 9876543210
Bot: Our admissions executive will promptly call you within 24 hours.
```

## 📦 How to Run / Demo

1. **Watson Preview:** Interact in the IBM Watson Assistant preview panel.
2. **Web Integration:** Deploy on your website using the Watson Webchat UI.

## ⚡ Skills Demonstrated

- IBM Watson Assistant design & configuration
- User flow design for conversational interfaces
- Automation of lead capture
- Cloud deployment and integration

*This repository demonstrates the practical application of AI-driven chatbots for streamlining student admissions, from greeting to course enrollment.*
