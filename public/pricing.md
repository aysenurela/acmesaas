# Acme SaaS — Pricing

> All prices are monthly, per team. Amounts are in major currency units (already divided by 100).
> SSO is only included on the Enterprise plan.
> To sign up: https://acmesaas-nine.vercel.app/signup
> To view plans: https://acmesaas-nine.vercel.app/features

---

## Plans overview

| Plan            | Employees | Responses/year | SSO |
|-----------------|-----------|----------------|-----|
| Starter         | 1–3       | 5,000          | No  |
| Team Advantage  | 4–10      | 50,000         | No  |
| Team Premier    | 11–50     | 100,000        | No  |
| Team Enterprise | 51+       | 200,000        | Yes |

---

## Prices by country

| Plan            | US (USD) | Canada (CAD) | Costa Rica (CRC) | UK (GBP) | Australia (AUD) |
|-----------------|----------|--------------|------------------|----------|-----------------|
| Starter         | Free     | Free         | Free             | Free     | Free            |
| Team Advantage  | $59      | CA$15        | ₡309             | £8       | AU$15           |
| Team Premier    | $119     | CA$30        | ₡619             | £16      | AU$30           |
| Team Enterprise | $249     | CA$70        | ₡1,299           | £40      | AU$75           |

Europe (EUR): Advantage €10, Premier €20, Enterprise €50.
Turkey (TRY): prices only available via the live API at https://acmesaas-nine.vercel.app/api/pricing/TR

---

## Country codes (ISO 3166-1)

| Country        | Code | Currency |
|----------------|------|----------|
| United States  | US   | USD      |
| Canada         | CA   | CAD      |
| Costa Rica     | CR   | CRC      |
| United Kingdom | GB   | GBP      |
| France         | FR   | EUR      |
| Germany        | DE   | EUR      |
| Spain          | ES   | EUR      |
| Italy          | IT   | EUR      |
| Australia      | AU   | AUD      |
| Turkey         | TR   | TRY      |

---

## Plan selection rules

- Team size 1–3   → Starter (free)
- Team size 4–10  → Team Advantage
- Team size 11–50 → Team Premier
- Team size 51+   → Team Enterprise
- Needs SSO       → Always Team Enterprise, regardless of team size

---

## Notes

- All plans billed monthly
- The Starter plan is free and does not appear on the /features page (API-only)
- Signup and account management must be completed via the website or a full-access API integration
