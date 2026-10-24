# X Simulator

Interactive simulator of how a website goes live on **Docker / Kubernetes + Apache + JBoss + PostgreSQL / MySQL**. It deploys a dummy site, `phitz-meow.simulator.com`, step by step, then lets you break it and fix it.

Single `index.html`. No build, no backend, nothing is actually deployed.

## Features

- Docker Compose or Kubernetes, PostgreSQL or MySQL
- Step-by-step deploy with config files, commands and logs
- Type the commands yourself (Tab autofills the next one)
- Live view of Apache, JBoss and the database, plus a browser preview of the site
- Visitor request animation
- Five incidents to fix: traffic spike, database crash, out of memory, bad release, Apache down

## Run

Open `index.html` in a browser.

## Host on GitHub Pages

1. Add `index.html` to the repo root.
2. **Settings → Pages → Deploy from a branch**, pick your main branch and `/ (root)`.
3. Open `https://<username>.github.io/<repo>/`.

## Customise

Edit `index.html`: `steps()` for deploy steps, `DB` for databases, `SC` for scenarios, `run()` for commands.

*Teaching simulation only. Commands and logs are simplified.*
