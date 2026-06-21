# CampusGo

CampusGo is a low-code Microsoft Copilot Studio agent that helps students, freshmen, exchange students, visitors, and staff find campus facilities through natural conversation.

## Challenge track

**Student Experience and Career Readiness (outside the classroom)**

## Scope

CampusGo is designed for campus-wide facility guidance. The current MVP validates the approach using two HKBU buildings: **AAB** and **CVA**.

## How it works

1. Users ask for a facility or describe a practical need in natural language.
2. Agent instructions apply location-first routing, recommendation logic, multilingual behavior, and safety guardrails.
3. Structured Excel knowledge provides confirmed facility, landmark, floor, opening-hour, and route information.
4. The built-in `current_Time` workflow supports opening-hour checks in Hong Kong time.
5. The agent returns grounded, human-friendly guidance or a confirmed fallback when information is incomplete.

## Repository contents

- `instructions.md` — the main CampusGo agent instructions.
- `facility data.xlsx` — structured facility knowledge for the MVP.
- `Location of CVA and AAB.xlsx` — building-level map links and starting points.

## Recreate the MVP

1. Create an agent in Microsoft Copilot Studio.
2. Copy `instructions.md` into the agent instructions.
3. Upload both Excel files as knowledge sources.
4. Add the `current_Time` workflow as a tool.
5. Test the agent and publish it to Microsoft 365 Copilot Chat.

## Responsible AI

CampusGo prioritizes structured facility records, avoids inventing unsupported locations or live conditions, distinguishes building-level maps from indoor guidance, and provides a confirmed fallback when information is incomplete.

## Pitch deck

[CampusGo Agent Pitch Deck](https://docs.google.com/presentation/d/12e56TYxTyBgep-rpSgzi3w59bDm2XL-N1G28ENSqrxo/edit)
