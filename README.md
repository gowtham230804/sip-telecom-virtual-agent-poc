elecom & SIP Infrastructure Virtual Agent (PoC)
Overview
This repository contains the exported JSON architecture for a conversational AI proof-of-concept (PoC) built using Google Cloud Dialogflow ES. The virtual agent is designed to automate tier-1 IT infrastructure support by diagnosing and resolving common Session Initiation Protocol (SIP) routing and authentication failures.

Technology Stack
Conversational AI Platform: Dialogflow ES

Architecture: Intent Mapping, Entity Extraction, NLP Training

Domain: Telecom Networking, SIP Protocol, Kubernetes (CNF)

Core Intents Engineered
The agent's Natural Language Understanding (NLU) model is trained to classify and respond to the following network escalations:

SIP_Error_401: Diagnoses unauthorized access and credential expiration.

SIP_Error_408: Troubleshoots request timeouts and blocked port 5060 firewall rules.

Check_Node_Status: Directs users to verify Kubernetes CNF pod health.

Escalate_To_Human: Gracefully handles intent fallbacks by simulating a Tier-2 JIRA ticket escalation.
