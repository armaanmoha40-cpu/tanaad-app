# TANAAD APP Admin Panel

Next.js + Firebase admin dashboard for TANAAD APP e-wallet/exchange.

## Run locally
```bash
npm install
cp .env.example .env.local
npm run dev
```

## Deploy to Vercel
1. Upload this project to GitHub.
2. Open Vercel and import the GitHub repository.
3. Add the Firebase environment variables from `.env.example`.
4. Deploy.

## Firebase collections expected
- users
- deposits
- withdrawals
- transactions
- notifications

Important: final balance updates should be protected by Firebase security rules or Cloud Functions.
