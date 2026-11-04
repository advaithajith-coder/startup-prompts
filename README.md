# Startup Intelligence: Prompt Library

A single-page library of **69 AI prompts in 52 sections** that walks a startup idea from problem framing to a final go / no-go verdict. It works for any country: the prompts adapt to the target market you name, covering local city tiers, informal markets, payment methods, legal and compliance rules, and funding sources.

**Live site: https://startup-prompts.vercel.app/**

You can also open `index.html` in any browser. You don't need to install anything, and nothing is sent anywhere.

## What's inside

| Pillar | Focus | Sections |
|---|---|---|
| Phase 0 | Idea intake and problem framing | 2 |
| A | Market intelligence: sizing, competitors, personas, demand, timing | 8 |
| B | Business model and financials: pricing, unit economics, projections, exits | 6 |
| C | Execution and growth: GTM, MVP, 90-day roadmap, SEO, brand | 8 |
| D | Local infrastructure: legal and compliance, regulation, funding landscape for your target country | 3 |
| E | Strategic defense: risks, pre-mortem, devil's advocate, moat, pivots | 6 |
| F | Founder intelligence: founder-market fit, readiness, the final verdict | 7 |
| G | Consulting-grade, stand-alone prompts | 12 |

## How to use it

The prompts read from two plain text files that you keep next to your AI chat:

1. **`context.md`**: write this once before you start. Include your name, the startup idea, the target customer, your **target market** (country or region), the **local currency**, budget, stage and team. Every prompt asks the AI to read it first, and uses the target market for local research and the currency for all money amounts.
2. **`progressive.md`**: an empty file at the start. After you run each section, paste the AI's answer into it. Later sections (marked *Reads progressive.md* in the app) use everything gathered so far, so they don't repeat earlier work and can connect the findings.

A short example `context.md`:

```markdown
Founder: Priya, ex-product manager, 6 years in logistics software
Idea: Route-planning app for small delivery businesses
Target customer: Owners of 5–50 vehicle delivery fleets
Target market: Mexico (start in Guadalajara)
Local currency: MXN
Budget: MXN 400,000 of savings
Stage: Idea, 12 customer interviews done
Team: Solo founder, looking for a technical co-founder
```

Then:

- Run the sections in **execution order**, shown on each section as "⚡ Execution order". Lower numbers come first.
- Click a prompt to expand it, then press **Copy** and paste it into your AI tool together with `context.md` (and `progressive.md` where needed).
- **Export All** downloads every prompt as one Markdown file.
- **+ Add Section** lets you add your own prompts. They are saved only in your current browser, so use Export All to keep a copy.

Use an AI tool that can search the web for the research-heavy sections (market sizing, competitors, demand signals, funding). Check any numbers, regulations and company names it gives you before you rely on them.

## Contributing

Ideas for new prompts or fixes are welcome. Open an issue or a pull request. All prompt data lives in the `SECTIONS` array inside `index.html`.

## License

[MIT](LICENSE)
