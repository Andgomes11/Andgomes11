# Anderson Gomes

Tech lead and software engineer. I build AI platforms end to end — architecture,
payments, infrastructure, and the operational work that keeps them running.

### What I'm building

**[as-advertised](https://github.com/Andgomes11/as-advertised)** — a rules
engine that checks whether a digital offer delivers what its ad promised, and
whether the domain selling it belongs to the brand it invokes.

It started with a real ad: *“50 items”* next to *“R$ 17.90”*, when fifty items
cost R$ 315. No claim in it was false — the deception lived in the composition and
in one omitted phrase. Two sweeps over 50 Brazilian consumer brands, precision
measured round to round, every positive finding opened by hand before it counted.

**[conferente](https://github.com/Andgomes11/conferente)** — an agent harness
that never presents unchecked model output as checked. Verification is code, never
a model call: every verifier returns *passed*, *failed* or *could not check*, and
that third state survives all the way to whoever reads the answer.

### What I do at work

I lead [career.guide](https://career.guide/) technically: an AI career-guidance
platform that has reached **350k+ users**, peaking at ~2,000 a day, B2C and B2B,
in three languages.

- Architected the stack of our new mobile product — a TypeScript monorepo with
  NestJS, PostgreSQL, React Native (Expo) and Next.js on Cloudflare Workers,
  contract-first APIs, and a CI pipeline with one required gate
- Built the AI-agent development harness the team ships with — enforced agent
  rules, specialised review subagents, and hooks that protect tests and migrations
- Multi-agent AI architecture — specialised agents, persistent memory, RAG over
  vector stores
- Payments across Stripe, dLocal, PayPal and Pix, routed per country
- AWS serverless throughout — Lambda, API Gateway, SQS, S3, MongoDB Atlas, with
  standardised CI/CD

I came into this from QA automation, which is where the habit of not trusting a
green result started.

### How I work

I measure before I claim. On the project above that meant opening every positive
finding by hand before reporting it — six of eight died there, and the rule is
written into the repository rather than into a slide. When a number moves between
runs I look for a misbehaving source before I credit my own fix, because a source
that degrades quietly degrades toward *fewer* findings, and that reads as “nothing
here”.

### Stack

TypeScript · Node · NestJS · PostgreSQL · Prisma · React Native · Next.js · Python ·
AWS Lambda · API Gateway · SQS · Cloudflare · Docker · MongoDB · Cypress · GitHub Actions

### Reach me

**andersongds37@gmail.com** · [linkedin.com/in/andgomes](https://www.linkedin.com/in/andgomes)

Open to full-time remote roles with US teams (US time zones), and to consulting —
strongest in applied AI, platform architecture, payment integrations, and
serverless.
