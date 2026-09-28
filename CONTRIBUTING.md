# Contributing to Statera-Guild

## Contribution Flow

Issue or Pull Request → review → Richard approval → merge.

External contributors should use Fork + Pull Request.

Organization Owner access is not granted to Guild participants
or participating companies.

## Evidence Policy v0.1

| Tier | Evidence |
|---|---|
| Tier 1 | Manufacturer official product page, datasheet, manual, CAD/engineering document |
| Tier 2 | Certification body, standards organization, government/regulatory database |
| Tier 3 | Authorized distributor or authorized system-integrator documentation |
| Tier 4 | Technical publication, academic paper, reputable technical database |

Not Evidence:

- Marketplace listing
- Anonymous forum
- Blog without primary source
- AI-generated statement
- Search-result snippet

`listed` requires at least one Tier 1–4 source under Evidence Policy v0.1.

`documented` requires at least one Tier 1 source.
Tier 2 may substitute only when Tier 1 does not exist.

AI answers are never Evidence.
The original source URL must be recorded.

### source_type mapping

- `official_product_page` → Tier 1
- `datasheet` → Tier 1
- `manual` → Tier 1
- `certification` → Tier 2
- `other` → Tier 3 or Tier 4 after case-by-case review

## Engineering Resource and Redistribution Policy

Default policy:

**metadata + official link**

Files are stored only when redistribution or reuse permission
is explicitly confirmed.

Use only official manufacturer product images.
If reuse conditions are unclear, link only.

Never upload files obtained through:

- purchase
- NDA
- Hills Robotics
- another company
- other non-public channels

`not_found` means that a resource was not found through the investigated
public path. It does not mean that the resource does not exist.

`unknown` redistribution status is treated as `link_only`.

Git LFS is not used at this stage.

The current purpose is engineering-resource and CAD discovery,
not third-party file warehousing.

## AI Working Rules

1. AI does not commit directly to `main`.
2. AI may draft only up to `listed`.
3. Every Component Card requires public source URLs.
4. Do not add Hills Robotics internal or company-provided information.
5. Connector-assisted changes require Richard confirmation.
6. AI must not mark `availability: available` without a URL.
7. AI output itself is not Evidence.

## ID Rules

Component Card:

`{Guild}-{Class}-{4 digits}`

Supplier:

`SUP-{4 digits}`

Issued IDs are immutable and never reused.
