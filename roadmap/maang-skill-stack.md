# MAANG Skill Pillars and Recommended Language Stack

This file defines the complete profile to build over the next two years. The goal is not to collect technologies. The goal is to become a strong problem solver, capable software engineer, mathematically prepared future AI learner, and interview-ready new graduate.

## Final target profile

> I solve algorithmic problems in C++, build and deploy tested backend/full-stack systems using TypeScript, Node.js, PostgreSQL, and React, understand core computer science and system fundamentals, use Python for mathematics and AI work, and explain my decisions clearly.

---

# 1. Coding and problem solving

## Primary language: C++

Use C++ for DSA, Codeforces, interview preparation, and algorithmic problem solving.

### C++ essentials

- [ ] Syntax, input/output, functions, and scope
- [ ] Arrays, strings, vectors, pairs, tuples
- [ ] References, pointers, structs, and classes
- [ ] STL containers and algorithms
- [ ] Iterators and range-based loops
- [ ] Sorting and custom comparators
- [ ] `map`, `set`, `unordered_map`, `unordered_set`
- [ ] `stack`, `queue`, `deque`, `priority_queue`
- [ ] Lambdas and basic templates
- [ ] Recursion and backtracking
- [ ] Debugging and edge-case testing
- [ ] Time and space complexity analysis

### DSA and algorithms

- [ ] Arrays and strings
- [ ] Hashing
- [ ] Linked lists
- [ ] Stack, queue, deque, heap
- [ ] Two pointers and sliding window
- [ ] Prefix sums and difference arrays
- [ ] Binary search and binary search on answer
- [ ] Recursion and backtracking
- [ ] Trees, BST, traversals, LCA
- [ ] Tries
- [ ] Graph traversal: BFS and DFS
- [ ] Shortest paths
- [ ] Minimum spanning tree
- [ ] Topological sorting
- [ ] Union-find / DSU
- [ ] Greedy algorithms
- [ ] Dynamic programming
- [ ] Bit manipulation
- [ ] Basic string algorithms
- [ ] Basic number theory and combinatorics

### Interview execution

- [ ] Clarify the problem before coding
- [ ] Explain brute force first
- [ ] Derive the optimized approach
- [ ] State correctness reasoning
- [ ] State time and space complexity
- [ ] Test normal and edge cases aloud
- [ ] Write readable code without depending heavily on autocomplete
- [ ] Practice timed mock interviews

---

# 2. Core computer science

## Operating systems

- [ ] Processes and threads
- [ ] Context switching and scheduling
- [ ] Concurrency and race conditions
- [ ] Mutexes, semaphores, and synchronization
- [ ] Deadlocks
- [ ] Virtual memory and paging
- [ ] Stack versus heap
- [ ] Filesystems and file descriptors

## Database systems

- [ ] Relational model
- [ ] Keys and constraints
- [ ] Normalization
- [ ] Joins and subqueries
- [ ] Indexes and B-trees
- [ ] Transactions and ACID
- [ ] Isolation levels
- [ ] Locks and concurrency
- [ ] Query planning and execution
- [ ] Replication and partitioning basics

## Computer networks

- [ ] OSI and TCP/IP models
- [ ] IP addresses and ports
- [ ] TCP versus UDP
- [ ] DNS
- [ ] HTTP and HTTPS
- [ ] TLS basics
- [ ] Cookies, sessions, and tokens
- [ ] Proxies and reverse proxies
- [ ] Load balancers
- [ ] WebSockets
- [ ] Latency, bandwidth, and packet loss

## OOP and software design

- [ ] Encapsulation, abstraction, inheritance, polymorphism
- [ ] Composition versus inheritance
- [ ] Interfaces and dependency inversion
- [ ] SOLID principles
- [ ] Common design patterns
- [ ] Clean architecture basics
- [ ] Refactoring and code smells

## Computer architecture basics

- [ ] CPU, registers, cache, RAM, and storage
- [ ] Memory hierarchy
- [ ] Compilation and linking
- [ ] Call stack
- [ ] Cache locality
- [ ] Basic parallelism concepts

## Distributed systems basics

- [ ] Horizontal versus vertical scaling
- [ ] Replication
- [ ] Partitioning and sharding
- [ ] Consistency and availability trade-offs
- [ ] Caching
- [ ] Message queues
- [ ] Idempotency
- [ ] Rate limiting
- [ ] Fault tolerance
- [ ] Observability basics

---

# 3. Recommended language and technology stack

## Language roles

| Purpose | Language |
|---|---|
| DSA, Codeforces, interviews | C++ |
| Primary software development | TypeScript |
| AI, mathematics, research, scripting | Python |

Do not add another major language until these three have clear purposes and practical depth.

## Backend stack

- [ ] JavaScript fundamentals
- [ ] TypeScript fundamentals and strict typing
- [ ] Node.js runtime concepts
- [ ] HTTP and REST API design
- [ ] Express for learning backend fundamentals
- [ ] NestJS for structured serious projects
- [ ] Validation and error handling
- [ ] Authentication and authorization
- [ ] Logging
- [ ] API documentation
- [ ] Unit and integration testing
- [ ] Background jobs and queues
- [ ] WebSockets

## Database stack

### Primary database: PostgreSQL

- [ ] Schema design
- [ ] SQL CRUD operations
- [ ] Joins and aggregations
- [ ] Constraints
- [ ] Indexes
- [ ] Transactions
- [ ] Migrations
- [ ] Query analysis
- [ ] Pagination
- [ ] Connection pooling
- [ ] Backup and restore basics

### Later additions

- [ ] Redis for caching, sessions, rate limiting, and jobs
- [ ] MongoDB only when a project has a genuine document-database use case

## Frontend stack

