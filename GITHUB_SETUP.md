# How to Upload to GitHub

Follow these steps to share your project:

## 1. Create Repository on GitHub

- Go to https://github.com/new
- Name it: `weathering-with-you`
- Click "Create repository"

## 2. Push Your Code

```bash
cd d:\Coding\weathering-with-you

git init
git add .
git commit -m "Initial commit: Rainfall prediction classifier final exam project"

git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/weathering-with-you.git
git push -u origin main
```

Replace `YOUR_USERNAME` with your GitHub username.

## 3. Get the Dataset

Download from Kaggle and save to `data/raw/weatherAUS.csv`
(Git will ignore this large file automatically)

## 4. Done!

Your project is now on GitHub. Share the link!

---

See README.md for project details.
