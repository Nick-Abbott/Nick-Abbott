# Hi, I'm Nick

**Systems engineer & platform architect.** I build systems end-to-end across backend architecture, infrastructure, and developer platforms. I like building abstractions that make other engineers more effective, from composing an API response to improving how teams build and ship software.

## What I build

### [Mosaic](https://github.com/Nick-Abbott/Mosaic)

Mosaic is my Kotlin framework for composable backend data orchestration: **think from the response up, not the database down.** Reusable Tiles describe pieces of a response and compose the data they need, while the framework provides concurrency, request-scoped deduplication, and batching behind that composition model. I built it to keep orchestration concerns from being reimplemented in every endpoint, so response logic stays understandable and individual pieces can be tested in isolation.

### [Chirli](https://chirli.com)

I'm building Chirli, a **social discovery product built around standing intent**. People describe what they want to do, learn, offer, find, or collaborate on, and the system continuously looks for complementary intentions. The idea is that discovery should keep working over time, without requiring people to search at the same moment.

The work spans semantic retrieval and matching, model experimentation, product design, and a Kotlin/React stack. I'm building it end-to-end, including the engineering infrastructure needed to develop and operate it.

## Professional work

At **American Express**, I've spent my career building both high-scale customer-facing systems and the platforms that make other engineers more effective. That includes backend systems serving millions of customers and engineering systems used across many teams.

- **Backend architecture:** APIs, aggregation and data composition, caching, performance, and reusable framework abstractions.
- **Developer platforms:** CI/CD, build systems, monorepo engineering, and tooling for large-scale modernization across Java, Kotlin, and TypeScript ecosystems.
- **Cross-team engineering:** technical direction, shared architecture, and mentoring across team boundaries.

## How I think about engineering

- **Absorb complexity once.** I care about who has to understand the complexity. A framework or platform can justify substantial internals when it gives its consumers a small, understandable interface and removes work they would otherwise repeat.
- **Give people strong defaults.** I prefer tools with clear opinions grounded in real needs. Predictable conventions reduce repeated decisions and divergence, leaving more attention for the problem at hand. Flexibility should earn its place.
- **Improve the system that produces software.** I treat CI, build systems, local environments, and developer tooling as part of product delivery. Architecture also shapes collaboration: a monorepo's value can come from visibility and shared ownership, even when its build mechanics cost more.
- **Design for the next person changing it.** I optimize for reading, debugging, onboarding, and maintenance as well as writing. Explicit code, clear ownership, and familiar structures matter long after the initial implementation.

## Other things I've built

- **Discord platform:** Around 2019, I built and operated a distributed, service-oriented bot platform that reached roughly 2 million users across 4,000 servers, working with a development team of about five.
- **[agent-skills](https://github.com/Nick-Abbott/agent-skills):** Reusable engineering skills for AI-assisted workflows, covering test auditing, proportionate change verification, CI performance, and release safety. These grew out of recurring engineering decisions in Chirli.
- **[NixOS configuration](https://github.com/Nick-Abbott/nixos):** My personal system and development environment, kept as declarative configuration.

## Writing

**[Mosaic: A New Way to Compose Backend Data in Kotlin](https://medium.com/@nick.abbott67/mosaic-a-new-way-to-compose-backend-data-in-kotlin-3da78ec0a684)** is a longer introduction to the framework and its response-first approach.

Selected posts on [LinkedIn](https://www.linkedin.com/in/nicholas-abbott):

- **[Maybe Java Was Right All Along](https://www.linkedin.com/posts/nicholas-abbott_maybe-java-was-right-all-along-for-decades-activity-7377515965531488256-sWmX):** explicitness, clarity, and optimizing software for maintenance.
- **[A monorepo won't fix your code](https://www.linkedin.com/posts/nicholas-abbott_a-monorepo-wont-fix-your-code-monorepos-activity-7387645434342772736-okMN):** the organizational reasons for shared repositories, alongside their technical costs.
- **[Simplicity is overrated](https://www.linkedin.com/posts/nicholas-abbott_simplicity-is-overrated-we-want-code-that-activity-7379568462634876928-IyXM):** absorbing complexity inside a platform so its consumers don't have to.
- **[Engineers crave rules](https://www.linkedin.com/posts/nicholas-abbott_engineers-crave-rules-we-like-to-tell-ourselves-activity-7382580704955731968-vRML):** opinionated tools, strong defaults, and predictability.

## Elsewhere

[LinkedIn](https://www.linkedin.com/in/nicholas-abbott)
