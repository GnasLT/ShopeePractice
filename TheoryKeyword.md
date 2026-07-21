Dưới đây là toàn bộ danh mục Keyword kiến thức được hệ thống hóa đầy đủ, chuẩn hóa theo thuật ngữ chuyên ngành (English Terms).

Danh sách này bao phủ trọn vẹn từ Lập trình, Kiến trúc hệ thống, Cơ sở dữ liệu, Mạng & Security, Cloud/DevOps cho đến Tối ưu hóa & Testing — phản ánh chính xác khung năng lực của một Senior / Lead / System Architect / Expert.

1. Programming & Software Architecture
Design Patterns: SOLID Principles, Factory, Singleton, Observer, Strategy, Repository Pattern, Dependency Injection (DI) / Inversion of Control (IoC).

Architectural Patterns: Monolithic, Microservices, Event-Driven Architecture (EDA), Serverless Architecture, CQRS (Command Query Responsibility Segregation), Event Sourcing, Domain-Driven Design (DDD), Hexagonal Architecture (Ports & Adapters).

Concurrency & Threading: Async/Await, Event Loop, Non-blocking I/O, Thread Pool, Race Conditions, Mutex, Atomic Operations.

Data Structures & Algorithms: Hash Table, B-Tree / B+ Tree, Ring Buffer, LRU/LFU Cache, Graph/Tree Traversals, Time/Space Complexity (Big-O).

2. Network, Web Protocols & Gateway Layer
Network Protocols: TCP/IP, UDP, HTTP/1.1, HTTP/2, HTTP/3 (QUIC), gRPC, WebSockets, Server-Sent Events (SSE), WebRTC (P2P), DNS Resolution.

Proxy & Load Balancing: Forward Proxy, Reverse Proxy, Layer 4 Load Balancing (TCP - NLB), Layer 7 Load Balancing (HTTP - ALB), Anycast Routing.

Web Servers & Gateways: Nginx, HAProxy, Traefik, Envoy, Kong API Gateway.

Load Balancing Algorithms: Round Robin, Least Connections, IP Hash (Sticky Session), Weighted Balancing, Passive/Active Health Checks.

Content Delivery Network (CDN): Edge Caching, Cache-Control Headers, Cache Invalidation, Edge Computing / Edge Workers, SSL/TLS Termination.

3. High Concurrency & Distributed Systems
Message Queues & Streaming: Apache Kafka, RabbitMQ, NATS, AWS SQS/SNS, Consumer Groups, Message Partitioning, Dead Letter Queue (DLQ).

Caching Strategies: Cache-Aside, Write-Through, Write-Behind, Cache Avalanche, Cache Stampede, Cache Penetration.

Concurrency Control & Locking: Distributed Lock (Redlock), Optimistic Concurrency Control (OCC - Versioning), Pessimistic Locking (SELECT FOR UPDATE).

Rate Limiting & Throttling: Token Bucket, Leaky Bucket, Sliding Window Log, Fixed Window.

Distributed Consistency & Transactions: CAP Theorem, PACELC Theorem, Eventual Consistency, Distributed Transactions, Two-Phase Commit (2PC), Saga Pattern, Outbox Pattern, CRDTs, Operational Transformation (OT).

Fault Tolerance: Circuit Breaker Pattern, Retry Policy with Exponential Backoff & Jitter, Bulkhead Pattern, Graceful Degradation.

4. Databases & Storage Engine
Relational Database (RDBMS): PostgreSQL, MySQL, ACID Properties, Database Normalization, B-Tree Indexing, Composite Index, Cover Index, Query Execution Plan (EXPLAIN ANALYZE).

NoSQL & Time-Series DB: MongoDB, Cassandra, DynamoDB, ClickHouse, InfluxDB, Prometheus.

Database Scaling: Read/Write Splitting (Replication), Connection Pooling (PgBouncer), Database Sharding, Horizontal/Vertical Partitioning, Consistent Hashing.

Storage Mechanics: Write-Ahead Logging (WAL), Append-Only File (AOF), LSM-Tree, In-Memory Storage (Redis).

Search Engines: Elasticsearch, OpenSearch, Full-Text Search, Inverted Index.

5. Web Security & Auth
OWASP Top 10 Security: XSS (Cross-Site Scripting), CSRF (Cross-Site Request Forgery), SQL Injection (SQLi), SSRF (Server-Side Request Forgery), CORS, Content Security Policy (CSP), Input Sanitization.

Authentication & Authorization: OAuth 2.0, OpenID Connect (OIDC), JWT (JSON Web Token), Session Management, Refresh Tokens, RBAC (Role-Based Access Control), ABAC (Attribute-Based Access Control).

Infrastructure Security: Web Application Firewall (WAF), Mutual TLS (mTLS), DDoS Mitigation, Rate Limiting, Encryption at Rest / Encryption in Transit.

6. Frontend Performance & Rendering
Rendering Strategies: CSR (Client-Side Rendering), SSR (Server-Side Rendering), SSG (Static Site Generation), ISR (Incremental Static Regeneration), Hydration.

Performance Metrics (Core Web Vitals): LCP (Largest Contentful Paint), INP (Interaction to Next Paint), CLS (Cumulative Layout Shift), TTFB (Time to First Byte).

Frontend Optimization: Code-Splitting, Tree-Shaking, Lazy Loading, Asset Bundling (Vite/Webpack), Web Workers, Service Workers (PWA), Virtual DOM Optimization, Repaint & Reflow Reduction.

Advanced Rendering: HTML5 Canvas, WebGL, Three.js, PixiJS, Micro-Frontends.

7. Cloud, DevOps & Infrastructure
Containerization & Orchestration: Docker, Multi-stage Builds, Docker Compose, Kubernetes (K8s) (Pods, Deployments, Services, Ingress, ConfigMaps).

Infrastructure as Code (IaC): Terraform, Ansible.

CI/CD Automation: GitHub Actions, GitLab CI/CD, Pipeline Automation, Zero-Downtime Deployment (Blue-Green Deployment, Canary Deployment, Rolling Update).

Cloud Providers (AWS / GCP Focus):

Compute: AWS EC2, AWS Lambda (Serverless), AWS ECS/EKS.

Networking: AWS VPC, Subnets, Route Tables, Internet Gateway, Security Groups.

Storage: AWS S3, CloudFront.

Database: AWS RDS, ElastiCache, DynamoDB.

8. Observability, Testing & Quality Assurance
Observability Stack (PLG/ELK):

Logging: Elastic Stack (ELK), Promtail + Loki, Centralized Logging.

Metrics: Prometheus, Grafana, OpenTelemetry.

Tracing: Distributed Tracing, Jaeger, AWS X-Ray.

Testing Pyramid: Unit Testing (Jest, Vitest), Integration Testing, End-to-End Testing (Playwright, Cypress), Test-Driven Development (TDD).

Performance & Chaos Testing: Stress Testing / Load Testing (k6, Locust, JMeter), Chaos Engineering (Giả lập sự cố mạng/máy chủ).

Code Quality & Static Analysis: TypeScript (Advanced Types, Generics), ESLint, SonarQube, Pre-commit Hooks (Husky).
