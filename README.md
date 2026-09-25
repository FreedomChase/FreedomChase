## Shaun Cheeseman — Málaga, Spain

I build, ship and operate production software. Working systems with real users, real
payments and real uptime — not slide decks, not mockups, not proposals.

Most of my work lives in private repositories, either because it is a commercial
product or because it belongs to a client. So this profile is thin by necessity,
not by activity. What follows is what I actually do.

### What I build

**Spanish e-invoicing and tax compliance.** A VeriFactu/AEAT platform implementing
RD 1007/2023 — cryptographic hash-chaining across invoices, immutable append-only
records, QR identifiers, real-time submission to the tax agency, and the mTLS
certificate flow that authenticates it. Multi-tenant, in production.

**Small SaaS products, end to end.** A queue-management service, a web-push
notification platform, a private invoicing microservice, a website security
scanner, a medication-safety tracker, a rural parcel-collection network. Each one
designed, built, deployed and operated by me — including the parts that are not
fun: migrations, billing edge cases, backups, and the 3am ones.

**Client platforms.** CRM, telephony and scheduling systems for companies in Spain
and Sweden. Not named here — they belong to the clients.

### How I work

Python/Flask, Node/Next.js, PostgreSQL, MongoDB, Docker Compose, Stripe,
Cloudflare. Infrastructure I run myself rather than hand to a platform, because
knowing what breaks and why is most of the job.

I care disproportionately about the boring half — whether the migration is
reversible, whether the backup has ever been restored, whether the monitor would
actually tell you. Most production incidents I have seen came from something
nobody checked rather than something nobody knew.

### Mentoring

I take sessions on [Codementor](https://www.codementor.io/). I am most useful when
you are stuck getting something **deployed and working** rather than written:

- a Docker setup that works locally and not in production
- Stripe subscriptions behaving strangely
- a multi-tenant design you are not sure will hold
- a migration you are afraid to run
- an architecture decision you are second-guessing

I will tell you plainly when the answer is "you don't need this yet".
