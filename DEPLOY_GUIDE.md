# How to Publish Your Portfolio to GitHub Pages

Follow these steps to host your website for free on GitHub.

## Prerequisite: Create a GitHub Account
If you don't have one, sign up at [github.com](https://github.com).

## Step 1: Create a New Repository
1.  Log in to GitHub.
2.  Click the **+** icon in the top-right corner and select **New repository**.
3.  **Repository name**: `portfolio` (or `jaisheel-nagda-portfolio`).
4.  **Public/Private**: Choose **Public** (required for free GitHub Pages).
5.  **Initialize**: Do **NOT** check "Add a README" or .gitignore (we have our own files).
6.  Click **Create repository**.
7.  Copy the HTTPS URL provided (e.g., `https://github.com/YourUsername/portfolio.git`).

## Step 2: Push Your Code (Run these commands)
Open a terminal in your project folder (`e:\Antigravity`) and run:

```powershell
# 1. Initialize Git
git init

# 2. Add your files
git add .

# 3. Commit your changes
git commit -m "Initial portfolio release"

# 4. Link to your GitHub repo (Replace URL with yours!)
git remote add origin https://github.com/YOUR_USERNAME/portfolio.git

# 5. Rename branch to main
git branch -M main

# 6. Push code
git push -u origin main
```

## Step 3: Enable GitHub Pages
1.  Go to your repository on GitHub.
2.  Click **Settings** (top tab).
3.  On the left sidebar, click **Pages**.
4.  Under **Build and deployment** > **Source**, select **Deploy from a branch**.
5.  Under **Branch**, select `main` and `/ (root)`.
6.  Click **Save**.

## Step 4: View Your Site
*   Wait about 1-2 minutes.
*   Refresh the Pages settings page.
*   You will see a banner: "Your site is live at..."
*   Click the link to share your new portfolio!
