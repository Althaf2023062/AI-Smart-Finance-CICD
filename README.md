# AI Smart Finance Automation System - CI/CD

![CI-CD Pipeline](https://github.com/Althaf2023062/AI-Smart-Finance-CICD/actions/workflows/cicd.yml/badge.svg)

## Project Overview

AI Smart Finance Automation System is an AI-based financial automation application designed to automate financial transaction recording using OCR and AI classification.

The system integrates CI/CD practices using GitHub Actions, Docker, automated testing, and CodeQL security scanning to ensure reliable and consistent software delivery.

---

## Technologies

- Python Flask
- GitHub Actions
- Docker
- CodeQL
- Pytest
- Flake8
- Tesseract OCR
- OpenAI API
- Telegram Bot API
- MySQL

---

## System Workflow

The application workflow includes:

1. User uploads digital receipt
2. OCR extracts transaction information
3. AI classifies expense category
4. Transaction data stored in database
5. Dashboard analytics generated
6. Telegram notification sent automatically

---

## CI/CD Workflow

The CI/CD pipeline includes:

1. Install dependencies
2. Lint validation
3. Unit testing
4. Security scanning using CodeQL
5. Docker image build
6. Staging deployment
7. UAT simulation
8. Production deployment simulation

---

## Branch Strategy

| Branch | Purpose |
|---|---|
| main | Production |
| develop | Development |
| feature/* | Feature development |
| hotfix/* | Bug fixing |

---

## DORA Metrics

| Metrics | Target |
|---|---|
| Deployment Frequency | Daily |
| Lead Time for Changes | < 2 hours |
| Change Failure Rate | < 10% |
| MTTR | < 30 minutes |

---

## Docker Build

```bash
docker build -t ai-finance-app .
```

---

## Run Application

```bash
python app.py
```

---

## Security Features

- Static Application Security Testing (SAST)
- Automated security scanning
- CodeQL analysis
- Dependency validation
- Secure CI/CD workflow

---

## CI/CD Features

- Automated GitHub Actions workflow
- Docker containerization
- Automated linting and testing
- Static Application Security Testing (SAST)
- Multi-stage deployment simulation
- Git Flow branching strategy
- Continuous Integration
- Continuous Deployment

---

## Repository Structure

```text
ai-smart-finance-cicd/
│
├── .github/workflows/
│   ├── cicd.yml
│   └── codeql.yml
│
├── app/
│   ├── app.py
│   ├── ocr.py
│   ├── classifier.py
│   ├── database.py
│   └── notification.py
│
├── tests/
│   └── test_app.py
├── requirements.txt
├── Dockerfile
├── .dockerignore
├── .gitignore
└── README.md
```
