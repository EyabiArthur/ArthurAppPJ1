
git init
git add .
git commit -m "chore: create Flutter project my_first_app"

# after step 4 edits
git add lib/main.dart
git commit -m "feat: show Hello, Eyabi! and change theme seed colour"

# after step 5/6 edits
git add lib/main.dart
git commit -m "feat: add second Text in Column and log screen width"

git branch -M main
git remote add origin https://github.com/<your-username>/my_first_app.git
git push -u origin main
