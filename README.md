![Architecture Diagram](architecture.png)

# secure-ai-banking-architecture

Project Overview
I designed this architecture to show how a bank can safely use AI. It ensures that a customer can ask questions about their account while their private data stays completely protected.

How it works. 
1. The Security Proxy (The Filter)
This is the brain of the setup. It does two things
* PII Masking: hides customer's name and ID number so the AI never sees private info.
* Threat Detetion: checks for "bad words" and hacking attempts to keep the system safe.

2. The AI Engine.
   The AI recieves cleaned data, understands the request and asks the database for the answer using Secure Query.

3. The Bank Vault (The data).
   The bank's data is locked behind a Strict Access Control wall. Only authoriauthorized requests from the AI can get through.

Skills Demonstrated
* System Architecture (designed in Lucidchart)
* Cyberseurity Principles (Zero Trust & PII Masking)
* Data privacy & Compliance
