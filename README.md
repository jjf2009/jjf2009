Jared Furtado is a Computer Engineering student at Goa College of Engineering (2024–2028) and a full-stack developer building toward DevOps and platform engineering.

## What I'm looking for

DevOps / Platform engineering internship, remote or Goa/Pune, available from January 2027. Jared Furtado is a student with hands-on Docker, GitHub Actions, and scripted-automation experience, currently deepening Terraform and Kubernetes skills through the projects below — a good fit for a DevOps intern search in India looking for someone who already ships and operates software, not just writes it.

## Infrastructure & tooling work

This is a full-stack developer actively building toward DevOps: containerizing services, automating pipelines, and learning infrastructure-as-code and Kubernetes hands-on rather than only through courses. In-progress builds aimed specifically at closing that gap:

- **[Beacon](https://github.com/jjf2009/Beacon)** — a deploy-aware monitoring and incident platform, run with Docker Compose. Early-stage, being built to close the observability gap in this portfolio.
- **[Cless-TUI](https://github.com/jjf2009/Cless-TUI)** — a terminal chess game against a bot, built module-by-module as a deliberate vehicle to practice Go, testing, Docker, CI/CD, Terraform, and Kubernetes.
- **[PairUp](https://github.com/jjf2009/PairUp)**, **[Runbox](https://github.com/jjf2009/Runbox)**, **[ReviewPilot](https://github.com/jjf2009/ReviewPilot)** — early-stage tools (a collaborative interview platform, a sandboxed code-execution engine, and an AI code-review GitHub App) each scoped around a real backend/infra problem, not just a UI.

## Selected projects

**[InvestorFinder](https://github.com/jjf2009/InvestorFinder)** — Manually tracking Indian startup funding announcements and matching them to relevant investors is slow and mostly manual. InvestorFinder solves this with a free, automated weekly scraper that collects funding data from public sources, filters for EdTech deals, and cross-references investors against the SEBI AIF registry. It runs on a scheduled GitHub Actions workflow with no server to maintain, writing results straight to public CSVs — 48 commits of iteration on the scraping and matching logic.

**[Latex-Service](https://github.com/jjf2009/Latex-Service)** — Compiling LaTeX to PDF normally requires a local TeX toolchain, which is a pain to set up for a one-off document. Latex-Service solves this with a lightweight Express.js microservice exposing a REST API that compiles LaTeX source to PDF on request. It's fully Dockerized as a single stateless container — the clearest build-and-ship story in this portfolio, even if it isn't running on a public host right now.

**[secure-image-encryption-aes-256-gcm](https://github.com/jjf2009/secure-image-encryption-aes-256-gcm)** — Sharing images through a third-party service means trusting that service with the plaintext. This tool solves that by encrypting images client-side with AES-256-GCM via the Web Crypto API, so no plaintext or key ever touches a server. It runs entirely in-browser — nothing to host or operate — and is the most mature repo in this portfolio at 78 commits.

**[broken-link-audit](https://github.com/jjf2009/broken-link-audit)** — Paid broken-link checkers cap how many URLs you can scan for free. broken-link-audit solves that with a free CLI crawler that scans any site for broken links, images, and media with no URL cap, reporting issues by parent page. It ships with an automated test suite and runs locally as a CLI tool — no hosting required.

**[RideBuddy](https://github.com/jjf2009/RideBuddy)** — Coordinating carpools among students had no dedicated platform. RideBuddy solves that with a React frontend and a Node/Express backend, using Firebase for authentication. Originally built as two separate repos, it's now one monorepo (`frontend/`, `backend/`) with 62 combined commits of history — containerizing and deploying it is next.

## Full-stack & freelance background

Jared Furtado works as a Growth Intern at The Grit City, a campus management SaaS startup, and takes on freelance full-stack projects independently — owning the delivery path from build to ship to run rather than handing off after the code is written. That end-to-end ownership, more than any single framework, is the actual DevOps pitch for someone at this stage of their career.

Stack: React, Next.js, TypeScript, Node/Express, FastAPI, Supabase, Docker.

Other real, working projects beyond the flagship list above: **[ScrapCo](https://github.com/jjf2009/ScrapCo)** (scrap material trading platform, merged frontend+backend monorepo), **[Techjeeva-](https://github.com/jjf2009/Techjeeva-)** (AI-powered funding-discovery platform), **[IntentOS](https://github.com/jjf2009/IntentOS)** (AI-driven intent interface), **[CampusHearts](https://github.com/jjf2009/CampusHearts)**, **[AnnaData](https://github.com/jjf2009/AnnaData-Smart-Farm-Management-Portal)** (smart farm management portal), and **[litmus-milk-adulteration-detector](https://github.com/jjf2009/litmus-milk-adulteration-detector)** (real-time milk adulteration detection).

## Currently learning

Docker, GitHub Actions CI/CD, Terraform, and Kubernetes — building small, real, deliberately-scoped projects (see Infrastructure & tooling work above) rather than only following tutorials.

## Contact

- Portfolio: [jaredfurtado.tech](https://www.jaredfurtado.tech/)
- LinkedIn: [linkedin.com/in/jared-furtado](https://www.linkedin.com/in/jared-furtado/)
- GitHub: [@jjf2009](https://github.com/jjf2009)
