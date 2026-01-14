# Igor Roslyakov — Technical Writing Portfolio

## About me
Technical writer focused on developer documentation and Python education.

## Documentation projects

### 🟢 Webhook Receiver Onboarding Template

Onboarding documentation template for a backend webhook receiver, including 
minimal FastAPI implementation, architecture notes, and operational runbooks.

**Audience:** Backend engineers joining a team, junior to mid-level, who need 
to understand how a webhook-based service works and how to contribute to it.  
**Focus:** 
1. Onboarding documentation structure.
2. Clarity of technical explanations.
3. Documentation of common backend concerns:
   1. request handling;
   2. security assumptions;
   3. idempotency;
   4. operational troubleshooting.

🔗 [webhook-receiver-onboarding-template](https://github.com/igor-rosliakov-techwriter/webhook-receiver-onboarding-template)


### 🟡 Dockerized Backend Development Environment (In Progress)

Documentation-driven template for a local backend development environment
built with Docker Compose. The project demonstrates how developer-facing
documentation supports onboarding, environment setup, and day-to-day
development for backend services.

The repository includes a minimal FastAPI-based API service, a background
worker, PostgreSQL, Redis, and supporting documentation explaining how the
system is structured, started, debugged, and operated locally.

**Audience:** Backend engineers and new team members who need to run and
understand a multi-service backend system locally.

**Focus:**
1. Developer onboarding for local environments.
2. Documentation of Docker and Docker Compose usage in backend teams.
3. Explanation of service interactions:
   1. API → database persistence;
   2. API → queue-based background processing;
   3. worker-based task execution.
4. Operational documentation:
   1. health checks;
   2. debugging workflows;
   3. common local development pitfalls;
   4. runbooks for typical failure scenarios.

**Status:**
The project is actively developed. Current scope includes environment setup,
health checks, and API-to-database/queue integration. Background worker
processing and extended runbooks are being implemented incrementally.

🔗 [dockerized-backend-dev-environment](https://github.com/igor-rosliakov-techwriter/dockerized-backend-dev-environment)



### 🟢 Technical Writing Samples (Articles & Educational Materials)

Curated collection of developer-focused technical writing samples covering
backend systems, platform architecture, infrastructure workflows, and developer tooling.
Audience: Backend, platform, and infrastructure engineers, as well as technical
writers working with developer-facing documentation and onboarding materials.

** Focus:**
1. Clear explanation of complex technical systems.
2. Architecture and data flow documentation.
3. Backend and platform-level concepts:
   1. asynchronous processing and monitoring;
   2. message-driven systems;
   3. Kubernetes-based platform architecture;
   4. developer workflows and tooling;
   5. infrastructure and DevOps practices.

🔗 [technical-writing-samples](https://github.com/igor-rosliakov-techwriter/Technical-Writing-Samples/tree/main)
