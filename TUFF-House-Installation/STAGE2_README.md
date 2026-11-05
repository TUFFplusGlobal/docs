# TUFF+ documentation — Stage 2 (draft)

Copy the **contents** of this `TUFF-House-Installation` folder into `C:\Github\docs\TUFF-House-Installation\`.

This package adds A03–A07 and B02, plus an updated draft master control document. Your existing folders may be named `Manual-A-Field`, `Manual-B-Technical`, and `Manual-00-Governance`; these names are intentionally matched.

**Status:** DRAFT — NOT FOR CONSTRUCTION. Installation concepts are based on supplied demonstration videos, not final engineered instructions.

Before committing: close Word; inspect `git status`; ensure no `~$` files or sensitive patent material are staged.

```powershell
cd C:\Github\docs
git status
git add TUFF-House-Installation
git diff --cached --name-only
git commit -m "Add TUFF installation manual stage 2 drafts"
git push
```
