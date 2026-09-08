# Phishing Samples — Social Engineering Classification Lab (P2)

In this lab you will **clone this repo into your VS Code workspace**, read 5 phishing samples, and file a GitHub Issue for each one on THIS repo, classifying the social engineering tactic used and the psychological trigger exploited. Reference the **S.E.T. framework** (see `SET-FRAMEWORK.md`) in every Issue.

## Part 1 — Clone the repo into your VS Code workspace

1. Open your workspace: https://vscode.ivycollegiate.org/<your-name>/ and sign in.
2. Open the terminal in VS Code (menu **Terminal → New Terminal**, or **Ctrl+`**).
3. Make sure you are in your home directory. Type this command and press Enter:

   ```
   pwd
   ```

   If it does NOT end with your username (e.g. `/home/achen27`), run:

   ```
   cd ~
   ```
4. Clone the class repo (copy-paste this whole line, then press Enter):

   ```
   git clone https://github.com/ivycollegiate-development/phishing-samples.git
   ```
5. Verify it worked:

   ```
   ls
   ```

   You should see a new folder called `phishing-samples`. Open it in VS Code via the Explorer sidebar.

## Part 2 — Read the material

6. Read `SET-FRAMEWORK.md` — the S.E.T. taxonomy you will use in every Issue.
7. Read each file in `emails/` — they are numbered `email-1.txt` … `email-5.txt`.

## Part 3 — File your Issues on GitHub (on this repo)

8. In a browser tab, go to the **Issues tab**: https://github.com/ivycollegiate-development/phishing-samples/issues (sign in to GitHub with your school account if needed).
9. Click **New issue** and file **one Issue per email — 5 Issues total**:
   - Title: `Email N — <tactic name>`
   - Body must include:
     - **Tactic:** the primary S.E.T. tactic used
     - **Trigger:** the psychological instinct it exploits
     - **Red flags:** at least 2 concrete indicators (domain tricks, urgency, sender details…)
10. Submit on Google Classroom: paste the links to your 5 Issues.

Your teacher reviews the Issues on this repo to check understanding. You are not editing any code — that's why there's no fork and nothing to push.

All samples are teacher-drafted fakes based on publicly documented campaigns. No live malicious content.
