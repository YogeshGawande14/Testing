# Tixify — GitHub Commit and Submission Plan

## Repository identity
Use **Tixify** as the academic project title. The local backend folder is named `BMS`, as the user clarified; this is an internal codebase name and does not change the project title. Do not present Tixify as BookMyShow or as affiliated with it.

## Before pushing
- [ ] Confirm the linked repository and branch.
- [ ] Run `git status`.
- [ ] Exclude `target/`, `.idea/`, temporary files and local secrets.
- [ ] Check `application.properties` and SQL files for credentials/private data.
- [ ] Verify React exists before claiming React implementation.
- [ ] Add `README.md` and `docs/` to the correct repository root.

## Example commit
If these files are added as one batch now, one accurate commit is appropriate:

```bash
git status
git add README.md docs/
git commit -m "docs: add Tixify Activity 2 documentation"
git push
```

Only create separate commits for genuinely separate changes. Do not backdate commits or fabricate earlier development history.

## Submission checklist
- [ ] Code and docs pushed to linked repo.
- [ ] README project title is Tixify.
- [ ] Five modules align with submitted scope.
- [ ] Implementation claims are verified.
- [ ] No secrets committed.
- [ ] External guide discussion recorded accurately.
- [ ] Faculty sign-off obtained through the official process.
- [ ] Repository link submitted through the college process.

Repository URL: [Paste actual URL]
