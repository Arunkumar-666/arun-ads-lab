cd "C:\Users\ARUN KUMAR"
rename-item arunadslab.index.html index.html   # optional but typical
git init
git add index.html
git commit -m "Add landing page"
git branch -M main
git remote add origin https://github.com/<your-username>/arun-ads-lab.git
git push -u origin main
