# Project Roadmap

Two excellent projects with strong documentation are more valuable than many tutorial clones.

## Small warm-up project — Months 1–3

Build a C++ command-line application such as an expense tracker, library manager, or student-record system.

Required:
- [ ] Clear menu and input validation
- [ ] Functions and classes used sensibly
- [ ] File persistence
- [ ] Search, update, and delete operations
- [ ] Error handling
- [ ] README with setup and usage

Purpose: regain C++ fluency and practice Git—not create the centerpiece of the resume.

## Project 1 — Full-stack foundation (Months 6–9)

### Recommended idea: University Collaboration Platform

Possible users: students, teachers, clubs, and study groups.

### Core features
- [ ] Account registration and login
- [ ] Secure password storage
- [ ] User roles and permissions
- [ ] Courses, groups, or communities
- [ ] Posts, comments, and reactions
- [ ] Search, filtering, sorting, pagination
- [ ] Profile management
- [ ] Responsive React interface
- [ ] PostgreSQL database

### Engineering requirements
- [ ] TypeScript frontend and backend
- [ ] Validation at API boundaries
- [ ] Central error handling
- [ ] Database migrations and seed data
- [ ] Unit and integration tests
- [ ] OpenAPI/Swagger documentation
- [ ] Environment-variable configuration
- [ ] Deployment instructions
- [ ] Docker added during Year 2
- [ ] CI pipeline added during Year 2

### README must explain
- Problem and users
- Features
- Architecture
- Data model
- Setup
- Tests
- API documentation
- Security choices
- Trade-offs
- Future improvements

## Project 2 — Standout project (Months 16–18)

### Recommended idea: Competitive Programming Analytics Platform

This connects software engineering, Codeforces, DSA, and data-driven learning into one coherent project story.

### Product features
- [ ] Import public competitive-programming profiles
- [ ] Track solved problems by tag and difficulty
- [ ] Analyze repeated weaknesses
- [ ] Recommend practice sets
- [ ] Visualize rating and topic progress
- [ ] Create personal goals and revision queues
- [ ] Compare progress with friends
- [ ] Create custom practice contests
- [ ] Notifications and scheduled reminders

### Deeper engineering features
Choose features because the product needs them—not for buzzwords.

- [ ] Background synchronization jobs
- [ ] Job queue with retry policy
- [ ] Redis caching
- [ ] Rate-limit handling for external APIs
- [ ] WebSockets or server-sent events for live updates
- [ ] Idempotent synchronization
- [ ] Search
- [ ] Object storage if reports/files are generated
- [ ] Role-based administration
- [ ] Audit logs

### Production requirements
- [ ] Architecture document before implementation
- [ ] Issue-based milestone plan
- [ ] Docker Compose development environment
- [ ] CI for lint, type check, and tests
- [ ] Structured logging
- [ ] Health checks
- [ ] Metrics or basic monitoring
- [ ] Security review
- [ ] Database index analysis
- [ ] Load testing of critical endpoints
- [ ] Deployed demonstration
- [ ] Honest performance numbers

## Alternative standout projects

- Real-time collaborative study workspace
- Distributed job scheduler dashboard
- Campus event and organization platform
- Team project-management tool with real-time collaboration
- Developer API monitoring and incident dashboard

Choose one, not all.

## Project quality checklist

### Product
- [ ] Solves a clear problem
- [ ] Has a defined user
- [ ] Core flow is easy to demonstrate
- [ ] Handles loading, empty, and error states
- [ ] Is deployed and accessible when possible

### Code
- [ ] Understandable structure
- [ ] Consistent naming and formatting
- [ ] No secrets committed
- [ ] Validation and error handling
- [ ] Tests for important behavior
- [ ] Small, meaningful commits

### Database
- [ ] Relationships are justified
- [ ] Constraints enforce correctness
- [ ] Migrations exist
- [ ] Important queries are indexed
- [ ] Transactions protect multi-step writes

### Operations
- [ ] Reproducible local setup
- [ ] Docker configuration
- [ ] CI checks
- [ ] Logs and health endpoints
- [ ] Backup/migration awareness

### Communication
- [ ] Professional README
- [ ] Architecture diagram
- [ ] API documentation
- [ ] Trade-offs documented
- [ ] Demo video or screenshots
- [ ] Resume bullets describe impact honestly

## Tutorial rule

Courses and tutorials may teach individual tools. The final project must require personal decisions, debugging, design, and documentation. Never present a copied course project as original engineering work.
