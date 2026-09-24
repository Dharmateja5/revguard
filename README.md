# RevGuard Documentation Website

Static documentation website for **RevGuard — Autonomous Revenue Leakage Investigation & Recovery**.

## Run locally

Open `index.html` directly in a browser, or serve the directory with any static web server.

For example:

```bash
python -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

## Publish with GitHub Pages

### Option A — Serve from repository root
1. Create a new GitHub repository.
2. Upload the contents of this folder to the repository root.
3. In GitHub, open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select your default branch (for example `main`) and `/ (root)`.
6. Save.

### Option B — Keep the site in a `docs/` folder
If you place this website inside a repository-level `docs/` directory, choose `/docs` in GitHub Pages settings instead.

## Structure

```text
RevGuard_GitHub_Website/
├── index.html
├── .nojekyll
├── README.md
├── assets/
│   ├── styles.css
│   └── app.js
└── docs/
    ├── 01_scope.html
    ├── 02_prd.html
    ├── 03_architecture.html
    ├── 04_evaluation_safety.html
    ├── 05_implementation_plan.html
    ├── 06_demo_submission.html
    ├── 07_evidence_data_spec.html
    └── 08_architecture_decisions.html
```

Each document also supports browser printing / PDF export.
