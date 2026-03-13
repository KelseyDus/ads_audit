# AuditFlow — Paid Ads Intelligence

## Deploy to Vercel

1. Push this folder to a new GitHub repo
2. Import at vercel.com/new
3. **IMPORTANT — Override build settings:**
   - Build Command: *(leave empty / clear it out)*
   - Output Directory: *(leave empty / clear it out)*
   - Install Command: *(leave empty / clear it out)*
4. Add environment variable: `ANTHROPIC_API_KEY` = your key
5. Deploy

## File Structure

```
auditflow/
├── api/
│   └── anthropic.js   ← Serverless API proxy
├── index.html         ← Entire app (no build needed)
└── vercel.json
```
