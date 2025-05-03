# Git & GitHub: Hands-On Project with Commands

## ✨ Project: `student-info`

---

### 📁 Step 1: Create a Folder & Initialize Git

```bash
mkdir student-info
cd student-info
git init
```

**Explanation:** Initializes a new Git repository in the project folder.

---

### 📄 Step 2: Create a File

```bash
echo "Name: Sabareeswaran" > student.txt
```

**Explanation:** Creates a text file with a sample name.

---

### ➕ Step 3: Stage & Commit the File

```bash
git add .
git commit -m "Initial commit - added student name"
```

**Explanation:** Stages all changes and creates the first commit (a snapshot of the project).

---

### ✏️ Step 4: Modify the File

```bash
echo "Email: sabaree@gmail.com" >> student.txt
git add .
git commit -m "Added email field"
```

**Explanation:** Appends email to the file and creates a second version with a commit.

---

### 🔄 Step 5: View Commit History

```bash
git log
```

**Explanation:** Displays the list of all commits and their commit IDs (hashes).

---

### ⬅️ Step 6: Checkout Previous Version

```bash
git checkout <first-commit-id>
cat student.txt
```

**Explanation:** Moves the working directory to the selected commit. The file will show the version without the email.

---

### ↺ Step 7: Return to Latest Version

```bash
git checkout main
```

**Explanation:** Switches back to the latest version on the main branch.

---

### ☁️ Step 8: Push to GitHub

1. Create a repository on GitHub named `student-info`
2. Connect and push your local repo:

```bash
git remote add origin https://github.com/<your-username>/student-info.git
git branch -M main
git push -u origin main
```

**Explanation:** Connects local Git repo to GitHub and uploads code.

---

### 🤖 Extra Tips

```bash
git log --oneline
```

**Explanation:** Shows commit history in a compact format.

---

### 🔄 Summary Table

| Action                    | Command                          |
| ------------------------- | -------------------------------- |
| Initialize Git            | `git init`                       |
| Add file                  | `git add .`                      |
| Commit file               | `git commit -m "message"`        |
| View history              | `git log` or `git log --oneline` |
| Checkout previous version | `git checkout <commit-id>`       |
| Return to latest version  | `git checkout main`              |
| Add GitHub remote         | `git remote add origin <URL>`    |
| Push to GitHub            | `git push -u origin main`        |

---

Now you're ready to shoot your video with perfect command-line flow and real hands-on demo! 🚀
