# sd-team-repo

Practice repository for **UTS 43030 Professional Practice in Computing - Module 3: Software Development Tools**.

- **Lab 1 (Lecture 1)** - Git essentials: create/clone/associate a repo, branching & merging,
  amend / revert / reset / checkout-by-hash, rebase and conflict resolution.
  The three team roles (Team Leader, Member 1, Member 2) are simulated with three local clones.
- **Lab 2 (Lecture 2)** - GitHub Actions: `.github/workflows/main.yml` runs on every push to `main`,
  adds an "Updated by ..." line to `index.html`, appends a log entry to this README,
  commits the changes back with `GITHUB_TOKEN`, and publishes the site to GitHub Pages.

| Role        | Page          | Branch used in Lab 1 |
|-------------|---------------|----------------------|
| Team Leader | `leader.html` | `leader-feature`     |
| Member 1    | `member1.html`| `member1-feature`    |
| Member 2    | `member2.html`| `member2-feature`    |

## Workflow update log

<!-- Lab 2: main.yml appends one log line below on every push to main. -->
