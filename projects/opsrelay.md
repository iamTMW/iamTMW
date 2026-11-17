# OpsRelay - AI-Powered Incident Response

**Hackathon team project | November 2026**

[Original source repository](https://github.com/faizm10/opsrelay-agent) · [Live team dashboard](https://opsrelay-dashboard.vercel.app) · [My GitHub profile](https://github.com/iamTMW)

## The problem

A service can appear online while a critical customer workflow is failing. OpsRelay helps teams detect these failures, investigate evidence from service probes and logs, recommend fixes, and track work affected by outages.

The team project connects uptime monitoring, an AI-assisted diagnosis and repair pipeline, GitHub pull requests for human review, and MongoDB-backed incident/recovery state. The agent does not automatically merge fixes.

## What I built

My contributions focused on the runnable applications and monitoring experience used to demonstrate and detect operational problems.

- **NovaMart:** Built a shopping demo application with a Next.js storefront, FastAPI backend, checkout flows, functional health probes, and automated tests.
- **NovaConnect:** Built a real-time messaging demo with a Next.js interface, FastAPI backend, WebSockets, message persistence, delivery-status handling, and automated tests.
- **OpsRelay uptime monitoring:** Implemented uptime-monitoring functionality and a status dashboard that surface service health and incidents for the wider team's investigation workflow.

These components were developed as part of a collaborative hackathon project, not as a solo product.

## Verified merged contributions

| Pull request | Work |
| --- | --- |
| [#2 - Build NovaMart shopping app with checkout and tests](https://github.com/faizm10/opsrelay-agent/pull/2) | Shopping service and tests |
| [#9 - Build NovaConnect messaging app with tests and bug scenarios](https://github.com/faizm10/opsrelay-agent/pull/9) | Real-time messaging, failure scenarios, functional probes |
| [#13 - Add OpsRelay uptime monitoring and status dashboard](https://github.com/faizm10/opsrelay-agent/pull/13) | Service monitoring and dashboard |

## Technology & engineering practices

**Frontend:** Next.js, React, TypeScript  
**Backend:** Python, FastAPI, WebSockets  
**Team platform:** MongoDB Atlas, GitHub Actions, AI-assisted incident triage  
**Practices:** REST APIs, functional probes, automated tests, code review, GitHub pull requests, incident monitoring

## Why it matters

OpsRelay connects software engineering with business operations. Detection needs to go beyond a page loading: teams should verify that a real customer task still works. Incident recovery also needs evidence and human oversight so that attempted repairs do not create new problems.

**Credit:** The linked [OpsRelay repository](https://github.com/faizm10/opsrelay-agent) contains the full team's work and original Git history. This page describes my specific contributions and the broader team system separately.
