## Sai Anish Pinninti

Cybersecurity + AI engineer in training. ESAIP Angers, Group 04, class of 2026 cohort. I build security and AI tools that are small, useful, and honest about what they do.

Bilingual French / English. Comfortable across the stack but happiest where the security boundary meets the product surface — auth flows, SSRF guards, prompt handling, header policy.

---

### Selected projects

| Project | What it does | Stack |
| --- | --- | --- |
| **[bastion](https://github.com/AR-base/bastion)** | Passive website security scanner for small businesses, with a plain-English AI risk briefing. Defense-in-depth SSRF guard, full security-header analysis, CI-tested. | Cloudflare Workers · Claude · vanilla JS |
| **[phishlens](https://github.com/AR-base/phishlens)** | Interactive phishing-awareness training: realistic email simulator, AI tutor, and live URL inspector. Falls back to a curated KB when the model is unreachable. | Vercel Functions · Claude · vanilla JS |
| **[esaip-ai-assistant](https://github.com/AR-base/esaip-ai-assistant)** | Bilingual chat assistant for ESAIP students and faculty. Streaming responses, image / PDF attachments, role-aware UI. | Vercel Edge · Claude · vanilla JS |

Each project ships with a `SECURITY.md`, an explicit threat model in the README, and tests where the surface justifies them.

---

### What I care about when shipping

- **Defense in depth.** One control fails; another catches it. Headers, then CSP, then size caps, then rate limits.
- **Honest scope.** Demos that don't pretend to be products; products that don't pretend to be magic.
- **Readable code.** Comments where the *why* is non-obvious, never where the *what* already is.
- **Pure functions where possible.** Easier to test, easier to reason about under attack.

---

### Currently exploring

Cloudflare Workers, Durable Objects, Vectorize, the Workers Rate Limiting API. Anthropic prompt caching and structured tool use. Threat modeling against LLM-mediated apps.

---

### Reach me

GitHub: [@AR-base](https://github.com/AR-base) · Email: psaianish2001@gmail.com
