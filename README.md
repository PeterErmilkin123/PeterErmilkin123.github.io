# Peter Ermilkin Portfolio

A responsive, static portfolio for GitHub Pages. No installation, build step, or API keys are required.

## Upload to your existing repository

1. Extract the portfolio ZIP on your computer.
2. Upload the **contents** of the extracted folder to your portfolio repository. `index.html` must sit directly in the repository root, alongside `styles.css`, `projects/`, and `assets/`. Do not upload just the ZIP or put all the files inside another folder.
3. Commit the uploaded files to your publishing branch (usually `main`). Keep the repository public for your assignment.
4. In the repository, open **Settings → Pages**. Under **Build and deployment**, select **Deploy from a branch**, then your publishing branch and **/(root)**. Click **Save**. If Pages is already configured this way, you only need to upload the files.
5. Wait for deployment to finish. Open the website URL shown in Pages settings and check both project pages and the workbook download. Submit that live URL for the assignment.

Official instructions: https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site

The assignment's “Github Setup.mov” was not supplied. These instructions follow GitHub's documentation. Public repository status and live deployment must be checked on your own repository; providing these files does not complete those steps by itself.

## Files

- `index.html` — home page with personal statement, skills, projects, experience, and contact links
- `styles.css` — desktop, mobile, and print styling
- `projects/internship-monitor.html` — overview of the AI-assisted internship monitor
- `projects/internal-audit.html` — completed simulation overview and workbook link
- `assets/exam-preparation-risk-assessment.xlsx` — recovered completed workbook, copied without changes
- `assets/favicon.svg` — PE browser icon
- `.nojekyll` — disables Jekyll processing for this static site

All internal links are relative, so the site works both on a username.github.io site and under a repository path.

## Content and future edits

- The name, education, GPA, work highlights, and listed skills come from Peter's supplied résumé. The contact details used are the email and LinkedIn URL Peter supplied for the site.
- The two projects have working local overview pages. No GitHub repository URL was supplied for the internship monitor, so there is no placeholder or invented code link. When you have a public repository URL, add a “View source on GitHub” link to its project page.
- Python and GitHub Actions are identified as project technologies, not independently verified résumé skills. AI assistance is stated on the project page.
- The audit project is labeled as an educational simulation. Case figures are not represented as actual company results or current legal standards.
- The résumé PDF, phone number, instructor slides, personality report, and meeting recording are not part of the public site package.
- There are no third-party fonts, analytics, scripts, trackers, forms, or external image dependencies. Email uses a normal `mailto:` link, which opens the visitor's configured mail application.
- Update the graduation date, GPA, skills, experience, and copyright year as needed.

## Preview locally

Open `index.html` in a browser. For an HTTP preview, run `python -m http.server 8000` from this folder and open `http://localhost:8000`.

## Assignment checklist

- One-sentence professional introduction: included on the home page.
- Organized skills: included, based on the résumé.
- At least two relevant projects: included, with descriptions and linked project references.
- Usable navigation: links to sections, project pages, email, LinkedIn, and the workbook.
- GitHub setup and deployment: upload these files, confirm the repository is public, and verify the live Pages URL before submitting.
