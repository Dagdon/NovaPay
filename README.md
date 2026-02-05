
NovaPay 🚀
NovaPay is a production-ready, invoicing system built on the Stellar network. It enables freelancers and small businesses to issue professional invoices and receive payments in USDC, ensuring fast transactions and minimal fees across borders.

🛠 Tech Stack
Backend: Node.js + NestJS (Modular Architecture)

Frontend: Next.js + Tailwind CSS

Database: PostgreSQL + Prisma ORM

Payments: Stellar SDK (USDC on Stellar)

Authentication: JWT

Testing: Jest + Supertest

✨ Core Features
Invoice Management: Create, track, and manage invoices with ease.

Crypto Payments: Native support for Stellar USDC payments.

Automated Verification: On-chain payment detection using unique Stellar memos.

Client Portal: Public-facing links for clients to view and pay invoices instantly.

Business Profiles: Customizable business details for professional billing.

🚀 Getting Started
Prerequisites
Node.js (v18+)

Docker & Docker-Compose

A Stellar Testnet account (for development)

Installation
Clone the repository:

Bash
git clone https://github.com/your-username/novapay.git
cd novapay
Install dependencies:

Bash
npm install
Setup Environment: Copy .env.example to .env and fill in your database and Stellar credentials.

Spin up the database:

Bash
docker-compose up -d
Run Migrations:

Bash
npx prisma migrate dev
Start Development Server:

Bash
npm run start:dev
🧪 Testing
We aim for high reliability. Run the test suite to ensure everything is working:

Bash
# Unit tests
npm run test

# E2E tests
npm run test:e2e

# Coverage report
npm run test:cov
