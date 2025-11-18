# SENIOR SOFTWARE ENGINEER

**Location**: UK
**LinkedIn**: [Profile removed for privacy]

## OBJECTIVE

Senior Software Engineer with 5+ years of experience delivering secure, scalable cloud platforms and AI-driven solutions. Skilled in AWS, distributed systems, and automation, with a proven record of working closely with cross-functional teams, mentoring peers, and driving collaborative delivery. Passionate about building innovative systems and leveraging technology to solve real-world problems.

## EDUCATION

**Master of Science in Artificial Intelligence** - UK University - 2022 – 2025

**Master of Engineering in Electrical and Electronic Engineering** - UK University - 2012 – 2016

## CERTIFICATIONS

- AWS Certified AI Practitioner - Sep 2024
- AWS Certified Solutions Architect – Associate - Jun 2023
- AWS Certified Cloud Practitioner - May 2023

## SKILLS

**Programming**: Python, TypeScript, JavaScript, React, Nest.js, Node.js

**Cloud & DevOps**: AWS (Lambda, Step Functions, S3, EC2, CloudWatch, Bedrock, Secrets Manager), Google Cloud, Terraform, Docker, GitLab CI/CD, Jenkins, Amazon Linux (golden images), Vault

**Data & AI**: Elasticsearch, Kibana (Maps, Spaces, Claims), Jupyter Notebook, Machine Learning, Reinforcement Learning

**Infra & Messaging**: Redis, RabbitMQ, NATS, MySQL, PostgreSQL, Microservices Architecture

**Monitoring & Security**: Prometheus, ELK Stack, Splunk, CloudWatch Alarms, SonarQube, Nexus Scanning, Compliance Pipelines

**Tools & APIs**: Swagger/OpenAPI, Pact Testing, Firebase, Jira, Confluence, Salesforce, Adobe Sign, DocuSign, WSO2 Identity Server (SSO)

**Soft Skills**: Leadership, Agile/Scrum, Stakeholder Management, Mentoring, Cross-functional Collaboration

## PROJECTS

### Robotics Navigation System
- Built autonomous navigation models for a TurtleBot in a 3D Gazebo simulation using reinforcement learning (Sarsa algorithm)
- Implemented tabular, linear, and non-linear function approximation methods to improve policy learning, path planning, and obstacle avoidance
- Engineered an end-to-end robotics pipeline by integrating Python, ROS, and Jupyter Notebook for simulation, control, and experimentation
- Applied real-time state-action value updates and exploration strategies, demonstrating practical reinforcement learning in robotics navigation

## EXPERIENCE

### Senior Software Engineer
**UK Home Office** - Jan 2024 – Present - UK Region

- Solely initiated development of a greenfield project within NCDS, initially deployed on Elastic Cloud Enterprise (ECE) and later re-architected into a custom multi-Availability Zone Elasticsearch + Kibana cluster on AWS EC2 using Terraform. Grew the team from 2 to 4 developers and 4 DevOps engineers
- Identified critical limitations in ECE and designed a fully managed solution on AWS EC2. Provisioned dedicated Elasticsearch and Kibana nodes per Availability Zone for high availability and fault tolerance
- Deployed Elasticsearch and Kibana nodes on hardened Amazon Linux golden images with Vault for secret management and CloudWatch alarms for monitoring
- Dockerised Elasticsearch and Kibana nodes with persistent data volumes and implemented daily automated index-level snapshots to S3
- Engineered a multi-tenant access model: dynamically mapped organisation id values to Kibana claims, binding each organisation to an isolated Kibana space
- Integrated tenancy with WSO2 Identity Server (SSO), achieving organisation-aware authentication and authorisation across React, Express, Elasticsearch, and Kibana
- Designed and delivered a serverless ingestion pipeline: S3 event → AWS Lambda → Step Functions, implementing safe retry logic, concurrency controls, and dead-letter queues
- Introduced a shared Python data model library to unify data definitions across ten AWS Lambda functions, using dataclasses instead of ORMs for improved cold-start performance
- Delivered GDPR compliance by design: implemented automated housekeeping Lambdas that permanently deleted PII after 30 days
- Defined a comprehensive CI/CD pipeline using GitLab CI, SonarQube, and Nexus IQ. Enforced strict quality gates: linting, test coverage ≥ 80%, vulnerability scanning
- Led architectural reviews with senior government architects. Challenged proposals and advocated for secure, standardised approaches
- Designed and built the React front-end from scratch, adhering to GOV.UK Design System (GDS) standards and accessibility requirements
- Developed a secure Express.js backend service to mitigate CORS issues introduced by WSO2 SSO
- Integrated Liquibase into the deployment process for schema migrations and seeding reference data
- Led the QAT enablement strategy from the ground up. Provisioned AWS roles, created Feature Test environment, and developed Jenkins test helpers
- Planned and coordinated a structured multi-stage test process (FT → SIT → UAT → Production)
- Delivered advanced geospatial dashboards in Kibana Maps
- Integrated Splunk with ELK for centralised logging, protective monitoring, and compliance reporting
- Recognised with a company performance award for outstanding delivery, technical innovation, and impact on scalability, security, and engineering quality

### Senior Software Engineer
**Technology Company** - Nov 2021 – Jan 2024 - UK Region

- Worked in a fast-paced, high-growth startup across staffing and payroll applications
- Built Nest.js Webhooks and API integrations connecting payroll system with workforce management platforms
- Built the payment ingestion pipeline to process shift approvals for companies with weekly, biweekly, and monthly pay cycles
- Improved database performance by removing redundant writes and adding caching/deduplication
- Ensured financial accuracy by storing all monetary values as integer pennies
- Integrated with lending service to manage lending volumes, predicting required funds based on payroll trends
- Contributed to front-end applications: maintained Angular and developed a React Partner Portal from scratch
- Authored modular Nest.js APIs with Swagger/OpenAPI documentation
- Designed a job-matching algorithm using linear regression to predict worker suitability
- Acted as a technical liaison for partner integrations and production incidents

### Software Engineer / Developer (Earlier Roles)
**Legal Technology Companies** - Mar 2018 – Nov 2021 - UK Region

[Earlier experience anonymized for privacy]

---

**Note**: This CV has been anonymized by removing personal identifying information including name, specific university names, LinkedIn profile URL, and specific company names where appropriate. Location has been generalized to "UK Region" instead of specific cities.
