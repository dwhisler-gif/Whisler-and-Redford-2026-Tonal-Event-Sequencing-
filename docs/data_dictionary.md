# Data dictionary

This file should define all variables and files used in the project.

## File naming conventions

- `raw/` — unprocessed and minimally cleaned data
- `processed/` — cleaned data created by analysis scripts
- `codebooks/` — documentation for coded variables

## Variable conventions

Use a consistent format for each variable entry:

- Name
- Description
- Type
- Units
- Coding / values
- Missing value conventions
- Notes

## Example

| Variable | Description | Type | Coding |
| --- | --- | --- | --- |
| `participant_id` | Unique participant identifier | string | anonymized ID |
| `trial_number` | Trial index within session | integer | 1..N |
| `response_time` | Reaction time in milliseconds | float | measured in ms |

## Data sharing guidance

- Remove direct identifiers before public release.
- Document any exclusions or missingness.
- Keep a separate codebook for every processed dataset.
