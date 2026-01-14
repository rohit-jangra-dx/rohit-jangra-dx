# Rohit Jangra
#### Backend Engineer | Fullstack Developer

India | Email: your.email@example.com

## PROFESSIONAL SUMMARY

Backend Engineer with hands-on experience owning and operating production systems end-to-end for a loan services platform. Strong in Python backend development, batch processing, external API integrations, data consistency, and system reliability. Known for rapid adaptation across stacks, architectural thinking, and building systems designed to run safely under failure and retries.

## PROFESSIONAL EXPERIENCE
### Freelance Backend Engineer (Sole Developer)
Remote | 2023 – Present

#### Loan Application & Eligibility Platform (Python, Node.js, MongoDB)

- Designed and built a production loan application platform supporting user onboarding, account       creation, and loan application workflows.
- Implemented REST APIs for managing users, applications, and lender eligibility states.
- Designed MongoDB schemas and indexes to support safe querying and updates at scale.
- Acted as the system owner, responsible for correctness, data integrity, and operational stability.

#### Batch Dispatcher & Partner API Integration (Python)

- Built a cron-driven batch dispatcher to process loan applications and dispatch them to multiple   external lender APIs.
- Implemented OS-level locking (flock) to guarantee single-instance execution and prevent concurrent runs.
- Designed the system for idempotency and safe re-runs, avoiding duplicate partner requests.
- Added retry logic, failure isolation, and partial success handling for unreliable third-party APIs.
- Ensured data safety by treating source records as immutable and operating only on filtered eligible datasets.
- Optimized MongoDB queries and indexing to process large datasets (tens to hundreds of thousands of records) without impacting production performance.
- Deployed and operated the system on a Linux VPS with structured logging for live debugging.

#### Frontend Migration (Angular)
- Took over a legacy React frontend with significant technical debt
- Learned Angular on the job and migrated the frontend to Angular, aligning UI flows with backend APIs.
- Integrated REST APIs and asynchronous eligibility updates.

### Freelance Web Developer
- Delivered custom full-stack applications for clients, from requirements gathering to deployment.  
- Built a real-money Ludo betting platform (Go, Postgres, Redis, React, Podman) with:  
   • Real-time game server handling concurrent multiplayer sessions  
   • Secure OTP authentication and integrated payment workflows  
   • Automated deployments with GitHub Actions + containerization  
- Developed a Lost-and-Found system (FastAPI, MongoDB) enabling item matching & notifications.  

## SELECTED PROJECTS
#### Hybrid Movie Recommendation System (Python)
- Built a hybrid recommender system using LightFM with collaborative filtering and metadata features.
- Experimented with WARP and WARP-KOS loss functions.
- Evaluated models using Precision@K, Recall@K, and AUC.
- Produced a complete technical report covering modeling decisions and evaluation trade-offs.

## TECHNICAL SKILLS
### Languages:
Python, JavaScript, TypeScript, Go (working knowledge)

### Backend & Systems:
REST APIs, Batch Processing, Cron Jobs, External API Integration, Concurrency Control, Idempotency, Retry Strategies, Logging & Debugging

### Databases & Storage:
MongoDB, PostgreSQL, Redis

### Infrastructure & Ops:
Linux, Nginx, Shell Scripting, Process Orchestration

### Architecture Concepts:
System Design, Failure Handling, Data Consistency, Backend Service Ownership

## ADDITIONAL STRENGTHS
- Strong ability to adapt to new stacks and frameworks based on project needs
- Experience debugging issues across OS, network, and application layer
- Focus on building boring, reliable systems that can run unattended in production

