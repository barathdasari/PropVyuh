---
layout: default
---

# PropVyuh

**Your Chakravyuh against bad home loans. Strategize. Simulate. Strike.**

> India's smartest open-source home buying war room. Zero fluff. Pure numbers.

<a href="dashboard.html" style="display:inline-block;margin:20px 0;padding:14px 36px;background:linear-gradient(135deg,#155799,#159957);color:#fff;font-weight:bold;font-size:1.1rem;border-radius:8px;text-decoration:none;box-shadow:0 4px 14px rgba(21,89,153,0.3);transition:transform 0.2s;">Launch Dashboard &rarr;</a>

---

## What It Does

PropVyuh is a **zero-dependency, single-page simulator** built for Indian home buyers navigating the 2026 market. No sign-ups. No ads. Just math.

- **Compare Banks** — PSU vs Private, EBLR-linked, April 2026 benchmarks (7.10% – 8.25%)
- **Calculate True Cost** — Stamp Duty, Registration, GST with state-specific rates for 13 states
- **Check PMAY Eligibility** — Toggle CLSS subsidy for EWS/LIG/MIG categories (~₹2.30L – ₹2.67L)
- **Simulate Pre-payments** — See exactly how much interest you save and how many years you cut
- **Visualize Everything** — Interactive donut + line charts powered by Chart.js

---

## Feature Matrix

| Module | What You Get |
|--------|-------------|
| **Location Engine** | 13 states — auto-fills Stamp Duty (4%–8%) + Registration |
| **Bank Benchmarks** | SBI, HDFC, ICICI, Axis, Kotak, PSU Banks + Custom Rate |
| **GST Calculator** | RTM: 0% · Affordable: 1% · Under-Construction: 5% (33% land abatement) |
| **PMAY-CLSS** | One-click toggle with EWS/LIG/MIG-I/MIG-II subsidy deduction |
| **Pre-payment Sim** | Month-by-month amortization → Interest Saved + Years Reduced |
| **Cost Donut** | Base Price vs Statutory Costs vs GST vs Loan Interest |
| **Repayment Curves** | Standard vs Accelerated outstanding balance over loan life |

---

## April 2026 Market Snapshot

```
RBI Repo Rate       5.25%  (post successive cuts)
Best Home Loan      7.10%  (PSU Banks)
SBI EBLR            7.25%
HDFC Bank           7.90%
Max LTV             80%    (Min 20% Down Payment)
```

---

## Tech

- **Single HTML file** — no build step, no bundler
- **Zero local dependencies** — only Chart.js via CDN
- **Mobile responsive** — phone, tablet, desktop
- **Dark glassmorphic UI** — built for long planning sessions
- **Indian formatting** — ₹ symbol, Lakh/Crore via `Intl.NumberFormat('en-IN')`

---

<a href="dashboard.html" style="display:inline-block;margin:10px 0;padding:14px 36px;background:linear-gradient(135deg,#155799,#159957);color:#fff;font-weight:bold;font-size:1.1rem;border-radius:8px;text-decoration:none;box-shadow:0 4px 14px rgba(21,89,153,0.3);">Open PropVyuh Dashboard &rarr;</a>

---

<sub>Rates as of April 2026 (RBI Repo: 5.25%) · For educational & planning purposes only · PMAY-CLSS figures approximate per NHB benchmarks</sub>
