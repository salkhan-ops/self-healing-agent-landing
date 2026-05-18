# Self Healing Agent Landing Page

Static GitHub Pages landing page / UI preview for the Self Healing Agent project.

This repo contains only frontend static files:

- `index.html`
- `style.css`
- `assets/`

No backend, API keys, agent logic, or cloud credentials should be stored here.

touch index.html style.css README.md .nojekyll
mkdir -p assets

# paste the index.html block
# paste the style.css block
# paste the README.md block

python3 -m http.server 8000

git init
git status
git add .
git commit -m "Initial static landing page"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/self-healing-agent-landing.git
git push -u origin main