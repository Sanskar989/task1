

## 📘 Assignment 1: Basic Git Workflow

### 🎯 Objective:

---

### 📝 Steps Followed:

1. **Initialized a Git repository:**

   * Ran the command `git init` in the project directory to create a new local Git repository.

2. **Created a text file:**

   * Created `notes.txt` with 5–10 lines of sample content.

3. **Staged and committed the file:**

   * Used `git add notes.txt` to stage the file.
   * Used `git commit -m "feat: add initial notes file"` to make the initial commit.

4. **Made 3 meaningful changes with commits:**

   * ✏️ **Change 1:** Added a new point to the file
     `git commit -am "chore: added extra point to notes"`
   * ✏️ **Change 2:** Corrected a spelling error
     `git commit -am "fix: correct typo in line 3"`
   * ✏️ **Change 3:** Reformatted content structure
     `git commit -am "refactor: restructure the bullet list for clarity"`

5. **Viewed commit history:**

   * Ran `git log` to view the history of commits (screenshot added below).

6. **Examined differences between commits:**

   * Used `git diff <commit1> <commit2>` to compare content changes between versions.


* ✅ All commits made with meaningful messages following the **Conventional Commits** format.
* ✅ Screenshot of `git log` is attached below.
  <img width="589" alt="git log" src="https://github.com/user-attachments/assets/940d552d-555c-469d-9850-ff50ca1a1495" />
<img width="602" alt="git diff" src="https://github.com/user-attachments/assets/2b0878cd-8843-4bff-975b-e7c13480cf98" />


* ✅ Each commit's change is explained clearly above.
* ✅ This README.md summarizes the full workflow.

---
Thought for 7 seconds


Here’s a warm, down‑to‑earth version you can drop straight into **README.md**—it reads like a quick journal entry of what you actually did rather than a dry checklist.

---

## 🤝 Assignment 2 – GitHub Basics & Collaboration


1. **Logged in (or signed up) on GitHub**
   Already had an account—so I just hit **Sign In**. If you’re new, the *Sign Up* button’s right there on the homepage.

2. **Spun up a fresh repo**
   Clicked the big green **“New”** button, named it `basic-git-workflow`, added a short description, and left everything else default.

3. **Pushed my local project from Assignment 1**

   ```bash
   git remote add origin https://github.com/<username>/basic-git-workflow.git
   git push -u origin main
   ```

   Boom—my commits landed in the cloud.

4. **Added a starter README on the website**
   On the repo page, I clicked **Add file → Create new file**, named it `README.md`, typed “Hello GitHub 👋”, and committed it right from the browser.

5. **Pulled that new README back down to my laptop**

   ```bash
   git pull origin main
   ```

   Now local and remote were in perfect sync.

6. **Created a new branch for edits**

   ```bash
   git checkout -b feature/update-readme
   ```

   Think of branches as scratch pads—safe zones where experiments won’t break `main`.

7. **Updated the README with these very steps**
   Added all the details you’re reading now, then:

   ```bash
   git add README.md
   git commit -m "docs: flesh out README with assignment steps"
   ```

8. **Pushed my branch up to GitHub**

   ```bash
   git push origin feature/update-readme
   ```

9. **Opened a Pull Request (PR)**
   On GitHub, hit **Compare & pull request**, double‑checked the diff (looked good!), and clicked **Create pull request**.

10. **Reviewed & merged the PR**
    Gave it a quick self‑review (thumbs‑up from me 😄) and pressed **Merge pull request**. Done—changes now live in `main`.



* **Screenshot:** Check the `/screenshots` folder for `pull_request_success.png` showing the merged PR.
  <img width="960" alt="M1" src="https://github.com/user-attachments/assets/971316f2-a96d-4666-8ee8-dbc3012518f2" />
  ![Screenshot 2025-05-07 040554](https://github.com/user-attachments/assets/1eb29d86-55a2-430b-8e77-2fd3ea39a924)


* **Takeaway:** Branches + pull requests = clean collaboration. Even solo, it keeps history tidy and mistakes easy to roll back.

---
