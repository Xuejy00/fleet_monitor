# Publish The Project Page

This folder is a GitHub Pages-ready static site. All links are relative, so it can be hosted from a project page such as:

```text
https://xuejy00.github.io/fleet_monitor/
```

Recommended steps for a project page on your `Xuejy00/fleet_monitor` repository:

```powershell
cd C:\Users\xjy47\Desktop\DistMon-main\Review\web_template\Academic-project-page-template-master
git init
git checkout -b gh-pages
git add .
git commit -m "Initial project page"
git remote add origin https://github.com/Xuejy00/fleet_monitor.git
git push -u origin gh-pages
```

Then open GitHub:

1. Go to `Settings` -> `Pages`.
2. Select branch `gh-pages` and folder `/root`.
3. Save and wait for GitHub Pages to deploy.

Do not push this folder to the code repository's `main` branch unless you explicitly want to replace the repository root with the website files.

If this is published under a different repository, update the `og:url` meta tag in `index.html` to the final public URL.
