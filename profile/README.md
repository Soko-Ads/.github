<div align="center">

# Soko Ads

### AI-native infrastructure for audio & programmatic publishers.

<sub>Identity resolution · Demand intelligence · IVT filtering · PMP deal automation</sub>

[![Website](https://img.shields.io/badge/sokoads.com-0A0A0A?style=for-the-badge&logo=safari&logoColor=white)](https://sokoads.com)
[![Contact](https://img.shields.io/badge/contact-aggrey%40sokoads.com-informational?style=for-the-badge&logo=minutemailer&logoColor=white)](mailto:aggrey@sokoads.com)
[![Location](https://img.shields.io/badge/USA-1F6FEB?style=for-the-badge&logo=googlemaps&logoColor=white)](#)

</div>

---

## What we build

Publishers — especially in streaming audio and CTV — are bleeding yield to
walled gardens, opaque exchanges, and fraudulent traffic. Soko Ads builds
the agentic intelligence layer that lets independent publishers take
control of their own demand, inventory, and identity graphs.

Our flagship platform, **Soko**, is an AI-native publisher intelligence
system that combines large-model agents with real-time bidstream telemetry
to automate the operational work that sell-side teams currently do by hand.

## The Soko pipeline

A six-phase agent pipeline that turns raw bidstream + catalog data into
optimized PMP deals:

| Phase | Agents (parallel where shown) | Output |
|------:|-------------------------------|--------|
| 1 | **Observer** · **Market Intel** · **IVT Filter** | clean, enriched bid stream |
| 2 | **Identity Graph** (ID5, UID2, household enrichment) | resolved identities |
| 3 | **Signal Discovery** · **Demand Signal** | hidden cohorts + DSP demand patterns |
| 4 | **Inventory Matcher** | ranked inventory vs. deal targeting |
| 5 | **Deal Engine** | PMP deals mapped to SoundStack, Magnite, Triton, AdsWizz |
| 6 | **Creative** · **Retention** · **Geo** | enrichment + post-bid optimization |

## Tech we ship on

<table>
  <tr>
    <td>

**Frontend**
- React 18 + TypeScript
- Vite + Tailwind CSS
- Vitest

    </td>
    <td>

**Backend**
- FastAPI (Python 3.12)
- SQLAlchemy async + asyncpg
- Alembic, PostgreSQL 16, Redis 7

    </td>
    <td>

**AI Agents**
- Anthropic API
- Custom orchestrator
- SSP + identity adapters

    </td>
    <td>

**Infrastructure**
- Terraform
- AWS ECS Fargate, RDS, ElastiCache, ALB, ECR
- Grafana · Prometheus · OpenTelemetry

    </td>
  </tr>
</table>

## Integrations

**SSPs:** SoundStack · Magnite · Triton · AdsWizz
**Identity:** ID5 · UID2 · household graphs
**Standards:** OpenRTB 2.6 · IAB TCF 2.2 · Prebid Server

## What's coming to this org

- [ ] `soko-platform` — full-stack monorepo (frontend, backend, agents, infra)
- [ ] `aeon-agents` — open components of the agent framework
- [ ] `soko-design-system` — tokens, primitives, publisher dashboards
- [ ] `openrtb-utils` — parsing, validation, fixtures
- [ ] Public docs + architecture diagrams

## Get in touch

Interested in piloting Soko on your inventory, partnering on identity, or
joining the team?

- **Email:** [aggrey@sokoads.com](mailto:aggrey@sokoads.com)
- **Website:** [sokoads.com](https://sokoads.com)

<div align="center">
<sub>© Soko Ads — building calm, trustworthy infrastructure for publishers.</sub>
</div>
