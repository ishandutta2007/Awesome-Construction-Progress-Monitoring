# Awesome-Construction-Progress-Monitoring

## Top Construction Progress Monitoring Platforms Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Reality Capture, AI Progress Tracking, BIM Alignment & Earned Value Verification*  

**Last updated: September 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Construction Progress Monitoring**. These tools help general contractors, owners, and trade partners verify work-in-place, detect schedule deviations early, and maintain an objective record of what was built versus what was planned.



**Examples** include Buildots, OpenSpace, Doxel, Disperse, Reconstruct, Avvir, Versatile, and WakeCap (the category leaders).



**Open-source emphasis**: Construction progress monitoring has a **fragmented but growing open-source ecosystem**. Unlike some enterprise software categories, no single open-source platform matches the full scope of commercial reality capture and AI progress tracking solutions. However, **niche, high-impact tools exist** — most notably the **Sandwich Panel Installation Tracker**, a production-deployed AutoCAD plugin that eliminated subcontractor disputes and reduced weekly reporting from 4 hours to 10 seconds on a 5,000-panel project . Research frameworks like **P6 Extraction Framework** provide schedule-driven digital twin synchronization foundations . This section documents these focused solutions honestly.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents



- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Buildots](https://buildots.com/)**  

  AI-powered construction progress tracking platform. Uses 360 cameras, drones, and laser scans to capture site footage, then compares against BIM models and schedules to track element-level progress . Features automated delay forecasting weeks in advance, trade management, and SOC 2 Type 2 / ISO 27001 certification. Raised $130M in 2026 (total $297M), serving 100+ major companies including Intel, Digital Realty, and JE Dunn .



- **[OpenSpace](https://www.openspace.ai/)**  

  The global leader in 360° reality capture and AI-powered analytics. Captures 25,000 sq ft in 10 minutes with images viewable in ~15 minutes . **OpenSpace Track** (powered by Disperse) provides milestone-based progress tracking with 700+ visual components across 200+ program tasks . Acquired **Disperse** in October 2025 to deliver a full-stack platform . Customers have captured imagery on nearly 70,000 projects across 99 countries .



- **[Doxel](https://doxel.ai/)**  

  AI-powered progress tracking for construction, specializing in **data center construction**. Uses computer vision to automatically track progress and avoid rework . Enterprise partnership with Stream Data Centers (August 2025) for near real-time project visibility . Supports Insta360 X5 camera integration for rugged jobsite capture .



- **[Disperse](https://www.disperse.io/)**  

  Milestone-based progress tracking platform (now part of OpenSpace). Uses a **human-plus-AI hybrid approach** — architects and engineers configure projects and verify AI insights for accuracy . Features **Spotlights** for detecting rework, delays, and non-conformance with Priority flags and Action Lists .



- **[Reconstruct](https://reconstructinc.com/)**  

  Remote quality control and progress monitoring platform. Uses smartphones, 360 cameras, or drones to generate **as-built digital twins** with precise 2D floor plans and 3D models . Patented overlay technology compares design against reality, with 4D BIM visualization for schedule sequencing .



- **[Avvir](https://avvir.ai/)**  

  Automated construction monitoring platform (acquired by Hexagon in October 2022). Uses computer vision to compare laser scans and photographs against BIM models, creating a digital twin of the site . Integration with DroneDeploy provides 360 Walkthrough reality capture paired with AI-driven BIM analysis .



- **[Versatile](https://versatile.ai/)**  

  AI-powered crane and steel erection tracking. A sensor mounts to the crane hook to capture every lift, automatically logging as-installed steel sequences with timestamps and GPS evidence . Customers report **27% reduction in crane idle time** and **131 labor hours saved per sequence** . Track feature provides Time Travel replay and Magical Replay from crane's perspective .



- **[WakeCap](https://www.wakecap.com/)**  

  Progress management platform with **helmet-mounted cameras** for 360° reality capture auto-aligned to BIM . Validated at ROSHN with **95% progress accuracy** and **100% site coverage** . Features earned-value tracking (BAC, EV, PV, SV) with P6-linked roll-ups and historical progress replay .



## Open-Source GitHub Projects



### Niche High-Impact Tools



- **[Sandwich Panel Installation Tracker](https://github.com/KonevOleg/sandwich-panel-tracker)**  

  **Production-deployed AutoCAD plugin for real-time construction progress tracking of sandwich panel installation** . **Real-world results**: On a 5,000-panel industrial building project, reduced weekly reporting time from **4 hours to 10 seconds**, eliminated subcontractor disputes through data-backed tracking, and enabled setup of 4,943 panels in ~30 minutes . Features: visual color-coded status tracking (grey=not installed, green=installed, red=defective, yellow=repairable), auto-generated AutoCAD tables with square footage breakdowns, one-click Excel export, joint calculations, and cutout tracking . Built with AutoLISP/Visual LISP using XData for persistent per-entity database inside DWG. **MIT License** .



### Research Frameworks



- **[P6 Extraction Framework](https://github.com/bededani22-art/p6-extraction-framework)**  

  **Schedule-driven digital twin synchronization for construction progress monitoring** . Python, VBA, and SQL-based framework published in Zenodo (July 2026). Extracts P6 schedule data to enable 4D BIM synchronization and automated progress comparison. **Research-grade**, suitable as a foundation for custom digital twin implementations .



### Additional Strong Open-Source Options



- **Niche Tracking**: **Sandwich Panel Tracker** (AutoCAD plugin, production-proven, MIT) .

- **Schedule Integration**: **P6 Extraction Framework** (Python/VBA/SQL, research-grade) .

- **Reality Capture Foundations**: Open-source photogrammetry tools (COLMAP, OpenMVG) for generating 3D models from site imagery — requires significant integration for construction-specific workflows.

- **BIM Tools**: **IfcOpenShell** (open-source IFC parsing and geometry library) for BIM model processing — foundation for custom progress comparison tools.



**Frameworks for building custom systems**: Combine **Sandwich Panel Tracker** for element-level installation tracking in AutoCAD environments, **P6 Extraction Framework** for schedule-driven progress synchronization, **IfcOpenShell** for BIM model parsing and comparison, and **COLMAP** or **OpenMVG** for photogrammetry-based reality capture. Add **PostgreSQL** for progress data persistence and **Streamlit** for dashboards.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Construction progress monitoring platforms handle sensitive project data; ensure compliance with contractual requirements and data protection regulations.

- **Open-source reality**: The open-source ecosystem for construction progress monitoring is **fragmented and niche-focused**. **Sandwich Panel Tracker** demonstrates that production-grade open-source tools can deliver measurable value (4 hours → 10 seconds reporting, eliminated disputes) for **specific element types** . **P6 Extraction Framework** provides research-grade schedule integration . However, **comprehensive platform capabilities** — multi-trade progress tracking, AI-powered deviation detection, BIM alignment across entire projects, and portfolio-level dashboards — require commercial platforms (Buildots, OpenSpace, Doxel). The open-source path is viable for **focused, element-specific tracking** or as a **foundation for custom development** with significant engineering investment.



---



**Made for construction project managers, VDC engineers, field superintendents, and owner representatives.**  

Let's make construction progress monitoring more open, transparent, and verifiable.
