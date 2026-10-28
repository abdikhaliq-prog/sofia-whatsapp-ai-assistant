# Sofia: AI WhatsApp assistant for clinics

Sofia answers patient messages on WhatsApp, including outside business hours, and hands sensitive questions to a human. I designed, built and run it solo, end to end.

## What it does
- Answers common patient questions on WhatsApp
- Sends a booking link when the patient is ready
- Follows up automatically with people who stop replying (24 hours, 3 days, 7 days)
- Hands sensitive questions to the clinic's human team
- Always discloses that it is an AI, and never gives medical advice

## Stack
- n8n (self-hosted) for workflows
- Claude API for conversation
- PostgreSQL for state and data
- WhatsApp Cloud API for messaging
- Stripe for billing: checkout, renewals, failed payments, cancellations
- Uptime monitoring and alerts

## How it is tested
Structured live tests before every release: answer accuracy, AI disclosure, no medical advice, and human handoff.

## Demo
- Video: https://www.loom.com/share/2c54cb5658fd4e89baa3a8798e2e5abf
- Site: https://khaliqsystems.com

## About
Built by Abdikhaliq Ali Hussein, Sao Paulo, Brazil. The source is private because it contains client configuration. I am happy to walk through the design.
