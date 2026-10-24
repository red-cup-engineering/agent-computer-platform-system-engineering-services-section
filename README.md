# Agent Computer Platform System Engineering Services Section

<!-- 561-group-standards:badges:start -->
[![Red Cup Engineering](https://img.shields.io/badge/561%20Group-Red%20Cup%20Engineering-c0392b)](https://github.com/red-cup-engineering)
[![License: MIT](https://img.shields.io/badge/license-MIT-c0392b)](LICENSE)
[![Indigenous data: CARE](https://img.shields.io/badge/Indigenous%20data-CARE-4b6f44)](https://github.com/red-cup-engineering/.github/blob/main/GOVERNANCE.md)
[![Tips welcome](https://img.shields.io/badge/tips-welcome-d4a017)](https://github.com/561-group/.github/blob/main/TIPS.md)
<!-- 561-group-standards:badges:end -->

**The engineering layer for platforms that host and operate agent computer
systems.** This repository composes specialized platform engineering
repositories and their design material. It is not an agent implementation,
a deployable hosting service on its own, or a claim that any platform is
currently running.

## Where to begin

The current `services/` directory composes two separately maintained
repositories:

- [Flatfile Agent Resource System engineering](services/flatfile-agent-resource-system-engineering-services-section) — the resource-system domain and its related implementations and conformance material; verify the current realization and installation instructions in that component itself.
- [Multi-agent computer platform systems](services/multi-agent-computer-platform-system-engineering-services-section) — hosting and coordination platforms for more than one agent.

This section also has `content/` and a root `package.json` describing the
composition. The root manifest **does not define a command-line entry point
or an application export**. To try a specific service, follow the child
repository's own package manifest, tests, and runbook.

For the agent *computing* layer rather than the hosting layer, go to
[Agent Computer System Engineering Services Section](https://github.com/red-cup-engineering/agent-computer-system-engineering-services-section).
For source composition of multi-agent *behavior*, see
[Multi-Agent Computer System Engineering Services Section](https://github.com/red-cup-engineering/multi-agent-computer-system-engineering-services-section).

## Current status

The two entries above are Git submodule pointers tracked at this repository's
HEAD. They are evidence of source composition, **not** of a provisioned host,
successful deployment, live availability, or standards certification. Check
each child project's current Issues, pull requests, development branches,
source exports, and independent test results before making operational claims.

## Scope and boundaries

An agent system determines what agents compute and how their work is
constrained; a platform supplies the durable *hosting and operating*
boundaries for such systems. This section organizes that second concern.
Operations ownership, credentials, admission, and live runbooks remain
with their respective providers and receiving services.
