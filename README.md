# Portfolio

This is a static portfolio website for Dennis Ngugi Wambui.

## Local preview
Open `Index.html` in a browser or run a simple local server, for example (PowerShell):

```powershell
# serve current folder on port 8000 (PowerShell - Python must be installed)
python -m http.server 8000
# then open http://localhost:8000/Index.html
```

## Publishing with GitHub Pages
1. Create a repository on GitHub named `my-portfolio` (or the name you prefer).
2. Add the remote (already provided):

```powershell
git remote add origin https://github.com/dennisngugiwambui/my-portfolio.git
git branch -M master
git push -u origin master
```

3. On GitHub, go to the repository Settings -> Pages and enable GitHub Pages from the `master` branch (root). The site URL will be:

```
https://dennisngugiwambui.github.io/my-portfolio/
```

If the push requires authentication, use a Personal Access Token (PAT) or set up SSH keys.

## Notes
- If you'd like me to push from this environment I can attempt to run the git commands, but you will need to provide credentials or a PAT when prompted. Otherwise follow the steps above locally.

