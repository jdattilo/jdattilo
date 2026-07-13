# Joseph Dattilo

**Engineer · Founder · AI fleet operator**  
Lansing, Michigan

I build production systems where humans and AI agents are first-class contributors—with the work queues, scoped credentials, approval gates, and transport-level controls required to make that safe.

I've spent more than twenty years across hardware, software, manufacturing, test, and operations. The through-line is simple: learn how the real work happens, then build the system the operation can actually run on.

[Personal site](https://josephdattilo.com/) · [What I’m building](https://josephdattilo.com/building/) · [Open-source history](https://josephdattilo.com/open-source/) · [LinkedIn](https://www.linkedin.com/in/joedattilo/) · [Date Palm Media](https://datepalm.media/)

## What I build

I don't start with the technology. I start where the workflow is messy and consequential: a factory floor, a painting operation, a datacenter test lab, or a software team running AI coding agents.

I observe the work, model the real constraints, build the system of record, and introduce automation or AI behind boundaries that people can inspect and enforce.

Today I'm turning that pattern into the **FleetHarbor suite**: controlled infrastructure for teams where humans and AI agents work from the same repositories, boards, and fleets.

## Current systems

| Project | Purpose | Public status |
|---|---|---|
| **[RepoHarbor](https://repoharbor.dev/)** | A self-hosted Git control plane with transport-level branch policy, PR mediation, scoped tokens, and server-side credential custody. | Nearing general availability; Apache-2.0 core source release announced and coming soon. |
| **[TaskHarbor](https://taskharbor.dev/)** | A shared work queue for people and agents, with atomic claim-locks, WIP limits, agent-ready queues, human-gated scoping, and board-confined tokens. | Hosted early-access track; Apache-2.0 core source release announced and coming soon. |
| **FleetHarbor** | The fleet control plane: isolated agent pods with one scoped gateway token and server-side credential mediation. | Early-access track. |
| **NeuroHarbor** | Local model serving and fine-tuning for sensitive fleet workloads. | In development. |

<!-- Add source-repository links only after each repository is public and its license is present. -->

The products form one operating loop: TaskHarbor governs what is ready to build, the fleet performs the work, and RepoHarbor governs what can ship.

I run that loop on my own production software every working day (every product in the suite is built by the fleet it manages). [See the current-project overview.](https://josephdattilo.com/building/)

## Proven systems and independent authority

### OpenPastures / Cattle Suite

**Distributed storage-test infrastructure published by Dell**

While I was a senior software engineer on Dell’s Fluid Cache team, I built the Cattle Suite to coordinate multi-node storage testing: distributed execution, cluster and hardware registry, test queues, centralized logs, and build/run monitoring.

Dell officially published the suite as **OpenPastures** on May 12, 2016.

- **Official release:** [Dell Open Source — OpenPastures](https://opensource.dell.com/releases/openpastures/)
- **Background and provenance:** [my open-source history](https://josephdattilo.com/open-source/)
- **Mirrors:** [AE2 / Bicyclops](https://github.com/jdattilo/awesome-express-bicyclops) · [AE2 / Butterjunk](https://github.com/jdattilo/awesome-express-butterjunk) · [CATTLE](https://github.com/jdattilo/cattle-2.0) · [COW](https://github.com/jdattilo/cow-2.0) · [COWTRACKS](https://github.com/jdattilo/cowtracks-1.0) · [B2EB](https://github.com/jdattilo/b2eb-1.0)

Dell’s release directory is the canonical 2016 source. The GitHub repositories are later mirrors with detailed provenance and comparison notes.

### MyPaintBuckets

**Operational software in production**

I co-founded **[MyPaintBuckets](https://mypaintbuckets.com/)**, the system of record for new-residential painting operations: project details, material ordering, extra-paint-order capture, scheduling, and invoicing.

It is mature software with real customers and the proving ground where the fleet’s output meets a real industry and real deadlines.

## Earlier open-source hardware and embedded work

I founded **Virtuabotix** in 2011 as an Arduino-ecosystem electronics company with in-house design and manufacturing. It became **Date Palm Media** in 2017 as the work expanded into software, automation, and product delivery.

The first representative archive project is **[DHT11LIB](https://github.com/jdattilo/DHT11LIB)**, a dependency-free Arduino library for the DHT11 temperature and humidity sensor.

I maintained and extended the Virtuabotix releases, building on the library’s earlier attribution chain. It has remained public since 2011.

Additional Virtuabotix board designs, sensor libraries, firmware, examples, and schematics can join this section as they are verified and released.

## Focus areas

- AI coding-agent infrastructure and applied production AI
- Process automation and operational software
- Git policy, credential mediation, and human approval systems
- Distributed test, build, and datacenter tooling
- Embedded hardware, firmware, semiconductor test, and manufacturing systems

## Writing and evidence

- [Running a fleet of AI coding agents in production](https://josephdattilo.com/writing/running-a-fleet-of-ai-coding-agents/)
- [Current projects and public status](https://josephdattilo.com/building/)
- [Twenty-plus-year track record](https://josephdattilo.com/track-record/)
- [Open-source history and provenance](https://josephdattilo.com/open-source/)
- [About Joseph Dattilo](https://josephdattilo.com/about/)

## Contact

For product collaboration, applied AI and automation work, technical leadership, or agent-infrastructure discussions, email **[joe@datepalm.media](mailto:joe@datepalm.media)**.

Commercial delivery runs through **[Date Palm Media](https://datepalm.media/)**.
