# Hi, I'm Matteo 👋

**AI Enablement & Project Management · Berlin**

I take a business problem, map the workflow with the people who own it, build or scope the AI solution, and stay until the team actually uses it. Before moving into AI, I spent more than six years in international customer operations (SumUp, ja-dialog), which is where I learned how workflows break and why new tools get adopted or ignored.

🌍 Italian · German · English · French  ·  📫 [LinkedIn](https://www.linkedin.com/in/matt-ver/) · [matteovercelli@proton.me](mailto:matteovercelli@proton.me)

---

## Selected work

### 1 · AI support automation for a community organisation — We Are Village
**Problem:** The team answered the same member questions (login, app access, membership, event pricing) again and again over email and WhatsApp.

**What I did:**
- Ran discovery with the product manager, mapped the recurring support workflow, and agreed scope and approval with management
- Built a structured FAQ knowledge base, a Google Forms intake that routes unanswered questions to the right person, and a Claude prompt framework for drafting replies
- Wrote a usage guide and onboarded non-technical staff, with a documented handover

**Outcome:** a knowledge base of 11 live FAQ entries plus 7 drafted from the team's SOPs, a keyword-based FAQ matcher prototype, an unanswered-questions log, and a documented update process, so the team can own and extend it without me (six-week part-time internship).

**Skills:** discovery · process mapping · stakeholder alignment · rollout & training

---

### 2 · PropLaw — AI assistant for German building law (team capstone)
[→ Repository](https://github.com/knowledgegraphers/proplaw)

A four-person team built an assistant that answers homeowners' building-law questions with cited sources, comparing classic RAG with a knowledge-graph approach (GraphRAG).

**My part:**
- **Project lead (rotating PM):** stand-ups, prioritisation, roadmap versions, meeting minutes
- **Evaluation design:** wrote the benchmark methodology: 20 legal queries weighted by type and difficulty, scored for retrieval, reasoning and unsupported content
- **Knowledge graph data:** extended the graph from one federal state to all 16 Landesbauordnungen and added a quality audit
- **Testing & quality:** synthetic user-test runner, CI checks and pre-commit setup

**Outcome:** retrieval precision improved from 2.55 to 3.60 out of 6 (+40%) on the benchmark; live prototype for Brandenburg.

**Skills:** evaluation · RAG / knowledge graphs · agile delivery · Python

---

### 3 · Feedback triage workflow in n8n (own project)
[→ Repository](https://github.com/Mttv0/n8n-feedback-triage)

New feedback in a Google Sheet triggers the workflow → Claude classifies each entry by category and urgency and writes a one-line summary as JSON → a code step parses it safely → high-urgency items go to an "Urgent" tab, everything else to an "All feedback" tab.

**Skills:** low-code automation · LLM classification · workflow design

### 4 · Lead qualification for a B2B sales team (take-home case)
**Task:** identify and qualify Berlin property-management companies as potential customers for a metering-services provider, in four days.

**What I did:**
- Combined six public sources (industry association, business directories) into **844 deduplicated companies**, plus a separate list of the 31 largest housing co-ops
- Defined **seven qualifying KPIs** (portfolio size, Berlin focus, rental vs. condo mix, ownership, digital maturity, association membership, reachable decision-maker) and scored every company
- Grouped them into tiers and recommended a **tiered sales approach**: personal outreach for the top accounts, a lighter touch for mid-sized firms, automation for the long tail
- Checked decision-makers against company imprints, and designed outreach to respect German rules on unsolicited email

**Deliverables:** scored and tiered lead sheet, contact tab for the top 26 accounts, approach document and two summary slides.

**What I'd do differently:** turn it into a rerunnable pipeline: crawl company sites at scale, let an LLM agent extract the KPIs with a source quote for every value, and measure accuracy on a random sample before trusting the scores.

**Skills:** discovery · KPI design · data validation · go-to-market thinking

---

## Toolbox
**Delivery:** discovery, process mapping, success metrics, agile & hybrid project management, documentation

**AI & automation:** LLMs, prompt & context design, RAG / GraphRAG, evaluation, n8n, Claude API, connectors / MCP

**Technical basics:** Python, SQL, REST APIs, Git/GitHub
