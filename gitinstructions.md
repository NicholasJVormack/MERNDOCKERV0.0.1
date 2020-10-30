

echo "# MERNDOCKERV0.0.1" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/NicholasJVormack/MERNDOCKERV0.0.1.git
git push -u origin main

git remote set-url origin https://github.com/NicholasJVormack/MERNDOCKERV0.0.1.git