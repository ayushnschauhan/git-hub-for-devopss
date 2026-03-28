🔧 Git Commands Cheat Sheet (Based on Your Practice)
📁 1. Initialize Repository
git init

👉 Creates a new Git repository in your current folder.

📊 2. Check Status
git status

👉 Shows:


Untracked files


Modified files


Staged files



➕ 3. Add Files to Staging Area
git add filename

Example:
git add mi.txt
git add rcb.txt

👉 Add all files:
git add .


💾 4. Commit Changes
git commit -m "your message"

Example:
git commit -m "adding mi rcb"

👉 Saves snapshot of staged files.

❌ 5. Restore (Undo Changes)
git restore filename

Example:
git restore mi.txt
git restore rcb.txt

👉 Discards unstaged changes (resets file to last commit).

🗑️ 6. Remove File (Normal Linux command)
rm filename

Example:
rm hello-dosto.txt

👉 Note: Git will detect this deletion in git status.

📂 7. View Files (Not Git but useful)
ls
ls -a


🚫 8. Wrong Command You Tried
git init hello-dosto.txt ❌

👉 git init does NOT take a file name.

🚀 Important Extra Git Commands (You SHOULD Know)
🔍 View Commit History
git log

👉 Short version:
git log --oneline


🔄 Add + Commit Shortcut
git commit -am "message"

👉 Works only for already tracked files

🔁 Undo Staging
git restore --staged filename


🧹 Remove File from Git
git rm filename


🌿 Branch Commands
git branch
git branch branch-name
git checkout branch-name

👉 New way:
git switch -c branch-name


🔀 Merge Branch
git merge branch-name


🌐 Connect to GitHub
git remote add origin <repo-url>


⬆️ Push to GitHub
git push origin main


⬇️ Pull from GitHub
git pull origin main


🧠 What You Practiced (Summary)
You successfully learned:


Repo initialization ✅


File tracking ✅


Staging files ✅


Committing changes ✅


Restoring files ✅


Checking status repeatedly ✅


That’s basically Git basics mastered 🎯

