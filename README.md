<h1 align="center">Hi, I'm Chibuzo 👋</h1>

<p align="center">
  <b>Software engineer building full-stack products, from the database to the cloud.</b><br/>
  M.S. Computer Science at Texas A&amp;M University · previously Software Engineer at Oracle
</p>

<p align="center">
  <a href="https://linkedin.com/in/chibuzo-ufomba-498790173"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="mailto:chibuzoufomba15@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white" alt="Email"/></a>
  <a href="https://finance-coach-frontend.vercel.app"><img src="https://img.shields.io/badge/Live%20demo-Finance%20Coach-0e6b5c?style=flat" alt="Finance Coach live demo"/></a>
</p>

---

## What I've built

### 💸 [Finance Coach](https://finance-coach-frontend.vercel.app): an AI personal finance app, live in production
Connect your bank, see where your money goes, set budgets, and ask an AI coach questions about your own spending.
- **Backend:** Java 21 and Spring Boot, with PostgreSQL + pgvector. Plaid syncs bank transactions, Claude (on AWS Bedrock) answers questions using retrieval over the user's own transactions, and Stripe runs subscriptions and plan limits.
- **Infrastructure:** Docker on AWS ECS Fargate behind an ALB, RDS Postgres, all defined in Terraform. GitHub Actions runs 540+ tests (including integration tests on real Postgres with Testcontainers) and CodeQL on every change before deploying.
- **Performance:** tuned PostgreSQL queries to cut API response time from 2.5s to under 500ms.

[Backend](https://github.com/TechByChibuzo/finance-coach-backend) · [Frontend](https://github.com/TechByChibuzo/finance-coach-frontend)

### 🎙️ [Whisper for Nigerian English](https://github.com/TechByChibuzo/whisper-nigerian-english): speech recognition that understands Nigerian accents
Fine-tuned OpenAI's Whisper with LoRA on 13 hours of AfriSpeech-200, cutting word error rate from **29.4% to 16.4%**.

### 🤝 [Job Search Assistant](https://github.com/TechByChibuzo/job-search-assistant): a referral-first job search
Syncs open roles from Greenhouse, Lever and Ashby job boards into one daily inbox, so I can find a role early and reach the right people for a referral. Spring Boot, React and Postgres.

---

## Tools I use

<p>
  <img src="https://skillicons.dev/icons?i=java,spring,python,js,ts,react,postgres,redis,docker,kubernetes,aws,grafana,git" alt="Java, Spring, Python, JavaScript, TypeScript, React, PostgreSQL, Redis, Docker, Kubernetes, AWS, Grafana, Git"/>
</p>
