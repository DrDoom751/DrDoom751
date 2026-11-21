# AETHER-BURN X

**NASA Space Apps 2026 · Flame in Freefall · Team Orbitrace**  
**Team:** Basanth M, Rija Sageer, Yash Gurukul, Rizul Garg

## The question

NASA has studied combustion in microgravity, but results depend on the material, oxygen level, pressure, airflow, geometry, and measurement. How can someone find the relevant evidence and see when an apparent comparison is unsupported?

## What we built

AETHER-BURN X is a research workbench for navigating combustion evidence. Its documented project flow is:

1. Choose a scenario, including oxygen, pressure, airflow, gravity, and material.
2. Inspect research records and their source context.
3. Check coverage and compatibility before comparing findings.
4. Follow claims back to NASA reports and metadata.
5. Identify missing measurements that would make the next experiment useful.

The team's six-slide project deck describes a Django application with investigations, scenario controls, source traceability, an evidence assistant, and a guided judge tour. It reports **129 report-derived experiment records**, **82 NASA NTRS metadata records**, and **151 passing automated tests**. These are the team's documented software and curation results, not independent validation of a fire-safety prediction. The deck reports **no raw PSI time-series samples** in this build.

## The design decision that matters

A compelling chart can imply more than its evidence supports. AETHER-BURN X separates direct observations, calculations, model outputs, and unverified claims. It makes unavailable coverage and mismatched conditions visible instead of inventing a smooth answer for an untested environment.

## My role and collaboration

This was a four-person team project. The public case study describes the team's product and scientific approach; it does not assign individual features or code ownership without a contribution record. Individual contributions and the source/demo links can be added once the final submission materials are available.

## Limits and next steps

This workbench helps investigate research evidence; it is **not a spacecraft fire-safety certification tool**. The next research steps are authentic NASA PSI time-series ingestion, held-out quantitative checks, and carefully scoped low-gravity and airflow comparisons.

**Challenge:** [Flame in Freefall](https://www.spaceappschallenge.org/2026/challenges/flame-in-freefall/)  
**Research context:** [NASA technical report NTRS 20210011385](https://ntrs.nasa.gov/citations/20210011385)

*Source for build details: Team Orbitrace's AETHER-BURN X project deck, 15 November 2026. A public source repository and live demo link were not present in the connected GitHub account when this case study was prepared.*
