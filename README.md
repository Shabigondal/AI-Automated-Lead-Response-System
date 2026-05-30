# AI-Driven Automated Lead Response System

An end-to-end enterprise-grade automation workflow built on **Make.com** that instantly processes inbound leads from Google Forms, uses **AI** to analyze and draft a highly professional context-aware response, logs everything into **Google Sheets**, and automatically dispatches the response via **Gmail/Email** to the client.

---

## System Architecture & Workflow

The system is fully autonomous and operates on a 4-stage event-driven architecture:

1. **Trigger (Google Forms):** Captures real-time customer/client inquiries (Name, Email, Message).
2. **Brain (Make AI Assistant):** Processes the raw unstructured data and executes prompt engineering to generate a professional, context-rich response tailored to the user's inquiry.
3. **Database (Google Sheets):** Structured logging of the lead information along with the AI-generated response into specified columns for CRM tracking.
4. **Action (Gmail/Email SMTP):** Automatically dispatches a beautifully formatted dynamic email back to the lead's email address with zero human intervention.

---

## Visual Blueprint

Below is the conceptual mapping of how the system executes on auto-pilot:

- [x] Inbound Form Submission ➡️ [x] AI Context Analysis ➡️ [x] CRM Sheet Logging ➡️ [x] Instant Email Delivery

---

##  Key Features

* **Zero-Cost AI Processing:** Utilizes Make's built-in AI tools to bypass expensive OpenAI API token limits for testing.
* **Dynamic Mapping:** Automatically extracts JSON array parameters from standard form payloads to separate clean contact variables.
* **Auto-Pilot Operations:** Completely hands-free workflow that operates 24/7/365 without needing a local server.

---

## How to Deploy This Blueprint

1. Create a free account on [Make.com](https://www.make.com).
2. Create a new Scenario.
3. Click the three dots `...` (More) at the bottom toolbar and select **Import Blueprint**.
4. Upload the `AI-Automated-Lead-Response-System.json` file from this repository.
5. Re-authenticate your Google Forms, Google Sheets, and Gmail connections.
6. Turn the scheduling switch **ON**.


<img width="1024" height="651" alt="image" src="https://github.com/user-attachments/assets/56b513be-82fd-4cad-bc83-598e43287f22" />

Google Sheets with the logs
<img width="1024" height="651" alt="image" src="https://github.com/user-attachments/assets/9522b84d-8292-405e-af59-0f3c4402c436" />



Professional Gmail generated and sent to the user
<img width="1024" height="651" alt="image" src="https://github.com/user-attachments/assets/20db4fa5-fa50-4047-81e5-5bbd19aa9265" />





