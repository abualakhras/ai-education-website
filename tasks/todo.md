# Push project to GitHub

## Findings
- Project files: `index.html`, `claude.md` (plus this `tasks/` folder).
- Not a git repo yet. Git is installed and the git identity is already configured.
- GitHub CLI (`gh`) is **not installed**, and there are no SSH keys, so GitHub can't be reached yet.

## Plan
- [x] Install the GitHub CLI: `brew install gh` (needed the Xcode license accepted; installed with auto-update off to get past an untrusted MongoDB tap)
- [ ] You log in once (interactive, in your browser): `! gh auth login`
- [x] Add a `.gitignore` (ignores `.DS_Store`)
- [x] `git init -b main`, then commit `index.html`, `claude.md`, `tasks/todo.md` and `.gitignore`
- [ ] Create the GitHub repo and push: `gh repo create ai-education-website --private --source=. --push`
- [ ] Confirm the push worked and share the repo URL

## Review
_(filled in when done)_
