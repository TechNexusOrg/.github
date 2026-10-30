# TechNexusOrg

> **Build real software. Make real contributions. Build public proof of work.**

Welcome to the GitHub home of **TechNexusOrg**. We are a student-led open-source engineering ecosystem built to bridge the gap between academic computer science education and industry-grade production engineering.

This is not a certificate website. Credentials, passports, and fellowships are the direct cryptographic output of verified GitHub contribution histories, never the primary product.

---

## 🚀 Ecosystem Map & Quick Links

| Area | Purpose | Direct Link |
| :--- | :--- | :--- |
| 🌐 **Contributor Platform** | Issue claims, onboarding, and developer passports | [platform](https://github.com/TechNexusOrg/platform) |
| 📚 **Learning Tracks** | Self-paced terminal exercises, architecture deep-dives, and capstones | [/learn](https://github.com/TechNexusOrg/platform/tree/main/src/app/learn) |
| 💼 **Engineering Fellowships** | Supervised 8-week apprenticeships with maintainer 1-on-1 mentorship | [/internships](https://github.com/TechNexusOrg/platform/tree/main/src/app/internships) |
| 🔐 **Public Verification** | Ed25519 cryptographic credentials and JWKS discovery | [/verify](https://github.com/TechNexusOrg/platform/tree/main/src/app/verify) |
| 📖 **Student Guide** | Comprehensive onboarding manual for complete beginners | [STUDENT_GUIDE.md](https://github.com/TechNexusOrg/platform/blob/main/docs/STUDENT_GUIDE.md) |
| 🛡️ **Privacy & Governance** | Privacy-by-default GDPR compliance and Code of Conduct | [PRIVACY.md](https://github.com/TechNexusOrg/platform/blob/main/PRIVACY.md) |

---

## 🏛️ What Makes TechNexusOrg Different?

### 1. GitHub Evidence as the Sole Source of Truth
Every statistic, passport achievement, and level promotion links directly to immutable GitHub merge events, commit SHAs, and pull requests on official repositories. We never fabricate numbers, contributors, or certificates.

### 2. Ed25519 Cryptographic Verification
All credentials issued by TechNexusOrg are digitally signed using **Ed25519** asymmetric cryptography. Third-party verifiers, universities, and employers can independently verify credentials against our public JWKS key discovery endpoint (`/api/verify/keys`) without trusting arbitrary web claims.

### 3. Maintainer-Led Code Reviews
Contributors receive rigorous, constructive feedback from experienced maintainers covering edge cases, type safety, test coverage, and Conventional Commits conventions.

### 4. Privacy-by-Default Architecture
In compliance with global data privacy principles (GDPR/DPDP), contributor profiles default to private until explicit public consent is granted, with self-service JSON data export and account erasure endpoints.

---

## 📚 Structured Learning Tracks

TechNexusOrg provides structured, self-paced technical learning tracks designed to prepare students for real-world repository contributions:

### Track 1: Linux Fundamentals and Administration
- **Scope:** POSIX shell environment, standard I/O streams, pipelines, and the Filesystem Hierarchy Standard (FHS).
- **Core Topics:** File permissions (rwx, octal, SUID, SGID, Sticky bit), process management, signals (`SIGTERM`, `SIGKILL`), disk mounts (`/etc/fstab`), networking diagnostics (`iproute2`, `ss`), and SSH hardening.
- **Capstone Assignment:** Author and deploy an automated health monitoring daemon managed by a non-root `systemd` service unit with structured `journalctl` telemetry.

### Track 2: Git and Professional Open-Source Development
- **Scope:** Git internals, content-addressable storage (blobs, trees, commits), and Directed Acyclic Graph (DAG) mechanics.
- **Core Topics:** Branching models, 3-way merge versus linear rebasing, Conventional Commits specification, interactive rebasing (`git rebase -i`), resolving merge conflicts, and code review etiquette.
- **Capstone Assignment:** Fork an official repository, author atomic conventional commits, configure GitHub Actions CI status checks, and submit a clean, bisectable Pull Request.

---

## 💼 Supervised Engineering Fellowships

For advanced contributors seeking practical internship experience, TechNexusOrg runs supervised 8-week project-based fellowships:

1. **Platform Engineering & Systems Fellowship (8 Weeks):**
   - High-throughput asynchronous queue processing with PostgreSQL.
   - Hardening GitHub API trust boundaries and webhook HMAC verification.
   - Strict fail-closed production runtime environment configuration.
2. **Full-Stack Open-Source Fellowship (8 Weeks):**
   - Accessible Next.js App Router applications with strict SSR/SSG patterns.
   - Type-safe schema migrations using Drizzle ORM and PostgreSQL.
   - Privacy-by-default GDPR consent workflows and self-service data portability.

### Fellowship Verification Invariants:
- **Offer Letters:** Signed with deterministic SHA-256 verification hashes.
- **Weekly Work Logs:** Mandate verified GitHub PR links, hours logged, and blocker tracking.
- **Graduation Rubrics:** Comprehensive 5-point evaluations across Code Quality, Collaboration, Punctuality, Documentation, and Technical Initiative.

---

## 🛠️ The Standard Contribution Workflow

```text
Visitor
   ↓
1. Join with GitHub (OAuth + JWT Session)
   ↓
2. Complete Profile Onboarding (languages, tools, interests)
   ↓
3. Explore Curated Issues & Claim (7-day lease)
   ↓
4. Fork, Clone, and Develop Locally
   ↓
5. Run Tests & Validation Suite (npm test, npm run typecheck, npm run lint)
   ↓
6. Open Pull Request referencing "Fixes #<issue-id>"
   ↓
7. Maintainer Code Review & Interactive Rebase
   ↓
8. PR Merged into Official Main Branch
   ↓
9. Webhook Automatically Records Merged Contribution & Updates Metrics
   ↓
10. Ed25519-Signed Verifiable Credential Issued to Contributor Passport
```

---

## 🏆 The Founding 1,000

The **Founding 1,000** cohort honors the first 1,000 contributors who successfully complete and merge an approved pull request on official TechNexusOrg repositories.

- Registration alone **never** reserves a slot.
- Membership is awarded sequentially (1 to 1,000) only upon your first verified PR merge.
- Founding contributors receive permanent recognition on the public registry and an immutable Founding 1,000 credential.

---

## 📈 Contributor Levels

| Level | Path | Requirements |
| :--- | :--- | :--- |
| **Explorer** | Entry | Completed onboarding profile |
| **Contributor** | Engineering | At least 1 verified merged PR on an official project |
| **Active Contributor** | Engineering | 3+ verified merged PRs on official projects |
| **Core Contributor** | Engineering | 5+ merged PRs, 2+ peer code reviews, 2+ projects |
| **Maintainer** | Stewardship | Explicit maintainer appointment by organization leads |
| **Project Lead** | Leadership | Architecture ownership and release stewardship |
| **Mentor** | Community | Guidance of early-career contributors through reviews |

---

## 🏛️ For Universities & Training & Placement Offices (TPOs)

TechNexusOrg provides an evidence-based alternative to unverified certificates and campus coding contests:
- **Zero Hallucinated Metrics:** Every student claim links to public, verifiable Git commit logs and pull requests.
- **Institutional Verification:** Training & Placement Officers can independently audit student portfolios via `/verify/[id]` or query our public JWKS endpoint.
- **Structured Syllabi:** Ready-to-deploy curricula aligned with industry engineering expectations.

---

## 🔐 Security & Responsible Disclosure

If you identify a security vulnerability in any TechNexusOrg repository or service, please disclose it responsibly via GitHub Security Advisories or by emailing `security@technexus.org`.
