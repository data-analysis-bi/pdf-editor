# Private PDF Pro

This repository contains the offline Private PDF Pro application extracted for local usage.

## Option 1: Using it Locally

To use this application on your PC, you just need to serve these files using a local web server.

### If you have Python installed (Recommended)
1. Open up a terminal or command prompt in this folder.
2. Run the following command:
   ```bash
   python -m http.server 8080
   ```
3. Open your browser and go to `http://localhost:8080/`

### If you have Node.js installed
1. Open up a terminal in this folder.
2. Run the following command:
   ```bash
   npx serve .
   ```
3. Open your browser to the local link provided in the terminal (usually `http://localhost:3000`).

---

## Option 2: Hosting it on GitHub (To use with a link)

Since this is a fully client-side application (HTML/JS/CSS), you can easily host it for free using **GitHub Pages**.

### Steps to deploy:
1. Go to [GitHub.com](https://github.com/) and log in to your account.
2. Create a **New Repository**. Give it a name like `my-pdf-pro`. Do **not** initialize it with a README, .gitignore, or license.
3. Once created, GitHub will show you a page with some commands under "...or push an existing repository from the command line".
4. Open a terminal in this folder on your PC and run those commands. They will look like this:
   ```bash
   git remote add origin https://github.com/YOUR-USERNAME/my-pdf-pro.git
   git branch -M main
   git push -u origin main
   ```
5. After pushing, go to your repository's **Settings** tab on GitHub.
6. Click on **Pages** in the left sidebar.
7. Under "Build and deployment" -> "Source", select **Deploy from a branch**.
8. Under "Branch", select `main` (or `master`) and `/ (root)` folder, then click **Save**.
9. Wait about a minute. GitHub will provide you with a live link (e.g., `https://your-username.github.io/my-pdf-pro/`) at the top of the Pages settings. You can now use that link anywhere!
