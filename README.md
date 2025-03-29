# GlucoTrackr Landing Page 🩺📊

Welcome to the official landing page for **GlucoTrackr**, a smart, user-friendly glucose monitoring dashboard for people living with diabetes. This site was built using the [Hugo](https://gohugo.io/) static site generator and the [hugo-bootstrap-theme](https://github.com/filipecarneiro/hugo-bootstrap-theme).

![GlucoTrackr Screenshot](static/images/glucose-trend-graph.png)

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

## 📂 Repo Structure

. ├── content/ # Site content (features, pages, etc.) ├── static/images/ # Custom branding and feature illustrations ├── layouts/ # Customized theme templates ├── assets/css/ # Custom styles ├── config.toml # Site configuration ├── publish_to_gh_pages.sh # Deploy script └── USER-STORIES.md # 20 user stories for the product

---


## 📦 Deployment

To rebuild and publish the site:

```bash
hugo --cleanDestinationDir
./publish_to_gh_pages.sh public <your-github-username>/hugo-mock-landing-page
