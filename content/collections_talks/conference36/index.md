---
title: 'Claude Coke: Prevent Automated Crime by Agents'

# Use the admin profile for Kevin Riehl, preserving the supplied author order.
authors:
  - Gabor Hollbeck
  - Baran Peters
  - Alexander von Recum
  - Yuri Simantob
  - Jan Granacher
  - Alec McGail
  - admin

date: '2026-12-09'
publishDate: '2026-11-05'
url_source: 'https://neurips.cc/virtual/2026/poster/140039'
url_code: 'https://github.com/ghollbeck/ClaudeCokeCameraReady'
url_dataset: 'https://github.com/ghollbeck/ClaudeCokeCameraReady_Data'

publication_types: ['conference-journal']
publication: "*40th Annual Conference on Neural Information Processing Systems (NeurIPS 2026), Position Paper Track, Sydney, Australia, December 6-12, 2026.*"

abstract: "*40th Annual Conference on Neural Information Processing Systems (NeurIPS 2026), Position Paper Track, Sydney, Australia, December 6-12, 2026.*"

tags:
- AI safety
- LLM agents
- multi-agent systems
- AI governance
- position paper
- eth
- conference

featured: true

---

*40th Annual Conference on Neural Information Processing Systems (NeurIPS 2026), Position Paper Track, Sydney, Australia, December 6-12, 2026.*

We show that contemporary LLM-agent stacks can automate serious criminal activity at scale by composing capabilities that are already present, and that relevant technical safeguards and governance controls need to be in place before becoming operationally viable. The argument rests on three empirical findings that are usually studied separately but together close a loop that automates illicit purchasing, whether by accident or by design. (i) Autonomous LLM agents fail catastrophically at multi-agent-economy coordination tasks, with bankruptcy as the modal outcome and not a rare tail case. (ii) The rate at which agents reach for clearly harmful tools moves with common contextual manipulations. (iii) Autonomous browser control has become general enough that some frontier agents can navigate, populate, and complete checkout flows on simulated illicit-product storefronts under light obfuscation, with completion varying across tested model configurations. Combining these findings requires no new model capability: in our experiments, some LLM agents autonomously completed simulated dark-web purchases of drugs, shotguns, and hitman services, while others refused. We propose and discuss three interventions: mandatory pre-deployment safety testing, hard human-confirmation gates at financially material steps, and verifiable agent identity infrastructure.

[NeurIPS conference page](https://neurips.cc/virtual/2026/poster/140039) · [Paper on OpenReview](https://openreview.net/forum?id=dy8ITXgyTV)

The [manuscript source and figure assets](https://github.com/ghollbeck/ClaudeCokeCameraReady) are maintained separately from the [selected run records, analysis scripts, and reproduction notebooks](https://github.com/ghollbeck/ClaudeCokeCameraReady_Data). At the time of writing, access to the data repository is restricted; linking to it here does not constitute the redacted public release discussed in the manuscript.
