<p align="center"><img src=".github/readme-assets/banner.svg" width="100%" alt="Executive Authority Playbook — Identity, evidence and source governance for international leaders" /></p>

# Executive Authority Playbook

[![Validation](https://github.com/mhdteto/executive-authority-playbook/actions/workflows/validate.yml/badge.svg?branch=main)](https://github.com/mhdteto/executive-authority-playbook/actions/workflows/validate.yml)
![Python CI](https://img.shields.io/badge/Python%20CI-3.12-36d9ee?labelColor=081321)


**Practical working materials for founders, executives, investors and experts whose public record crosses organizations, markets and languages.**

Build a reference biography, reconcile roles and names, organize evidence and request factual corrections with a clear audit trail. This public playbook supports an accurate and maintainable record across websites, professional profiles, third-party sources and AI-generated descriptions.

[For leaders](https://mohammedteto.com/leaders/) · [Authority Architecture System](https://github.com/mhdteto/authority-architecture-system) · [Fictional examples](examples/) · [Templates](templates/)

<!-- shared-nav -->
<p>
  <a href="https://mohammedteto.com"><img src=".github/readme-assets/website.svg" width="148" height="36" alt="Website" /></a>
  <a href="https://mohammedteto.com/method/"><img src=".github/readme-assets/method.svg" width="148" height="36" alt="The method" /></a>
  <a href="https://mohammedteto.com/leaders/"><img src=".github/readme-assets/leaders.svg" width="148" height="36" alt="For leaders" /></a>
</p>

<!-- suite-navigation -->
## See the suite workflow

[![Recorded explorer with fictional citation groups, filters and CSV export](https://raw.githubusercontent.com/mhdteto/authority-architecture-system/main/.github/readme-assets/explorer-walkthrough.gif)](https://mhdteto.github.io/authority-architecture-system/#citations)

Actual browser capture of the suite explorer; fictional observations. Plays once. [Static view](https://github.com/mhdteto/authority-architecture-system/blob/main/.github/readme-assets/explorer-static.png) · [Text walkthrough](https://github.com/mhdteto/authority-architecture-system/blob/main/docs/explorer-walkthrough.md).

[Start your audit](https://github.com/mhdteto/search-ai-audit-starter) · [Reusable GitHub Action](https://github.com/mhdteto/search-ai-audit-action) · [Real first-party technical baseline](https://github.com/mhdteto/authority-architecture-system/tree/main/case-studies/mohammedteto-com).

## Start here: this repository in the workflow

**Your task:** Define the leader, material claims and review scope.

[Method →](https://github.com/mhdteto/authority-architecture-system) · [Audit →](https://github.com/mhdteto/search-ai-discoverability-checker) · [Structure →](https://github.com/mhdteto/entity-structured-data-kit) · [Measure →](https://github.com/mhdteto/ai-citation-tracker)

**Next step:** [entity-consistency-auditor](https://github.com/mhdteto/entity-consistency-auditor) — Compare the approved identity with supplied profile observations.

**Try it:** [complete fictional workflow](https://github.com/mhdteto/authority-architecture-system/tree/main/examples/fictional-workflow). All scenario records and engine answers are invented; generated reports are real CLI output.

**Python CI:** 3.12. The badge links to the real workflow; it describes automated checks, not ranking, factual accuracy or AI visibility.
[Map of all eight resources](https://github.com/mhdteto/authority-architecture-system/blob/main/docs/tool-map.md) · [Open an issue](https://github.com/mhdteto/executive-authority-playbook/issues/new/choose)
<!-- /suite-navigation -->

## Start with a concrete situation

| Situation | Working guide | First deliverable |
| :--- | :--- | :--- |
| Your biography changes from one profile to another | [Biography system](guides/biography-system.md) | Approved reference and claim register |
| You have changed role or organization | [Role transitions](guides/role-transitions.md) | Dated role timeline and correction queue |
| Search or AI confuses you with someone else | [Namesake review](guides/namesake-review.md) | Source-by-source identity review |
| A third-party page contains an error | [Source corrections](guides/source-corrections.md) | Evidence-backed correction request |
| Your record exists in several languages | [International record](guides/international-record.md) | Approved language variants and source map |
| Updates are scattered across a team | [Governance](guides/governance.md) | Named owners, approvals and review cadence |

## A focused working sequence

1. Define the entity, audiences, markets, languages and decision context in the [scope brief](templates/scope-brief.md).
2. Establish a dated [role timeline](templates/role-timeline.csv) and [official source register](templates/official-sources.csv).
3. Draft the [reference biography](templates/biography-reference.md), separating supported facts from ambitions.
4. Link factual claims to sources in the [claim review register](templates/claim-review.csv).
5. Review profiles and third-party records; open [correction requests](templates/correction-request.md) where needed.
6. Record changes and schedule review using the [governance brief](templates/governance-brief.md).

## What this is—and what it can establish

These are operational templates and review decisions, not an automated reputation service. A coherent biography can still be wrong; a published correction request may not be accepted; search engines and AI providers may retain or retrieve different information.

The materials do not promise a ranking, citation, recommendation, knowledge panel, investment outcome or removal of lawful reporting. Every example is **fictional teaching material**, not an anonymized client case or measured outcome. See [boundaries](guides/limits.md).

## Use the companion tools

- [Entity Consistency Auditor](https://github.com/mhdteto/entity-consistency-auditor) compares supplied profile observations with an approved reference. It does not verify truth or resolve namesakes automatically.
- [Authority Evidence Mapper](https://github.com/mhdteto/authority-evidence-mapper) organizes human-declared evidence links and keeps contrary sources visible.
- [Search & AI Discoverability Checker](https://github.com/mhdteto/search-ai-discoverability-checker) inspects technical discovery signals, without confirming indexing or predicting AI citations.

The tools support the process; they do not replace source review, the subject's approval or qualified specialist advice where needed.

## Validate the public materials

Reading and reusing the playbook requires no installation. To check local links and template structure:

```bash
python3 tools/validate.py
```

## Authorship, scope and reuse

Created by **Mohammed Teto — AI Reputation & Authority Strategist**, working with leaders and organizations internationally. [Practice](https://mohammedteto.com/) · [Method](https://mohammedteto.com/method/) · [Private assessment](https://mohammedteto.com/private-assessment/).

No office, client relationship or provider endorsement is implied by the market examples. Documentation, templates and original artwork are [CC BY 4.0](LICENSE.md). The validator is [MIT licensed](LICENSE-CODE). [Contributions](CONTRIBUTING.md) must preserve factual traceability and confidentiality.
