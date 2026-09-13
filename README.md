<div align="center">

# Noah · @NoahDeployed

**Founder. CTO. Full-stack builder. BC, Canada.**

I build production software

</div>

---

## Stack

<div align="center">

![Stack](https://skillicons.dev/icons?i=ts,nextjs,react,tailwind,supabase,postgres,vercel,python,cs,dotnet,threejs,git,github,figma)

</div>

---

## By the numbers

<div align="center">

![](https://img.shields.io/badge/Commits%20on%20the%20current%20build-1%2C158%20in%2029%20days-7C66F0?style=for-the-badge&labelColor=0d1117)
![](https://img.shields.io/badge/Automated%20checks%20in%20that%20repo-116-7C66F0?style=for-the-badge&labelColor=0d1117)

![](https://img.shields.io/badge/Database%20migrations-144-7C66F0?style=for-the-badge&labelColor=0d1117)
![](https://img.shields.io/badge/TypeScript%20in%20one%20app-90%2C000%20lines-7C66F0?style=for-the-badge&labelColor=0d1117)

![](https://img.shields.io/badge/Tokens%20used%2C%20last%2028%20days-28%20billion-7C66F0?style=for-the-badge&labelColor=0d1117)
![](https://img.shields.io/badge/Claude%20Code%20sessions-739-7C66F0?style=for-the-badge&labelColor=0d1117)
![](https://img.shields.io/badge/Python%20business%20OS-36%2C000%20lines-7C66F0?style=for-the-badge&labelColor=0d1117)

</div>

---

## What I build

I am the technical co-founder of a three-person software company selling to accounting firms, and before that I ran a one-person agency that shipped web products to businesses across BC. I handle the whole thing: architecture, database, security, the desktop side, design, deployment, billing and the customers.

The work I am proudest of is the unglamorous kind. Row-level security on every table. An audit log that a database trigger refuses to let anyone edit. A build that cannot be called done while a single check is red. Software that handles other people's tax records has to be boring in exactly the right places, and making it boring is the hard part.

Started building at 15

---

## Featured work

### Tax document reader for accounting firms
> Next.js 16 · TypeScript · Supabase · Postgres · Stripe · Claude API · C# .NET 8

The current build, and the most serious thing I have made. A CPA drops in whatever a client handed them, a scanned shoebox of twenty to seventy pages, and it comes back as one card per document with every figure read, placed and linked to the exact spot on the page it came from. The preparer checks the work instead of typing it.

- One PDF in, every document inside it split out and read on its own; blank pages, cover sheets and backs of slips recognised and skipped for free
- Every value carries the rectangle it was read from, so clicking a number shows you the paper. Anything the reader was unsure of is flagged and **blocks approval** in three separate places
- Duplicate receipts caught before they double a deduction, and a suspected copy cannot be approved until a person says which one is real
- A Windows desktop agent, 10,000 lines of C#, that lands the finished figures in the firm's own tax software through that software's own import surface. Exact-title verification before the first keystroke, focus loss aborts, every job runs at most once, a persistent stop switch, and a full trail
- 144 migrations, 116 automated checks, CI that scans every push for secrets, PII encrypted at rest with the key kept away from the ciphertext
- A security alarm that wires decoy credentials to a webhook: the moment one is touched, the platform records the hit, snapshots who was signed in, pings the team channel, texts the founders, and locks the doors if it was client data

### The Collective, a professional development platform for ASL interpreters
> Next.js · TypeScript · Supabase · Stripe · Cloudflare R2

Built with a partner for a client in Texas. Interpreters record themselves signing to a prompt and get timestamped feedback from peers and mentors. Certification verification with government ID uploads into private storage behind five-minute signed URLs; paths never reach the browser. Stripe-gated membership tiers, private video hosting on R2, a 14-table schema with row-level security on every table, rate limiting, MIME validation, PKCE auth and server-side sessions throughout.

### A desktop business OS, 36,000 lines of Python
> Python · PyQt5 · Claude API · Stripe API · IMAP/SMTP · Twilio

Built to replace every SaaS tool I was paying for, and it did. An IMAP inbox with AI reply drafting, a bulk outreach engine with deliverability tracking and reply detection, a live Stripe revenue dashboard, an AI calling system with drill-down analytics, and a daily KPI tracker. Ships as a single signed Windows executable.

### Six agents that run a business overnight
> Python · Claude API · Twilio · SMTP

The part of that desktop app most people do not believe until they watch the log. An outbound email agent working through 1,700 leads with personalised copy and a random delay so it never looks like a machine. A reply monitor that sends a booking link the moment someone answers. A diagnostic agent that classifies SMTP errors, rate limits and spam blocks and recovers on its own. An orchestrator that runs outreach in office hours and switches to analysis at night. An AI voice caller that qualifies raw leads and hands the warm ones to a human. It ran unattended while I slept.

### A client site engine for trades businesses
> HTML · CSS · JavaScript · no build step

One configuration object is one complete website. Multi-step lead capture, a trade-aware chatbot with price estimates and an emergency path, and a single CSS variable that recolours the whole site per trade. Sold to real plumbers, electricians and roofers.

### A cinematic 3D studio site
> Three.js · GSAP · Lenis

Full Three.js hero with PBR materials, a real key-and-rim lighting rig, floating animation and a contact shadow, with a scroll-driven camera orbit. Built with the same partner, to sell the two of us as one team.

---

## How I work

Two AI coding agents in one checkout, all day, with the guardrails to make that safe: a commit cannot land while a check is red, a stop hook that refuses to let an agent finish on a broken tree, and a repository that documents every bug that ever passed review with the mechanism that let it through. The agents write a lot of the code. Deciding what is wrong with it is the job.

---

<div align="center">

**Currently:** taking a tax product from ten beta firms to five hundred, and hiring the first engineer.

</div>
