# GlucoTrackr Landing Page 🩺📊

Welcome to the official landing page for **GlucoTrackr**, a smart, user-friendly glucose monitoring dashboard for people living with diabetes. This site was built using the [Hugo](https://gohugo.io/) static site generator and the [hugo-bootstrap-theme](https://github.com/filipecarneiro/hugo-bootstrap-theme).

![GlucoTrackr Screenshot](static/images/logo.png)

---

## 🚀 About GlucoTrackr

GlucoTrackr empowers individuals with diabetes to:

- Visualize real-time glucose trends
- Receive smart alerts for critical values
- Share reports with doctors and caregivers
- Gain AI-driven insights into blood sugar patterns

This landing page was built to showcase the product’s core features and visual identity.

---

## 🛠️ Built With

- [Hugo](https://gohugo.io/) — Fast static site generator
- [hugo-bootstrap-theme](https://github.com/filipecarneiro/hugo-bootstrap-theme) — Responsive, accessible theme
- [GitHub Pages](https://pages.github.com/) — Free hosting
- Custom illustrations generated with DALL·E

---


## 📦 Deployment

To rebuild and publish the site:

```bash
hugo --cleanDestinationDir
./publish_to_gh_pages.sh public <your-github-username>/hugo-mock-landing-page
# Hugo Mock Landing Page (Autodeployed)

This repository is an automated deployment version of my Hugo-based landing page.  
It uses GitHub Actions to build the site and deploy it to GitHub Pages every time I push to the `main` branch.

## 🔁 CI/CD Workflow

The GitHub Actions workflow is defined in `.github/workflows/gh-pages-deployment.yaml`.  
It performs the following steps:

1. Checks out the repository
2. Initializes the Hugo environment (v0.144.1)
3. Builds the static website with `hugo -D --gc --minify`
4. Publishes the `public/` output to the `gh-pages` branch using `peaceiris/actions-gh-pages`

## 🌐 Deployment URL

The website is live at:  
[https://johnkala.github.io/hugo-mock-landing-page-autodeployed/](https://johnkala.github.io/hugo-mock-landing-page-autodeployed/)

## 🧠 Claude YAML Explanation

See [`github-actions-workflow-explanation.pdf`](github-actions-workflow-explanation.pdf)  
for a line-by-line walkthrough of the GitHub Actions configuration, using Anthropic’s Claude AI.

## 🛠️ GitHub Pages Setup

- GitHub Pages is configured to deploy from the `gh-pages` branch
- Repository permissions allow GitHub Actions to write and trigger workflows

## 🧪 Live Reload

Every push to `main` triggers a new deployment.  
For example, changing `content/contact.md` immediately updates the live site via GitHub Actions.

