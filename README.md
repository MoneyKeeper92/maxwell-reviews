# Maxwell CPA Review — Review Exchange Pages

Static pages for the Google review → free resource exchange at **reviews.maxwellstudy.com**.

## URLs

| Path | Reward |
|------|--------|
| `/far101` | [FAR Baseline Exam](https://baseline-virid.vercel.app/baseline/8df432faa0c1) |
| `/aud101` | [AUD Exam Textbook](https://textbook.maxwellstudy.com/aud) |
| `/reg101` | [REG Exam Textbook](https://textbook.maxwellstudy.com/reg) |

## Flow

1. Student clicks **Write a Google review** (opens Google in a new tab)
2. After 1.5s, **I've left my review** appears
3. Student pastes review text and submits
4. Reward link is revealed — no backend, no email

Google review link (all pages): https://g.page/r/Cc1qaPpJQPUjEBM/review

## Netlify

- **Publish directory:** `public`
- **Build command:** *(none — static HTML)*
- **Custom domain:** `reviews.maxwellstudy.com`

No environment variables required.
