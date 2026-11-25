# Hi, I'm Carlos Mendoza 👋

**Systems & Computer Engineer · Full-Stack Developer**

I design and build serverless backends that scale without falling over — and the interfaces that use them.

📍 Barranquilla, Colombia · 🌎 Remote with teams in the US and Colombia · 🗣️ Spanish (native), English (B2)

---

## ⚡ Highlight: migrating a production backend without switching it off

**Full-Stack Developer @ My Little Venture LLC** (USA, remote) · *Dec 2025 – Sep 2026*

My Little Venture is a fundraising marketplace for kids and schools. I was the lead developer of the migration from a Python (FastAPI) backend to a **TypeScript monorepo of 16 serverless microservices on AWS Lambda**. Both backends ran in parallel behind prefix-based routing, so every service moved over one at a time with **zero downtime**.

| | |
|---|---|
| **1,000+** | commits — top contributor out of 12 authors |
| **16** | serverless microservices (TypeScript · AWS Lambda) |
| **~640** | REST endpoints with Hono |
| **114 / 260+** | domain slices / use cases (Hexagonal + Vertical Slice) |
| **338** | Vitest suites behind a SonarCloud quality gate |
| **0** | outages during the migration |

- **Architecture:** Hexagonal + Vertical Slice on pnpm workspaces. Ports isolate the domain from DynamoDB, Cognito and Stripe. Shared Zod contracts give end-to-end typing with the Next.js frontend.
- **Integrations:** end-to-end Stripe Connect (onboarding, bank verification, transfers, payouts, webhooks), Zoho Sign, Algolia, OpenAI and AWS Rekognition.
- **Events:** SQS queues and consumers, scheduled jobs, and compensation events with automatic retries.
- **Infra & quality:** Terraform, and Bitbucket CI/CD that runs lint → tests → quality gate → dev/uat/prod. Along the way I closed 100+ SonarQube issues.

<sub>The code belongs to the company: I can talk about architecture and decisions, not share source.</sub>

---

## 🧪 Selected projects

| Project | What it is | Stack |
|---|---|---|
| **[UNINORMA](https://github.com/openlabun/UNINORMA)** | Regulations assistant for Universidad del Norte. An SLM (Qwen 2.5 1.5B) with RAG that runs 100% locally: every answer cites its source, with no API costs and no data sent to third parties. | Python · FastAPI · ChromaDB · Ollama |
| **Activo360** | Asset and maintenance management for clinics and hospitals: inventory, digital asset records, preventive and corrective work orders, help desk, QR codes, KPIs, PDF/Excel reports and a field app for technicians. | Go · SQLite · Angular 20 · Tailwind v4 |
| **Sewer Network Design** | A 2001 MS-DOS hydraulic engineering program brought to the web and updated to the current Colombian standard (Res. 0330/2017). It computes flows, diameters, slopes and profiles, and works offline. | Go · PostgreSQL · Angular 20 · Playwright |
| **Cotix** *(UnderCodes)* | Digital quoting tool built by a team of 5. | Angular · .NET 9 |
| **ARTEMISA** *(Olympus Analytics)* | Environmental research automation platform: I built the interface layer, sign-in and access control. | Angular · TypeScript |

<sub>Activo360 and Sewer Network Design are private repositories. I'm happy to walk you through them.</sub>

---

## 🛠️ Tech stack

| | |
|---|---|
| **Languages** | TypeScript · JavaScript · Python · Go · C# · SQL |
| **Frontend** | React · Next.js · Angular · Astro · Tailwind |
| **Backend** | Node.js · Hono · FastAPI · .NET · Zod |
| **Cloud & infra** | AWS (Lambda, DynamoDB, Cognito, SQS, SES, S3) · Terraform · Docker · CI/CD |
| **AI** | SLM · RAG · ChromaDB · Ollama · OpenAI API · AWS Rekognition |
| **Data** | DynamoDB · PostgreSQL · MySQL · SQLite |
| **Quality** | Vitest · Playwright · SonarCloud |
| **Architecture** | Microservices · Hexagonal · Vertical Slice · Serverless · Event-driven · Monorepo |

---

## 🎓 Education

- **B.Sc. Systems & Computer Engineering**, Universidad del Norte (2021 – 2026). Distinguished Student 2025 · Innovation Award, Geo Expo-física 2022.
- **Academic exchange**, Universidad de Cantabria, Santander, Spain (Sep 2025 – Jan 2026).

---

## 📫 Let's talk

[![LinkedIn](https://img.shields.io/badge/LinkedIn-carlos--mendoza-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/carlos-mendoza-a77272322/)
[![Email](https://img.shields.io/badge/Email-mendozac744%40gmail.com-E2601B?logo=gmail&logoColor=white)](mailto:mendozac744@gmail.com)

Open to full-stack and backend roles, remote.
