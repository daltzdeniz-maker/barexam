# 🇵🇭 Philippine Bar Exam Practice Tool

An AI-powered practice tool for Philippine Bar Examination candidates. Generates scenario-based questions styled after actual past bar exams, and provides instant analysis and feedback on your answers.

## Features

- **8 Subject Areas**: Political Law, Labor Law, Civil Law, Taxation, Mercantile Law, Criminal Law, Remedial Law, Legal Ethics
- **AI-Generated Questions**: Scenarios crafted in the style of actual Philippine Bar Exams, referencing real statutes, the Constitution, and jurisprudence
- **Answer Analysis**: Submit your answer and receive instant AI feedback with score, strengths, weaknesses, missing citations, and a model answer
- **Session Statistics**: Track your attempts, excellent answers, and score rate
- **Past Bar References**: Quick links to LawPhil, Chan Robles, SC Bar Matters, and Official Gazette

## How to Deploy on GitHub Pages

### Step 1: Create a GitHub Repository

1. Go to [github.com](https://github.com) and sign in
2. Click **New repository** (the `+` button, top right)
3. Name it something like `ph-bar-review` or `bar-exam-practice`
4. Set it to **Public**
5. Click **Create repository**

### Step 2: Upload the File

**Option A — GitHub Web UI (easiest):**
1. In your new repository, click **Add file → Upload files**
2. Drag and drop `index.html`
3. Commit the file

**Option B — Git command line:**
```bash
git init
git add index.html
git commit -m "Initial commit: PH Bar Exam practice tool"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/ph-bar-review.git
git push -u origin main
```

### Step 3: Enable GitHub Pages

1. Go to your repository → **Settings** → **Pages** (left sidebar)
2. Under **Source**, select **Deploy from a branch**
3. Choose `main` branch, `/ (root)` folder
4. Click **Save**
5. Wait ~1 minute, then visit: `https://YOUR_USERNAME.github.io/ph-bar-review/`

## How to Use

1. **Select a subject** from the navigation bar (Political Law, Civil Law, etc.)
2. **Click "Generate Question"** — the AI will create a scenario-based question in the style of past bar exams
3. **Write your answer** in the text area using the IRAC method (Issue, Rule, Application, Conclusion)
4. **Click "Analyze My Answer"** — receive detailed feedback with score, strengths, gaps, and missing citations
5. **View Model Answer** at any time for reference
6. **Generate a new question** to continue practicing

## Legal Topics Covered

- Constitutional Law, Administrative Law, Election Law (Political Law)
- Labor Standards, Labor Relations, POEA/OWWA (Labor Law)
- Persons and Family Relations, Property, Obligations and Contracts (Civil Law)
- National Internal Revenue Code, Local Government Code, Tariff (Taxation)
- Corporation Code, Negotiable Instruments, Insurance (Mercantile Law)
- Revised Penal Code, Special Penal Laws (Criminal Law)
- Rules of Court, Evidence, Special Proceedings (Remedial Law)
- Code of Professional Responsibility and Accountability (Legal Ethics)

## Past Bar Exam Resources Referenced

- [Supreme Court Bar Matters](https://www.sc.judiciary.gov.ph/bar-matters/)
- [LawPhil Bar Questions Archive](https://lawphil.net/bar/bar.html)
- [Chan Robles Bar Examinations](https://www.chanrobles.com/barexaminations.htm)
- [Official Gazette of the Philippines](https://www.officialgazette.gov.ph)

## Notes

- This tool uses the Anthropic Claude API. The API key is handled server-side via Claude.ai when using the artifact directly.
- For self-hosting outside GitHub Pages, you would need to add your own Anthropic API key (see the `callClaude` function in `index.html`).
- Questions are AI-generated and for practice purposes only. Always verify legal information against official sources.

---

Good luck on the Bar! *Mabuhay ang mga abogado ng Pilipinas!* ⚖️🇵🇭
