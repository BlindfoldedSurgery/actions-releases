## v3.1.3 (2024-12-26)

### Fix

- **deps**: update dependency uv to v0.5.12

## v3.1.2 (2024-12-21)

### Fix

- Remove leading dash from cache suffix

## v3.1.1 (2024-12-21)

### Fix

- Check out code before installing uv

## v3.1.0 (2024-12-21)

### Feat

- Upgrade uv version to 0.5.11

### Fix

- Use explicit cache key suffix for workflows

## v3.0.0 (2024-12-20)

### Feat

- **deps**: update astral-sh/setup-uv action to v5

## v2.5.3 (2024-12-06)

### Fix

- **deps**: update dependency poetry to v1.8.5

## v2.5.2 (2024-12-05)

### Fix

- Use setup-uv action

## v2.5.1 (2024-12-04)

### Fix

- Fix typos in workflow files

## v2.5.0 (2024-12-04)

### Feat

- Support uv as build tool

### Fix

- Correctly extract version during bump (2)
- Correctly extract version during bump

## v2.4.0 (2024-12-03)

### Feat

- Update runner version to 24.04

## v2.3.5 (2024-10-14)

### Fix

- **deps**: update dependency poetry to v1.8.4

## v2.3.4 (2024-10-05)

### Fix

- **deps**: update dependency pre-commit to v4

## v2.3.3 (2024-05-08)

### Fix

- **deps**: update dependency poetry to v1.8.3

## v2.3.2 (2024-03-17)

### Fix

- Classify Poetry updates as feat/fix

## v2.3.1 (2023-12-17)

### Fix

- Use GH_TOKEN to checkout during bump

## v2.3.0 (2023-12-17)

### Feat

- Allow configuration of python-version

## v2.2.1 (2023-11-06)

### Fix

- Actually expose version outputs

## v2.2.0 (2023-11-06)

### Feat

- Expose bumped and version output for bump job

## v2.1.0 (2023-11-06)

### Feat

- Add commitizen-version workflow

## v2.0.0 (2023-10-28)

### BREAKING CHANGE

- You'll need to split up you calling job into check and bump jobs

### Feat

- Split up commitizen workflow

## v1.1.2 (2023-10-28)

### Fix

- Fix version capitalization
- Add debug env

## v1.1.1 (2023-10-28)

### Fix

- **ci**: Only push anything if bumped

## v1.1.0 (2023-10-28)

### Feat

- Allow publishing major tags

## v1.0.2 (2023-10-28)

### Fix

- Perform PR creation and automerge with different tokens

## v1.0.1 (2023-10-28)

### Fix

- Use PAT for PR creation
- Trigger first automated release

## v1.0.0 (2023-10-28)

Initial commit.
