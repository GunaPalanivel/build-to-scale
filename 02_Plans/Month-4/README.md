# Month 4: SQL, JDBC & Spring Boot

## Overview

Month 4 focuses on backend development with strong emphasis on database integration and enterprise Java frameworks. You will master SQL querying and optimization, build JDBC database connectivity layers, and develop RESTful APIs with Spring Boot. The goal is to achieve an 88%+ average assessment score, successfully build microservices, and deploy production-ready backend applications.

**Target skill level for all areas is 9/10 — precisely, no more, no less.**

---

## Monthly Goals

- Master SQL syntax, normalization, indexing, and advanced querying techniques.
- Build secure, efficient database connections using JDBC and connection pooling.
- Design and implement REST APIs with Spring Boot, including dependency injection, JPA, and exception handling.
- Validate backend services with unit and integration tests.
- Deploy backend applications to the cloud.
- Complete 35+ production-grade projects combining database and backend logic.

---

## Study Schedule

- Study Days: Monday to Friday (Days 1-5 each week)
- Review Day: Saturday (Day 6) for integration, debugging, and performance optimization
- Assessment/Planning: Sunday (Day 7) to test knowledge, reflect, and plan

---

## Weekly Breakdown

### Week 13: SQL & Database Design

**Daily Focus**

- **Day 85 (Monday)**

  - Morning (2h): SQL fundamentals — DDL, DML, DCL, TCL commands
  - Afternoon (2h): Database normalization (1NF, 2NF, 3NF, BCNF)
  - Evening (1h): Entity-Relationship diagrams and relationships (1:1, 1:N, N:M)
  - Metric: Design 3 normalized database schemas

- **Day 86 (Tuesday)**

  - Morning (2h): SELECT queries — WHERE, ORDER BY, LIMIT, DISTINCT
  - Afternoon (2h): Solve 30 SELECT problems on HackerRank SQL
  - Evening (1h): Aggregate functions — COUNT, SUM, AVG, MAX, MIN
  - Metric: Solve 30 HackerRank basic SELECT queries with 100% accuracy

- **Day 87 (Wednesday)**

  - Morning (2h): JOIN types — INNER, LEFT, RIGHT, FULL, CROSS, SELF joins
  - Afternoon (2h): 25 JOIN problems practice
  - Evening (1h): Subqueries and correlated subqueries
  - Metric: Master all JOIN types, solve complex multi-table queries

- **Day 88 (Thursday)**

  - Morning (2h): GROUP BY, HAVING clauses and window functions
  - Afternoon (2h): Advanced aggregation problem-solving
  - Evening (1h): Indexing strategies, query optimization, EXPLAIN plan analysis
  - Metric: Optimize 10 slow queries with ≥50% time reduction

- **Day 89 (Friday)**

  - Morning (2h): Transactions and ACID properties — COMMIT, ROLLBACK, concurrency
  - Afternoon (2h): Stored procedures, triggers, and functions creation
  - Evening (1h): Views and Common Table Expressions (CTEs)
  - Metric: Implement 5 stored procedures with error handling

- **Day 90 (Saturday)** — Review & Project Day

  - Project Work (4h): Complete e-commerce database design with normalization and indexing
  - Evening (1h): Performance testing and query optimization
  - Metric: Handle 50,000+ records with query times < 100ms

- **Day 91 (Sunday)** — Assessment & Planning
  - Morning (2h): SQL assessment — 40 questions (target: ≥88%)
  - Afternoon (2h): Optimization session and review best practices
  - Evening (1h): Document SQL patterns and optimization notes

**Week 13 Success Metrics**

- ✅ Assessment score ≥35/40 (88%)
- ✅ 80+ SQL problems solved on HackerRank
- ✅ 5 normalized database schemas designed
- ✅ Query optimization improves speed by 50%+

---

### Week 14: JDBC & Database Connectivity

**Daily Focus**

- **Day 92 (Monday)**

  - Morning (2h): JDBC architecture — Driver types, DriverManager, Connection usage
  - Afternoon (2h): Write first JDBC connection program to MySQL
  - Evening (1h): Connection pooling basics explained
  - Metric: Connect to 3 different databases successfully

- **Day 93 (Tuesday)**

  - Morning (2h): JDBC Statements — Statement, PreparedStatement, CallableStatement usage
  - Afternoon (2h): CRUD operations implementation using PreparedStatements
  - Evening (1h): Prevent SQL injection by using parameterized queries
  - Metric: Complete secure CRUD for 5 database tables

- **Day 94 (Wednesday)**

  - Morning (2h): ResultSet navigation, data extraction, and metadata utilization
  - Afternoon (2h): Build data export utility (CSV, JSON formats)
  - Evening (1h): Batch updates and transaction management basics
  - Metric: Export 10,000+ records within 5 seconds

- **Day 95 (Thursday)**

  - Morning (2h): Configure connection pooling using HikariCP
  - Afternoon (2h): Implement pooling in JDBC projects for optimization
  - Evening (1h): Exception handling and error management strategies
  - Metric: Achieve 10x performance improvement using pooling

- **Day 96 (Friday)**

  - Morning (2h): DAO (Data Access Object) pattern—separation of concerns and repository abstraction
  - Afternoon (2h): Refactor code to incorporate DAO pattern
  - Evening (1h): Resource management with try-with-resources
  - Metric: Implement DAO layers for 8 entities

- **Day 97 (Saturday)** — Review & Project Day

  - Project Work (4h): Build employee management system using JDBC with full CRUD, search, and reporting features
  - Evening (1h): Perform performance tests and optimize queries
  - Metric: Manage 5,000+ employees with queries responding under 200ms

