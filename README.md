# Interview Assignments Template

Template repository for coding/architecture/design assignments used in interviews.

Assignments are grouped by **position type**. Each task should define **tiered requirements*- (e.g., Tier 1 = Junior, Tier 4 = Staff) so you can assess depth, not just completion.

## How to Use This Repo

### 1. Create a Candidate Repo

- **Create a new public repo*- using this template.
  - Give it a unique name **without personal data* - (GDPR): e.g. `pv-int-250722`, `pv-prospect-int-250722`.
- **Remove irrelevant assignment folders and files*- (leave only what you’ll use).
- **Enable branch protection*- on `main` (require PRs).

### 2. Invite the Candidate

- Add the candidate with **Write*- access.

### 3. During the Interview

Ask the candidate to:

  1. Clone the repo.
  2. Create a feature branch (`feature/solution` or similar).
  3. Commit/push work as they go.
  4. Open a Pull Request into `main` at the end of the coding assignment.

> (If time-boxed live coding: remind them it’s okay to leave TODOs and explain trade-offs in the PR description.)

### 4. After the Interview

- Review via the PR
- Record scores in your scorecard and archive the repo.

## Repository Structure (example)

```yml
backend/
  <assignment-name>/
    README.md          # Problem statement & tiers
    SCORECARD.md       # Scorecard
    data/              # Sample inputs
frontend/
devops/
```

## Tiering Guidelines (quick reminder)

- **Tier 1**: Baseline correctness, simplest path.
- **Tier 2**: Broader functionality, simple analytics/UX.
- **Tier 3**: Concurrency, scalability, integration points.
- **Tier 4**: Advanced optimizations, resilience, creativity.

## Privacy & Compliance

- No candidate names or other personal data in repo names, branches, or commits.
