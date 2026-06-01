# How many Americans live with a chronic condition developed from COVID?

An interactive, transparent calculator exploring the implications of **Tian et al., _Long COVID Persistence and Surveillance Gaps Across 58 US Hospitals_ (JAMA Network Open, 2026)**.

**Live:** https://justinritchie.github.io/chronic-covid-tian-et-al/

## What it does

The study _measured_ one thing directly: among people with a documented COVID infection, **1 in 6 (16.3%)** developed a new, lasting condition needing medical care, and **1 in 7 (14.5%)** developed a new **chronic** condition requiring ongoing care. That rate is the fixed anchor.

Everything beyond it — how many of the infected that scales to, what happens across multiple reinfections, and how many conditions persist — depends on assumptions the data can't settle. So the page hands those levers to you:

- **Reinfection trajectory** — does per-infection risk get eliminated, decline, stay flat, or compound with each reinfection? (The single biggest swing; each option carries its evidence.)
- **Average infections per person** — anchored to wastewater estimates (~5 by early 2026); an optional overlay maps each infection to the calendar year it lands in.
- **Persistence** — what share of chronic conditions stay active, since the study explicitly can't determine resolution (anchored to ME/CFS recovery data).
- **Share ever infected** and a **per-infection rate adjustment**.

A "conservatism pyramid" shows how the count climbs from what official surveillance captures (~15M) up to the modeled true burden, and every figure links to its source.

## Important

Figures are **modeled estimates with wide uncertainty**, not point facts. There is no never-infected comparison group, so these are not "excess over background." Built for exploration and discussion of the paper's implications.

## Tech

A single, zero-dependency `index.html` — all logic, styling, and the SVG chart are inline. No build step.

## Sources

Tian et al. (JAMA Netw Open 2026); Cairns & Hotopf (Occup Med 2005); Bowe, Xie & Al-Aly (Nat Med 2022); Antonelli et al. (Lancet 2022); CDC seroprevalence (MMWR) and Household Pulse Survey; Pandemic Mitigation Collaborative (M. Hoerger). Full citations are linked in the page footer.
