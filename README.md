
# Business Intelligence WhatsApp AI Assistant 🚀

An autonomous, multi-session WhatsApp AI assistant designed to empower entrepreneurs and business business managers. This production backend automates real-time, context-aware customer support interactions, allowing business owners to handle customer inquiries instantly and effortlessly.

Developed by **Gloire Ahadi**, a Mechanical Engineer specializing in Machine Learning.

---

## 🛠️ System Architecture & Technology Stack

The platform functions by establishing a secure cloud-to-local communication infrastructure pipeline:

*   **Core Engine:** `Gemini 2.5 Flash` via the new official Google GenAI SDK.
*   **Context Token Acquisition:** Cryptographic API access keys generated securely through **Google AI Studio**.
*   **Communication Gateway:** **Twilio WhatsApp Business API Proxy Sandbox** for reliable network routing.
*   **Backend Server Environment:** Lightweight event-driven **Flask REST API** framework executing locally.
*   **Secure Public Network Tunnel:** **Ngrok HTTP Proxy Engine** to expose the local Flask development port `5000` via a secure, public webhook URL (`https://...ngrok-free.dev/whatsapp`).

---

## 🧠 Behavior & Embedded System Instructions

The backend instantiates independent state-memory isolated sessions (`ai.chats.create`) tracked uniquely per incoming customer phone number. The underlying Large Language Model operates under strict runtime system instructions embedded directly into the initialization layer:

1.  **Identity Signature:** Every introductory interaction signs off with the official developer metadata disclosure: *"I am an LLM developed by Gloire Ahadi, a Mechanical Engineer."*
2.  **Conciseness Constraints:** Responses are algorithmically constrained to a **maximum ceiling of 10 sentences** to maintain professional brevity and cost efficiency.

---

## Source Code 

🚀 **[View the Core Python Source Code Here](./AI_assistant_WhatsApp-Copy1.ipynb)**

## 📺 Live Prototype Demonstration

See the WhatsApp Business AI Assistant in action! Click the link below to watch the live video demonstration of the prototype responding to customer inquiries:

📱 **[Watch the Live WhatsApp Prototype on YouTube](https://youtube.com/shorts/TNiN0MvUbM4?si=aH8kBHtdt4vAOO-g)**

## 🚀 Step-by-Step Deployment Blueprint

### 1. Environment Setup
Clone the repository and install the official framework requirements:
```bash
pip install flask twilio google-genai
