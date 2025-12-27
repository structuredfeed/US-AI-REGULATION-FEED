# Machine Readable AI Regulation Feed (US)

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
See sources/us_sources.md for a full list of official sources.

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

## Disclaimer
This feed is provided "as is" without warranties of any kind.
No liability is assumed for errors, omissions, or interpretations.
Users should consult qualified legal professionals for regulatory or compliance advice.

## License
This repository provides a licensed structured representation of public information.
The underlying regulatory texts are public records governed by their respective jurisdictions.


