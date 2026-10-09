# Publish to GitHub

```bash
cd jobmatch
git init
git add .
git commit -m "Initial commit: JobMatch prototype"
git branch -M main
# create an empty repo named jobmatch on github.com first, then:
git remote add origin https://github.com/<your-username>/jobmatch.git
git push -u origin main
```

Optional: Settings > Pages > deploy from `main` / root to get a free live demo link.
