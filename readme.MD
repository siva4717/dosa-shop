 
# 🍽️ Dosa-Shop

This project demonstrates a complete Git workflow using a feature branch (`plain-dosa`) and merging it into the `main` branch with proper rules and review process.

---

## 🔒 Step 1: Setup Rules for `main` Branch

Configure branch protection rules:

- Require at least **1 approval**
- Restrict branch **deletions**
- Block **force pushes**

---

## 🌿 Step 2: Create Feature Branch

```bash
git checkout -b plain-dosa
````

---

## 👨‍🍳 Step 3: Work on `plain-dosa`

Make multiple commits:

* Add batter
* Add ghee
* Improve texture
* Final preparation

```bash
git add .
git commit -m "Add batter"
git commit -m "Add ghee"
git commit -m "Improve texture"
git commit -m "Final preparation"
```

---

## 📜 Step 4: View Commit History

```bash
git log
git log --oneline
```

Inspect a specific commit:

```bash
git cat-file -p <commit-id>
```

---

## 🔁 Step 5: Push & Create Pull Request

```bash
git push origin plain-dosa
```

* Create PR from `plain-dosa` → `main`

---

## 👥 Step 6: Add Collaborator

* Search user: `msgopi6626`
* Send invitation
* Collaborator accepts via email

---

## 🔍 Step 7: Review Pull Request

* Reviewer checks code
* Adds comments if needed
* Approves the PR after satisfaction

---

## ✅ Step 8: Merge Pull Request

* Merge PR into `main`
* This creates a **merge commit**

### 🔀 Merge Commit:

* Has **two parents**

  * `main` branch
  * `plain-dosa` branch

---

## 🧹 Step 9: Delete Branch

```bash
git branch -d plain-dosa
git push origin --delete plain-dosa
```

---

## 📌 Git Commands Summary

```bash
git checkout -b plain-dosa
git log
git log --oneline
git cat-file -p <commit-id>
git branch -d plain-dosa
git push origin --delete plain-dosa
```

---

## 🎯 Conclusion

This workflow ensures:

* Secure main branch
* Proper code review
* Clean Git history
* Effective collaboration using Pull Requests

