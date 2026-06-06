# Structural Estimation for Energy and Climate Decision-Making

This project applies structural estimation concepts to energy and climate analytics. The main objective is to understand how observed energy and emissions outcomes can be interpreted as the result of underlying decision-making processes involving economic growth, energy demand, technology, policy constraints, and CO₂ emissions.

Using country-level energy and climate data, the project explores the relationship between socioeconomic indicators, energy consumption, carbon intensity, and emissions patterns. The analysis is designed to move beyond descriptive statistics and prediction by introducing a utility-based and counterfactual perspective.

The project focuses on questions such as:

- Which factors are associated with higher or lower CO₂ emissions?
- How do energy consumption, GDP, population, and carbon intensity interact?
- How can simplified structural models help explain observed energy choices?
- What could change under alternative policy or technology scenarios?

The goal is to build an educational and analytical bridge between energy economics, climate data, and structural estimation.

## Project Deliverables: Cinematic Educational Animation

To make these complex concepts accessible, the project includes the production of a Kurzgesagt-inspired cinematic sci-fi educational animation. 
Follow our main character, KAI, as he travels through time to understand human decision-making via structural estimation—starting with an intuitive online dating example before scaling up to global climate policy simulations.

## Quick Start: Safe Git Workflow

When collaborating on this project, it is crucial to pull updates without overwriting your own local, uncommitted work. Follow this safe Git workflow to avoid conflicts and lost progress:

### 1. Save your local changes
Before pulling others' work, stash your local modifications safely away:
```bash
git stash
```

### 2. Fetch and Pull updates (with Rebase)
Fetch the latest changes from the remote repository and replay your local commits on top of them. This keeps the history clean and avoids messy merge commits:
```bash
git pull --rebase origin main
```
*(Note: Replace `main` with your target branch name if you are collaborating on a different branch)*

### 3. Restore your local changes
Bring back the work you stashed in step 1. If there are any conflicts with the newly pulled code, Git will prompt you to resolve them now without overwriting your work:
```bash
git stash pop
```

### 4. Resolving Conflicts (If applicable)
If `git stash pop` or the `rebase` results in a merge conflict:
- Open the conflicted files in your editor and resolve the differences manually.
- Run `git add <resolved-file>` to mark them as resolved.
- If you were rebasing, run `git rebase --continue`.
