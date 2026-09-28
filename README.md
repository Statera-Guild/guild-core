# Statera-Guild / guild-core

**STATERA — Balance the Intelligence**

Statera-Guild is the Engineering Ecosystem for Physical AI component,
supplier, and engineering-resource knowledge.

## Relationship to PASG

PASG is the Physical AI framework whose SSOT is maintained in
`Statera-Library/00_PASG_Core`.

Statera-Guild references PASG coordinates
(`EAL`, `OPL`, `Product/Hardware Platform`) and applicable qualifiers.

Statera-Guild does not redefine PASG and is not a PASG Axis.

## Guild Taxonomy v0.1

| Guild | Code | Classes |
|---|---|---:|
| Driving | DRV | 9 |
| Power | PWR | 9 |
| Sensor | SEN | 14 |
| Compute | CMP | 7 |
| Manipulation | MAN | 6 |
| **Total** | | **45** |

### Single Ownership

- Encoder → Sensor
- Gearbox/Reducer → Driving
- Joint Actuator Module → Manipulation
- Network Equipment / Wireless Communication → Compute

Manufacturers are not directory categories.
Products link to suppliers through `supplier_id`.

## Data Model

Component Class → Component Card → Engineering Resources

Component Card ID:

`{Guild}-{Class}-{4 digits}`

Example:

`CMP-EAM-0001`

Supplier ID:

`SUP-{4 digits}`

Example:

`SUP-0001`

IDs are immutable and never reused.

## Status

Only the following product Card states are currently used:

- `listed`
- `documented`

The terms `verified`, `certified`, `approved`, `recommended`,
and `PASG-certified` are not used before Phase 3.

Supplier registry presence uses `listed` only.
Product documentation/evaluation belongs to Component Cards.

## Current Pilot

Future pilot categories:

- `cards/compute/edge_ai_module/`
- `cards/compute/industrial_pc/`

Initial candidate suppliers:

- NVIDIA
- Qualcomm
- ASUS
- Neousys

No product Cards are populated in the initial structure.

## Disclaimer

Statera is an independent engineering and knowledge initiative.

Statera-Guild is not the official procurement system,
approved supplier list, or engineering standard of any company,
including Hills Robotics.
