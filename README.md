# Gotham Security Corp — Backend API

The core REST API powering Gotham Security Corp's security intelligence platform.

## Tech Stack

- **Runtime:** Node.js 20 (LTS)
- **Framework:** Express.js
- **Database:** PostgreSQL 15
- **Cache:** Redis 7
- **Auth:** JWT + OAuth2

## Getting Started

```bash
npm install
cp .env.example .env   # Fill in your local values
npm run dev
```

## Contributors

- alfred@gotham-security.com (Lead Backend)
- lucius.fox@gotham-security.com (Infrastructure)
- bruce.wayne@gotham-security.com (Security Audit)

## Deployment

CI/CD is handled via GitHub Actions. See `.github/workflows/deploy.yml`.

Staging deploys automatically on push to `develop`.  
Production requires manual approval.

## Documentation

API docs: https://docs.gotham-security.com/api/v2