- [ ] Semantic HTML
- [ ] CSS fundamentals
- [ ] Responsive design
- [ ] JavaScript in the browser
- [ ] TypeScript with React
- [ ] Components, props, state, and hooks
- [ ] Forms and validation
- [ ] Routing
- [ ] API integration
- [ ] Authentication state
- [ ] Loading and error states
- [ ] Accessibility basics
- [ ] Next.js only after React fundamentals

## Infrastructure and delivery

- [ ] Linux command line
- [ ] Bash fundamentals
- [ ] Git and GitHub
- [ ] Branches, pull requests, merges, and conflict resolution
- [ ] Environment variables and secrets
- [ ] Docker
- [ ] Docker Compose
- [ ] GitHub Actions
- [ ] CI/CD
- [ ] Reverse proxy basics
- [ ] Deployment
- [ ] One cloud platform only
- [ ] Monitoring and logs

Recommended first cloud: AWS, but cloud study should remain secondary to building and deploying working applications.

## Python for AI and research

Learn Python after the main development routine is stable.

- [ ] Core Python syntax
- [ ] Functions, classes, modules, and virtual environments
- [ ] NumPy
- [ ] pandas
- [ ] matplotlib
- [ ] Jupyter notebooks
- [ ] scikit-learn
- [ ] PyTorch later
- [ ] Reproducing mathematical derivations in code
- [ ] Reading and modifying research implementations

---

# 4. Real software engineering

- [ ] Read unfamiliar codebases
- [ ] Break work into GitHub issues
- [ ] Write meaningful commits
- [ ] Use branches and pull requests
- [ ] Review code
- [ ] Write unit tests
- [ ] Write integration tests
- [ ] Test APIs
- [ ] Debug systematically
- [ ] Handle failures and errors
- [ ] Log useful information
- [ ] Manage configuration and secrets safely
- [ ] Document setup and architecture
- [ ] Measure performance before optimizing
- [ ] Refactor without changing behavior
- [ ] Use CI to run tests and checks automatically

---

# 5. Project evidence

Build two deep projects rather than many shallow clones.

## Every serious project should include

- [ ] Clear problem and target users
- [ ] Thoughtful architecture
- [ ] Authentication
- [ ] Authorization and roles
- [ ] PostgreSQL schema
- [ ] Input validation
- [ ] Error handling
- [ ] Tests
- [ ] Docker setup
- [ ] CI/CD
- [ ] Deployment
- [ ] Logs
- [ ] API documentation
- [ ] Architecture diagram
- [ ] Strong README
- [ ] Meaningful Git history

## At least one flagship project should include several of these

- [ ] WebSockets
- [ ] Redis caching
- [ ] Background jobs
- [ ] Queue processing
- [ ] Search
- [ ] File storage
- [ ] Rate limiting
- [ ] Database indexing
- [ ] Performance measurement
- [ ] External API integration
- [ ] Notifications
- [ ] Role-based administration

Recommended flagship idea: a competitive-programming analytics and practice platform that tracks strengths, weaknesses, submissions, revision schedules, and problem recommendations.

---

# 6. Communication and interview maturity

- [ ] Explain technical ideas in simple language
- [ ] Speak while solving coding problems
- [ ] Ask clarifying questions
- [ ] Explain trade-offs
- [ ] Write concise technical documentation
- [ ] Present projects in two minutes and ten minutes
- [ ] Prepare STAR stories
- [ ] Prepare stories about failure, conflict, leadership, ownership, and learning
- [ ] Practice spoken English
- [ ] Conduct mock interviews
- [ ] Accept and apply feedback

---

# 7. Career evidence before graduation

Aim to complete at least two or three of the following:

- [ ] Internship
- [ ] Research assistantship
- [ ] Meaningful open-source contributions
- [ ] Serious team project
- [ ] Product used by real users
- [ ] Hackathon achievement
- [ ] Teaching or mentoring
- [ ] Technical writing
- [ ] Strong university capstone

Also prepare:

- [ ] One-page resume
- [ ] Clean LinkedIn profile
- [ ] Organized GitHub profile
- [ ] Project demos
- [ ] Quantified project impact
- [ ] Application tracker
- [ ] Broad company list beyond only MAANG

---

# 8. What not to prioritize now

Do not make these major tracks during the first year:

- [ ] Java, Go, Rust, C#, Kotlin, or other additional languages
- [ ] Kubernetes
- [ ] Advanced DevOps
- [ ] Multiple cloud providers
- [ ] Blockchain
- [ ] Mobile development
- [ ] Cybersecurity specialization
- [ ] Deep machine-learning frameworks before math and Python foundations

These are not bad technologies. They are simply lower priority for the current goal.

---

# 9. Final stack decision

```text
Primary target role: Backend-focused Software Engineer
Interview and competitive-programming language: C++
Primary development language: TypeScript
Backend: Node.js + Express first, then NestJS
Database: PostgreSQL
Frontend: React, then optionally Next.js
Infrastructure: Linux + Docker + GitHub Actions + one cloud
Caching and jobs: Redis later
AI and research language: Python
```

# 10. Graduation readiness checklist

- [ ] I can solve common interview problems in C++ and explain them clearly.
- [ ] I understand DSA, complexity, and core algorithmic patterns.
- [ ] I can build a tested backend application from scratch.
- [ ] I can design and query a PostgreSQL database confidently.
- [ ] I can build enough React frontend to ship a full product.
- [ ] I can deploy with Docker and CI/CD.
- [ ] I understand OS, DBMS, networks, OOP, and system-design fundamentals.
- [ ] I have two substantial projects.
- [ ] I have at least one real team, internship, research, or open-source experience.
- [ ] I can explain my projects, trade-offs, failures, and lessons.
- [ ] I use Python for mathematical and introductory AI work.
- [ ] I have a polished resume and practice mock interviews regularly.
