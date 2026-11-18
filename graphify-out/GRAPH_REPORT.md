# Graph Report - threat-intel-blog  (2026-11-18)

## Corpus Check
- cluster-only mode — file stats not available

## Summary
- 8 nodes · 6 edges · 2 communities (1 shown, 1 thin omitted)
- Extraction: 67% EXTRACTED · 33% INFERRED · 0% AMBIGUOUS · INFERRED: 2 edges (avg confidence: 0.93)
- Token cost: 0 input · 0 output

## Graph Freshness
- Built from commit: `7cdfd708`
- Run `git rev-parse HEAD` and compare to check if the graph is stale.
- Run `graphify update .` after code changes (no API cost).

## Community Hubs (Navigation)
- Community 0
- Community 1

## God Nodes (most connected - your core abstractions)
1. `Threat Intelligence Report Structure` - 6 edges
2. `CVE-2021-44228` - 1 edges
3. `CVE-2026-114713` - 1 edges
4. `DragonForce Ransomware Group` - 1 edges
5. `Report IOC Data Structure` - 1 edges
6. `Agent Rules and Graphify Procedures` - 1 edges
7. `Daily Threat Intelligence Report Overview` - 1 edges
8. `Bladabindi Malware` - 0 edges

## Surprising Connections (you probably didn't know these)
- `Threat Intelligence Report Structure` --conceptually_related_to--> `Agent Rules and Graphify Procedures`  [INFERRED]
  index.html → AGENTS.md
- `Daily Threat Intelligence Report Overview` --provides_context_for--> `Threat Intelligence Report Structure`  [EXTRACTED]
  README.md → index.html

## Hyperedges (group relationships)
- **Threat Intelligence Cycle Components** — index_html, report_ioc_data, cve_2026_114713 [INFERRED 0.75]

## Communities (2 total, 1 thin omitted)

### Community 0 - "Community 0"
Cohesion: 0.29
Nodes (7): Agent Rules and Graphify Procedures, CVE-2021-44228, CVE-2026-114713, DragonForce Ransomware Group, Threat Intelligence Report Structure, Daily Threat Intelligence Report Overview, Report IOC Data Structure

## Knowledge Gaps
- **7 isolated node(s):** `CVE-2021-44228`, `CVE-2026-114713`, `DragonForce Ransomware Group`, `Report IOC Data Structure`, `Agent Rules and Graphify Procedures` (+2 more)
  These have ≤1 connection - possible missing edges or undocumented components. (Counts symbols only; 7 node(s) total have ≤1 connection when file, concept and rationale nodes are included.)
- **1 thin communities (<3 nodes) omitted from report** — run `graphify query` to explore isolated nodes.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **Are the 2 inferred relationships involving `Threat Intelligence Report Structure` (e.g. with `Agent Rules and Graphify Procedures` and `Report IOC Data Structure`) actually correct?**
  _`Threat Intelligence Report Structure` has 2 INFERRED edges - model-reasoned connections that need verification._
- **What connects `CVE-2021-44228`, `CVE-2026-114713`, `DragonForce Ransomware Group` to the rest of the system?**
  _7 weakly-connected nodes found - possible documentation gaps or missing edges._