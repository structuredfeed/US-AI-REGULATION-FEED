# Machine Readable AI Regulation Feed (US)

## Current Release
- Version: v1.0
- Status: Frozen

## Overview
This repository provides a machine-readable JSON feed of official artificial intelligence (AI) regulation, policy, and guidance updates from public authorities in the United States, European Union, and United Kingdom.

The purpose of this feed is to transform publicly available regulatory information into a structured, normalized format suitable for automation, monitoring, and internal analysis.

## What This Is
- A structured representation of public regulatory signals
- Derived exclusively from official government sources
- Updated using automated processes
- Provided in JSON format for machine consumption

## What This Is Not
- This is not legal advice
- This is not an authoritative legal interpretation
- This does not replace official publications
- This does not guarantee regulatory compliance

## Data Structure
- `data/latest.json` — the most recent US AI related regulatory item
- `data/archive.json` — historical archive of all accepted items

## Data Sources
See `sources/us_sources.md` for a full list of official sources.

## Schema Governance

This repository uses a locked metadata schema.
The schema is frozen as of v1.0 and governed by the Schema Lock Declaration.

See: `SCHEMA_LOCK.md`

## Versioning & Data Scope
This repository follows a rolling release model.
- Version identifiers (e.g. v1.0) represent a stable snapshot of all qualifying regulatory instruments available at the time of release.
- The latest.json file points to the most recently published qualifying instrument at build time.
- The archive/ directory contains all previously indexed instruments preserved immutably.

## Inclusion Criteria
This dataset includes:
- Primary legislation (Acts)
- Secondary legislation (e.g. Regulations, Statutory Instruments)
- Official amendments and commencement instruments where applicable
- Devolved or federal equivalents where within scope (e.g. Welsh Statutory Instruments)

## Metadata Completeness
- Some official sources publish legislation with partial metadata (e.g. missing titles or summaries at time of publication).
- Such records are included unaltered to preserve fidelity with the authoritative source.
- Metadata completeness may improve in later versions without altering historical records.

## AI, Data, and Digital Relevance Flags
- Relevance indicators are generated using conservative classification rules.
- Flags may include false positives where legislation references automation, systems, or electronic processes without explicitly regulating artificial intelligence.
- These indicators are informational only and do not constitute legal interpretation.

## Jurisdictional Integrity
- Each repository is jurisdiction-specific.
- Cross-jurisdictional instruments are indexed only where they are officially incorporated or retained within the relevant legal framework.

## Methodology
- Only official summaries, abstracts, and metadata are used
- Full legal texts are not republished
- Content is transformed into a fixed JSON schema
- No speculative interpretation is added
- If information is unclear or unavailable, it is marked as "not specified"

## Update Frequency
Updates are performed automatically when new relevant regulatory signals are detected.
If no qualifying updates are published, no changes are made.

## Intended Use
This feed is intended for:
- Regulatory monitoring
- Internal policy tracking
- Risk awareness
- Research and analysis
- Automation and tooling

Users are responsible for determining how the information is used within their own compliance or decision-making processes.

## Compatibility Statement
This repository aggregates metadata derived from official public-sector sources.
- US sources: US Government works, public domain
- UK sources: Crown copyright, Open Government Licence v3.0
- EU sources: © European Union, reused under the EU Open Data Directive and EUR-Lex reuse policy

Public Domain content is fully compatible with the MIT License.
Open Government Licence v3.0 and EU Open Data licences are permissive and MIT-compatible when:
- Attribution is preserved
- No endorsement is implied

This repository:
- Does not redistribute full legislative, regulatory, or copyrighted text where restrictions apply
- Provides metadata, summaries, and links only
- Is compatible with MIT / Apache-2.0 / CC-BY-4.0 downstream use
Users are responsible for verifying downstream reuse requirements of linked source material.

## Repository License

This repository is licensed under the MIT License.

The MIT License applies only to:
- Original code
- Original JSON structures
- Metadata schemas
- Generated prompts and classification logic

This repository provides a licensed structured representation of public information.
Underlying regulatory and legislative texts remain governed by their respective issuing authorities.


## Disclaimer
This feed is provided "as is" without warranties of any kind.
No liability is assumed for errors, omissions, or interpretations.
Users should consult qualified legal professionals for regulatory or compliance advice.
