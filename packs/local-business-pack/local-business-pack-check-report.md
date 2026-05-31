# Local Business Skill Pack Check Report

This report records the pre-upload verification for Local Business Skill Pack v0.1.0.

## Skills Checked

1. `local-business-marketing-plan`
2. `review-reply-generator`
3. `service-menu-generator`
4. `promotion-campaign-planner`
5. `customer-message-reply`
6. `business-profile-optimizer`

## Round 1: Structure and Required Content

Status: Passed.

Verification scope:

- Pack-level files exist: `README.md`, `use-cases.md`, `safety-guidelines.md`, and `roadmap.md`.
- Each skill directory exists.
- Each skill includes `SKILL.md`, `README.md`, `examples.md`, `output-template.md`, and `checklist.md`.
- Each `SKILL.md` includes YAML frontmatter with the expected skill name.
- Each `SKILL.md` includes `## 中文注释`.
- Each `SKILL.md` includes the required sections:
  - Purpose
  - Best for
  - Not for
  - Input
  - Output
  - Process
  - Quality Bar
  - Example Input
  - Example Output
  - Safety / Compliance Notes
- Each `examples.md` includes at least 2 examples.
- All 6 templates exist.
- All 4 example folders include a v0.1.0 placeholder README.

Per-skill result:

| Skill | Required Files | Required SKILL.md Sections | 中文注释 | Examples |
| --- | --- | --- | --- | --- |
| `local-business-marketing-plan` | 5/5 passed | Passed | Present | 2 |
| `review-reply-generator` | 5/5 passed | Passed | Present | 2 |
| `service-menu-generator` | 5/5 passed | Passed | Present | 2 |
| `promotion-campaign-planner` | 5/5 passed | Passed | Present | 2 |
| `customer-message-reply` | 5/5 passed | Passed | Present | 2 |
| `business-profile-optimizer` | 5/5 passed | Passed | Present | 2 |

## Round 2: Risk and Safety

Status: Passed.

Verification scope:

- Safety language covers fabricated facts, reviews, credentials, claims, metrics, and user data.
- Safety language covers no guaranteed sales, customer growth, rankings, platform approval, or business results.
- Safety language covers private customer data and privacy risk.
- Each checklist contains actionable human review items.
- Each output template has a substantial Markdown structure.
- No obvious API keys, GitHub tokens, private keys, passwords, or secret assignments were found.

Per-skill result:

| Skill | Safety Coverage | Checklist Items | Output Template Sections |
| --- | --- | ---: | ---: |
| `local-business-marketing-plan` | Passed | 8 | 11 |
| `review-reply-generator` | Passed | 8 | 9 |
| `service-menu-generator` | Passed | 8 | 11 |
| `promotion-campaign-planner` | Passed | 8 | 11 |
| `customer-message-reply` | Passed | 8 | 9 |
| `business-profile-optimizer` | Passed | 8 | 10 |

## Upload Note

GitHub Actions validation is intentionally not included in this PR because the currently available GitHub OAuth token does not include the `workflow` scope required to push files under `.github/workflows/`.
