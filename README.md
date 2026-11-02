<h1 align="center">Chibuzo Ufomba</h1>

<p align="center">
  Software Engineer · M.S. Computer Science, Texas A&amp;M University
</p>

<p align="center">
  <a href="https://linkedin.com/in/chibuzo-ufomba-498790173"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="mailto:chibuzoufomba15@gmail.com"><img src="https://img.shields.io/badge/Email-24292F?style=flat-square&logo=gmail&logoColor=white" alt="Email"/></a>
  <a href="https://finance-coach-frontend.vercel.app"><img src="https://img.shields.io/badge/Finance%20Coach-Live%20demo-24292F?style=flat-square" alt="Finance Coach live demo"/></a>
</p>

---

I'm a software engineer who builds full-stack products end to end: backend services, web frontends, databases and the cloud infrastructure they run on. I was a Software Engineer at Oracle, working on REST APIs and containerized applications, and I'm currently completing a Master's in Computer Science at Texas A&M University.

## Selected projects

**[Finance Coach](https://finance-coach-frontend.vercel.app)**: AI-powered personal finance application, deployed to production  
Users connect their bank accounts, track spending against budgets, and ask an AI coach questions about their own finances.
- Java 21 and Spring Boot backend on PostgreSQL with pgvector. Integrates Plaid for bank data, Claude on AWS Bedrock with retrieval over the user's transactions, and Stripe for subscriptions and plan limits.
- Runs on AWS ECS Fargate behind an Application Load Balancer, with RDS PostgreSQL, all provisioned with Terraform. GitHub Actions runs 540+ tests, including integration tests against PostgreSQL with Testcontainers, plus CodeQL analysis before every deployment.
- Reduced API response time from 2.5s to under 500ms through PostgreSQL query optimization.

[Backend repository](https://github.com/TechByChibuzo/finance-coach-backend) · [Frontend repository](https://github.com/TechByChibuzo/finance-coach-frontend)

**[Whisper for Nigerian English](https://github.com/TechByChibuzo/whisper-nigerian-english)**: speech recognition for Nigerian-accented English  
Fine-tuned OpenAI Whisper with LoRA on 13 hours of AfriSpeech-200 audio, reducing word error rate from 29.4% to 16.4%.

**[Job Search Assistant](https://github.com/TechByChibuzo/job-search-assistant)**: referral-first job search platform  
Aggregates open roles from the Greenhouse, Lever and Ashby job board APIs into a single daily feed, to support timely, targeted referral outreach. Built with Spring Boot, React and PostgreSQL.

## Experience

**Software Engineer**, Oracle  
Built REST APIs and containerized applications, working across the full stack.

## Education

**M.S. Computer Science**, Texas A&amp;M University (in progress)

## Technical skills

**Languages:** Java, Python, JavaScript, TypeScript, SQL  
**Frameworks:** Spring Boot, React  
**Data:** PostgreSQL, pgvector, Redis  
**Cloud and DevOps:** AWS (ECS, RDS, Bedrock), Terraform, Docker, Kubernetes, GitHub Actions, Grafana  
**Testing:** JUnit, Mockito, Testcontainers
