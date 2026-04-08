MTN MoMo API — Beginner's Guide

A concise, developer-friendly guide to integrating the MTN Mobile Money (MoMo) API
into your application. Covers sandbox setup, authentication, collections,
disbursements, error handling, and going live.

What's Inside

Getting Started
Create a developer account and get your API keys 
Authentication
3-step OAuth flow to obtain a Bearer token 
Collections
Request payments from customers 
Disbursements
Send money to recipients 
Code Examples
Working Node.js snippets
Error Handling
Common errors and fixes 
Going Live
Steps to move from sandbox to production 

Prerequisites

- Basic knowledge of REST APIs and HTTP
- An account on [momodeveloper.mtn.com](https://momodeveloper.mtn.com)
- Node.js or Python (for the code examples)

 Quick Start

1. Sign up at the [MTN MoMo Developer Portal](https://momodeveloper.mtn.com)
2. Subscribe to a sandbox product and grab your **Subscription Key**
3. Follow the 3-step auth flow to get an access token
4. Make your first `POST /collection/v1_0/requesttopay` call

 Resources

-  [Official API Docs](https://momodeveloper.mtn.com/api-documentation)
-  [Sandbox Testing Guide](https://momodeveloper.mtn.com/testing)
-  [Developer Forum](https://momodeveloper.mtn.com/forums)

> This guide targets the **sandbox environment**. No real money is moved during testing.