- **Day 98 (Sunday)** — Assessment & Planning
  - Morning (2h): JDBC assessment — 25 questions (target: ≥88%)
  - Afternoon (2h): Code review and improvements
  - Evening (1h): Document JDBC best practices

**Week 14 Success Metrics**

- ✅ Assessment score ≥22/25 (88%)
- ✅ Secure and optimized CRUD implemented
- ✅ Connection pooling delivers 10x performance gains
- ✅ DAO pattern correctly implemented
- ✅ JDBC skills rated 8/10

---

### Week 15: Spring Boot Fundamentals

**Daily Focus**

- **Day 99 (Monday)**

  - Morning (2h): Spring Boot introduction — starters, auto-configuration
  - Afternoon (2h): Create first Spring Boot REST API application
  - Evening (1h): Overview of Spring architecture and dependency injection
  - Metric: Develop 3 starter Spring Boot projects

- **Day 100 (Tuesday)**

  - Morning (2h): Dependency Injection — @Autowired, @Component, @Service, @Repository usage
  - Afternoon (2h): Build service layer using DI
  - Evening (1h): Bean lifecycle and scopes explanation
  - Metric: Dependency Injection applied to 10 classes effectively

- **Day 101 (Wednesday)**

  - Morning (2h): Spring Data JPA — entities, repository interfaces, database relationships
  - Afternoon (2h): Transition JDBC code to Spring Data JPA
  - Evening (1h): Query method customizations with @Query annotations
  - Metric: Convert 5 database tables to JPA entities with proper relationships

- **Day 102 (Thursday)**

  - Morning (2h): REST API development — @RestController, @RequestMapping, HTTP method annotations
  - Afternoon (2h): Build REST API for a sample blog application
  - Evening (1h): Request/response handling and DTO usage
  - Metric: Implement 15 REST endpoints with correct HTTP status codes

- **Day 103 (Friday)**

  - Morning (2h): Exception handling in Spring Boot — @ControllerAdvice and custom exceptions
  - Afternoon (2h): Implement global exception handling strategies
  - Evening (1h): Input validation using @Valid and custom validators
  - Metric: Manage 20+ error scenarios with accurate responses

- **Day 104 (Saturday)** — Review & Project Day

  - Project Work (4h): Develop task management API with full CRUD, user, task, and category resources using Spring Boot and JPA
  - Evening (1h): API testing using Postman and documenting APIs
  - Metric: Deliver production-quality REST API with 20+ endpoints

- **Day 105 (Sunday)** — Assessment & Planning
  - Morning (2h): Spring Boot assessment — 30 questions (target: ≥85%)
  - Afternoon (2h): Cloud deployment of Spring Boot application (Heroku/Railway)
  - Evening (1h): Generate Swagger/OpenAPI documentation

**Week 15 Success Metrics**

- ✅ Assessment score ≥26/30 (87%)
- ✅ Production-ready REST API with 20+ endpoints
- ✅ Fully integrated Spring Data JPA replacing JDBC
- ✅ Successfully deployed applications with documentation
- ✅ Spring Boot basics mastery: 7.5/10

---

### Week 16: Advanced Spring Boot & Month 4 Integration

**Daily Focus**

- **Day 106 (Monday)**

  - Morning (2h): Spring Security basics — authentication and authorization concepts
  - Afternoon (2h): Implement JWT based authentication
  - Evening (1h): Role-based access control setup
  - Metric: Secure all endpoints, implement 3-tier role hierarchy

- **Day 107 (Tuesday)**

  - Morning (2h): Testing Spring Boot applications — JUnit 5, MockMvc, @WebMvcTest
  - Afternoon (2h): Develop unit and integration test suites
  - Evening (1h): Analyze and improve test coverage
  - Metric: Achieve ≥85% code coverage

- **Day 108 (Wednesday)**

  - Morning (2h): Application best practices—configuration management, environment profiles
  - Afternoon (2h): Logging using SLF4J and Logback
  - Evening (1h): Monitoring endpoints via Spring Boot Actuator
  - Metric: Setup production-ready configuration and monitoring

- **Days 109-110 (Thursday - Friday)**

  - Full days (6h each): Full-stack integration
    - Frontend (HTML, CSS, JavaScript)
    - Backend Spring Boot REST API with JPA and security
    - MySQL database integration
    - JWT authentication
    - Deploy backend and frontend to the cloud
  - Metric: Functioning full-stack application with real users tested

- **Day 111 (Saturday)** — Review & Optimization

  - Testing, bug fixes, performance tuning
  - Deployment to production environment with CI/CD pipelines
  - Metric: Lighthouse scores ≥90, API latency <300ms

- **Day 112 (Sunday)** — Month Assessment & Retrospective
  - Month-end comprehensive assessment (60 questions; target: ≥88%)
  - Portfolio update with documentation and demo videos
  - Planning Month 5 learning goals

**Week 16 & Month 4 Success Metrics**

- ✅ Assessment score ≥53/60 (88%)
- ✅ Full-stack production-ready app deployed
- ✅ Mastery: Java 8.5/10, Spring Boot 8/10, SQL/JDBC 8.5/10
- ✅ Total projects completed >35 across all technologies

---

## Engineering Mindset & Delivery Philosophy

- Develop incrementally with testable, deployable milestones ("brick-by-brick").
- Emphasize quantifiable outcomes—performance metrics, code quality, coverage.
- Conduct continuous peer and mentor code review with actionable feedback.
- Balance theoretical knowledge with production-ready applications.
- Follow clean coding principles, consistent style, and documentation.
