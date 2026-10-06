ALISA BLESKE PORTFOLIO SITE

This folder is a complete static website. No build step, no server code, no database.

Contents
- index.html: the page
- resume.pdf, stanford-nil-case-study.pdf, career-prospectus.pdf, events-portfolio.pdf: linked documents
- operating-system.png: Chief of Staff fact sheet
- portfolio-1.jpg through portfolio-7.jpg: portfolio page previews

All links between these files are relative, so keep every file together in the same folder.
Fonts load from Google Fonts; nothing else is external.

To publish
Upload the whole folder to any static host. Any of these work on a free plan:
- Netlify: drag the folder onto app.netlify.com/drop
- Vercel: new project, import the folder (framework preset: Other)
- Cloudflare Pages: create a project and upload the folder directly
- GitHub Pages: push the folder to a repo and enable Pages on the main branch

A custom domain (for example alisableske.com) can be connected in the host's domain settings.

To update later
Replace the changed file (for example a new resume.pdf with the same name) and redeploy.
