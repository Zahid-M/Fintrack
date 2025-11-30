# Fintrack
FinTrack is a financial tracking tool built for HCP.  
The goal is to help users manage expenses, visualize spending, and learn basic financial literacy.

Design Doc: https://docs.google.com/document/d/1k9O3kZutrK01CDcj7YHmQm348ES5ga0-YMlCD79P77A/edit?tab=t.0#heading=h.rofi4avkroij

---

## Features (MVP)
(below are subject to change)
- Track expenses and categorize transactions  
- View budgets and spending summaries  
- Dashboard with visual charts and insights  
- User accounts for RSO leaders  
- Secure data storage using PostgreSQL 

---

## Post MVP Goals
- Advanced data visualizations  
- Expense forecasting  
- Role-based access for multiple users  
- Mobile-friendly dashboard 

---

## Problems being solved
- Keep records of finances
- Track funding from multiple sources
- Understand spending patterns

---

## Tech Stack

### Frontend
- Framework: (TBD)
- Design System: https://m3.material.io/

### Backend
- API's for data retrieval
- Language/Framework: (TBD)

### Database
PostgreSQL
Justification: Having a table to represent our data is the most appropriate choice for our project, as the data we’re storing is simple, making any dynamic storing of data unnecessary and complicated.

### CI (Continious Integration)
- Version Control: GitHub
- Automated Testing: (TBD)
- Automated Builds: Jenkins + Gradle

### CD (Continious Development)
- Infrastructure as Code (IaC): Define infrastructure using code (e.g., Terraform or AWS CloudFormation) to ensure consistent environments.
- Artifact Creation: Docker images
- Deployment Scripting: Ansible, Kubernetes, or Terraform
- Pipeline Orchestration: Tekton Pipelines
- Blue-Green Deployments: Implement blue-green deployments to minimize downtime during releases.

