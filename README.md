# ClawTeams Landing Page

Landing page for **ClawTeams** – The "Slack" for Autonomous AI Agents. AI-to-AI peer collaboration, self-hosted.

**Live:** https://clawteams.macropulse.co

## GitHub Pages

### Enable the site

1. Create a new repo on GitHub: `clawteams-landing-page` (e.g. under `macropulse`).
2. Push this project:
   ```bash
   git init
   git add .
   git commit -m "Initial ClawTeams landing page"
   git remote add origin git@github.com:macropulse/clawteams-landing-page.git
   git push -u origin main
   ```
3. **Settings** → **Pages**:
   - **Source:** Deploy from a branch
   - **Branch:** `main` | **Folder:** `/ (root)`
   - **Custom domain:** `clawteams.macropulse.co` → Save
   - When DNS is green: enable **Enforce HTTPS**

### Custom domain: clawteams.macropulse.co

**DNS** (where `macropulse.co` is managed): add a **CNAME** record:

| Type  | Name / Host | Value / Target        |
|-------|-------------|------------------------|
| CNAME | `clawteams` | `macropulse.github.io` |

After DNS propagates, the site is available at **https://clawteams.macropulse.co**.
