<h1 align="center">Hi, I'm Francisco 👋</h1>

<p align="center">
  <b>I turn messy, manual work into software people actually use.</b><br/>
  Order portals for wholesalers, clinical records for doctors, bots that run a group chat. Usually with an LLM somewhere in the loop.
</p>

<p align="center">
  🇦🇷 Argentina · Native Spanish, fluent English
</p>

---

### What I build

I start from the problem, not the stack: who is doing what by hand, what it costs them, and what's the smallest thing that removes it. Then I ship it, watch people use it, and iterate.

- **Business tools.** Replacing WhatsApp-and-spreadsheet workflows with real products: catalogs, orders, account statements, PDFs.
- **Automation.** Scheduled jobs, scrapers, and notifications that run unattended on Railway.
- **Applied AI.** LLMs where they earn their place: reading photos of tickets, answering questions about records, giving bots a personality. Privacy and guardrails come first.

---

### Featured projects

<table>
<tr>
<td width="50%" valign="top">

#### 🔍 [VibeCode Scanner](https://github.com/franatucha/vibecode-scanner)
A CLI and GitHub Action that audits AI-generated codebases for the mistakes vibe coding leaves behind: leaked keys, unauthenticated routes, SQL built from strings, open CORS, hallucinated packages. You get a score and a readable report.

`TypeScript` `Node` `GitHub Actions`

</td>
<td width="50%" valign="top">

#### 🩺 [Pediatric Chart](https://github.com/franatucha/pediatric-chart)
WHO growth charts that do the math properly: LMS z-scores, corrected age for preterm babies, WHO classifications and alerts when a child drops across percentile lines. Includes an assistant you can *ask* about a patient's growth, with a panel that shows exactly what the model sees. Patient data is pseudonymized before it reaches the model.

`Next.js` `TypeScript` `Recharts` `Claude` · tested against WHO tables

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### 📦 B2B Order Portal <sub>· coming soon</sub>
A wholesale ordering platform, modeled on one I built for a real distributor. Clients browse the catalog, place orders, and check their account balance. The back office manages pricing, discounts, order status, and generates PDFs. Sign-in is by magic link.

`Next.js` `Prisma` `NextAuth` `shadcn/ui`

</td>
<td width="50%" valign="top">

#### 🤖 WhatsApp Bot Kit <sub>· coming soon</sub>
Run several WhatsApp bots from one process and one session. Each bot is a plugin with its own crons, commands, and LLM persona. Includes a dry-run mode that never sends a message. It started as a bot that runs my friends' lottery pool.

`Node` `Baileys` `OpenAI` `Railway`

</td>
</tr>
</table>

---

### Toolbox

**Daily:** TypeScript · Next.js · React · Node.js · PostgreSQL · Prisma / Drizzle · Tailwind · OpenAI API
**Shipping:** Railway · Vercel · GitHub Actions · Playwright
**Also:** NestJS · Baileys (WhatsApp) · Jira API

---

### Other things I've automated

- A delivery dashboard that pulls project status straight from Jira
- A collaborative platform for families to document their history together

<p align="center"><sub>Most client work is private. The repos above are open rebuilds of real projects, with fictional data.</sub></p>
