# P3: Feature-branch Git workflow

I use a feature branch when I want to work on one change without editing `main` directly.

## Steps
1. Start on `main` and run `git pull`.
2. Create a branch: `git switch -c feature/about-section`.
3. Make the change and check it with `git status`.
4. Stage and commit: `git add .` then `git commit -m "Add about section"`.
5. Return to main with `git switch main` and merge using `git merge feature/about-section`.
6. Push the updated main branch.

This page shows the idea of keeping one feature separate until it is ready.