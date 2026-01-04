# Static Website from DOCX

This website was generated from `小型环面包络蜗杆的新型加工方法.docx`.

## Project Structure
- `index.html`: The main website content.
- `style.css`: Stylesheet for the paper-like layout.
- `images/`: Directory containing extracted images from the document.

## Deployment to GitHub Pages

1.  Initialize a git repository in this folder (if not already done):
    ```bash
    git init
    ```
2.  Add all files:
    ```bash
    git add .
    ```
3.  Commit changes:
    ```bash
    git commit -m "Initial commit of static site"
    ```
4.  Create a repository on GitHub.
5.  Link your local repository to GitHub:
    ```bash
    git remote add origin <your-github-repo-url>
    ```
6.  Push to GitHub:
    ```bash
    git push -u origin main
    ```
7.  Go to your GitHub repository **Settings** -> **Pages**.
8.  Select `main` branch (and `/root` folder) as the source.
9.  Save. Your site will be live at `https://<username>.github.io/<repo-name>/`.
