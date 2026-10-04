# Sumit Jaiswal — Professional Portfolio

A GitHub Pages-ready personal portfolio for **Sumit Jaiswal**, Electrical Commissioning Engineer.

## Website focus

- Siemens New Test Centre (NTC) experience
- Panel testing and commissioning
- Siemens SINAMICS drives
- Siemens S7-1200 / S7-1500
- TIA Portal
- PROFINET
- Troubleshooting
- Customer/site technical support
- Siemens Technical Academy apprenticeship
- Best Apprentice achievement

## File structure

```text
Sumit_Jaiswal_GitHub_Pages/
├── index.html
├── .nojekyll
└── README.md
```

`index.html` is the website entry point. `.nojekyll` tells GitHub Pages to serve this as a plain static website without Jekyll processing.

## Publish with GitHub Pages

### Option 1 — easiest: upload the files on GitHub

1. Sign in to GitHub.
2. Create a **new public repository**. A good repository name is:
   `sumit-jaiswal-portfolio`
3. Open the new repository.
4. Upload:
   - `index.html`
   - `.nojekyll`
   - `README.md`
5. Commit the files to the `main` branch.
6. Open **Settings → Pages**.
7. Under **Build and deployment**, select:
   - **Source:** Deploy from a branch
   - **Branch:** `main`
   - **Folder:** `/(root)`
8. Click **Save**.
9. Wait for GitHub Pages to deploy the site.

Your project-site URL will normally be:

```text
https://YOUR-GITHUB-USERNAME.github.io/sumit-jaiswal-portfolio/
```

Replace `YOUR-GITHUB-USERNAME` with your actual GitHub username.

### Option 2 — Git command line

After creating the repository on GitHub:

```bash
git clone https://github.com/YOUR-GITHUB-USERNAME/sumit-jaiswal-portfolio.git
cd sumit-jaiswal-portfolio

# Copy index.html, .nojekyll and README.md into this folder.

git add .
git commit -m "Add Sumit Jaiswal portfolio"
git branch -M main
git push -u origin main
```

Then configure GitHub Pages:

**Repository → Settings → Pages → Deploy from a branch → main → /(root) → Save**

## For the Siemens application

After the site is published, use the **live HTTPS URL** in the Siemens Website field, for example:

```text
https://YOUR-GITHUB-USERNAME.github.io/sumit-jaiswal-portfolio/
```

Do **not** enter a `sandbox:/...` link. That is only a local ChatGPT file link and is not publicly accessible.

## Updating the portfolio

Whenever you change `index.html` and push the change to `main`, GitHub Pages can publish the updated version.

## Important privacy note

GitHub Pages sites are public. Do not add passwords, personal identification documents, confidential Siemens project information, internal drawings, customer information, or other confidential company material.

## Official GitHub Pages documentation

- https://docs.github.com/en/pages/getting-started-with-github-pages
- https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site
