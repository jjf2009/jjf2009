Hi, I'm Jared Furtado, a Computer Engineering student at Goa College of Engineering (2024–2028). I'm a full-stack developer building toward DevOps and platform engineering.

## Infrastructure & tooling work

I'm building toward DevOps hands-on rather than only through courses: containerizing services, automating pipelines, and learning infrastructure-as-code and Kubernetes. These in-progress builds are aimed at closing that gap:

- **[Beacon](https://github.com/jjf2009/Beacon)** — a deploy-aware monitoring and incident platform, run with Docker Compose. Early stage; I'm building it to close the observability gap in my portfolio.
- **[Cless-TUI](https://github.com/jjf2009/Cless-TUI)** — a terminal chess game against a bot, which I'm building module by module as a deliberate way to practise Go, testing, Docker, CI/CD, Terraform and Kubernetes.
- **[PairUp](https://github.com/jjf2009/PairUp)**, **[Runbox](https://github.com/jjf2009/Runbox)**, **[ReviewPilot](https://github.com/jjf2009/ReviewPilot)** — early-stage tools (a collaborative interview platform, a sandboxed code-execution engine, and an AI code-review GitHub App), each scoped around a real backend/infra problem, not just a UI.

## Selected projects

**[InvestorFinder](https://github.com/jjf2009/InvestorFinder)** — Tracking Indian startup funding announcements and matching them to relevant investors is slow and mostly manual. I built a free, automated weekly scraper that collects funding data from public sources, filters for EdTech deals, and cross-references investors against the SEBI AIF registry. It runs on a scheduled GitHub Actions workflow with no server to maintain, writing results straight to public CSVs — 48 commits of iteration on the scraping and matching logic.

**[Latex-Service](https://github.com/jjf2009/Latex-Service)** — Compiling LaTeX to PDF normally needs a local TeX toolchain, which is a pain to set up for a one-off document. I built a lightweight Express.js microservice with a REST API that compiles LaTeX source to PDF on request. It's fully Dockerized as a single stateless container — my clearest build-and-ship project, even though it isn't running on a public host right now.

**[secure-image-encryption-aes-256-gcm](https://github.com/jjf2009/secure-image-encryption-aes-256-gcm)** — Sharing images through a third-party service means trusting that service with the plaintext. My tool encrypts images client-side with AES-256-GCM via the Web Crypto API, so no plaintext or key ever touches a server. It runs entirely in the browser — nothing to host or operate — and at 78 commits it's my most mature repo.

**[broken-link-audit](https://github.com/jjf2009/broken-link-audit)** — Paid broken-link checkers cap how many URLs you can scan for free. I built a free CLI crawler that scans any site for broken links, images and media with no URL cap, reporting issues by parent page. It ships with an automated test suite and runs locally — no hosting required.

**[RideBuddy](https://github.com/jjf2009/RideBuddy)** — There was no dedicated way for students to coordinate carpools. I built RideBuddy with a React frontend and a Node/Express backend, using Firebase for authentication. It started as two separate repos and is now one monorepo (`frontend/`, `backend/`) with 62 combined commits of history — containerizing and deploying it is next.

## Experience & leadership

- **Vice President, GEC Coders Club** (Aug 2026 – present) — promoted from Event Coordinator (Jul 2025 – Aug 2026), where I ran technical workshops and coding competitions and mentored juniors.
- **Freelance full-stack developer** (Dec 2025 – Aug 2026) — I delivered two client projects independently, owning the path from build to ship to run: the [Global Tourist Centre](https://globaltouristcentre.com/) website (moved to Next.js with German, French, Russian and Italian versions) and [Techjeeva](https://github.com/jjf2009/Techjeeva-) for FIIRE Forum. That end-to-end ownership, more than any single framework, is what draws me to DevOps.
- **Sales Intern, Avyott** (Dec 2025 – Jan 2026) — B2B outreach for a text AI agent product.

## Stack & other projects

Stack: React, Next.js, TypeScript, Node/Express, FastAPI, Supabase, Docker.

Other working projects of mine: **[ScrapCo](https://github.com/jjf2009/ScrapCo)** (scrap material trading platform, merged frontend+backend monorepo), **[IntentOS](https://github.com/jjf2009/IntentOS)** (AI-driven intent interface), **[CampusHearts](https://github.com/jjf2009/CampusHearts)**, **[AnnaData](https://github.com/jjf2009/AnnaData-Smart-Farm-Management-Portal)** (smart farm management portal), and **[litmus-milk-adulteration-detector](https://github.com/jjf2009/litmus-milk-adulteration-detector)** (real-time milk adulteration detection).

## Hackathons

I've taken part in eight hackathons across Goa since 2024, most recently with my team **Qbits** at the **Orix Hackathon 2026** (hosted by McLaren Strategic Solutions), where we received trophies and certificates of achievement. The others: Build with AI Hackathon 2026 (AgriTech, GDG Goa), PCCE Hackathon 2026, Goa University Hackathon 2025, Goa Police Hackathon 2025, AIEM Hackathon 2024, InternSpirit Hackathon 2024 and NIT Goa Hackathon 2024.

## Currently learning

Docker, GitHub Actions CI/CD, Terraform and Kubernetes — by building small, real, deliberately scoped projects (see Infrastructure & tooling work above) rather than only following tutorials.

## Contact

- Portfolio: [jaredfurtado.tech](https://www.jaredfurtado.tech/)
- LinkedIn: [linkedin.com/in/jared-furtado](https://www.linkedin.com/in/jared-furtado/)
- GitHub: [@jjf2009](https://github.com/jjf2009)
