# Website Asset Image Generator

A **generalized, non-executable technical case study** of an AI-assisted batch pipeline that prepares structured visual briefs, generates image assets, and organizes output metadata for downstream website work. The original business context and implementation details are intentionally not disclosed.

## Technical overview

The architecture illustrates request configuration → per-item processing → variation guidance from previously generated records → structured text-model response → image-model request → result parsing → metadata storage.

**Techniques:** n8n-style workflow orchestration, JavaScript transformations, REST/HTTP integration, JSON parsing, generative AI APIs, batch loops, and spreadsheet-backed output tracking.

## Architecture reference

[`workflow-architecture.json`](workflow-architecture.json) contains **12 documented nodes and their connection graph**, including conceptual inputs/outputs, transformations, and example-safe field names. It is **not an n8n import file** and will not execute. Nodes and example schemas describe the technical approach without exposing proprietary prompts, code, endpoints, identifiers, or internal records.

## My role

- Designed the end-to-end automation architecture, including workflow logic, AI integrations, data processing, and output management.
- Planned and structured the workflow to support automated visual asset generation for website development.
- Led testing and validation to ensure the workflow produced consistent and usable outputs.
- Implemented improvements to optimize workflow efficiency, output quality, and reliability.
- Managed ongoing maintenance, troubleshooting, and workflow refinement.

## Confidentiality

This is a portfolio adaptation, **not an exact reproduction** of the original implementation or business purpose. Company data, production configuration, and sensitive business specifics are not included. 
