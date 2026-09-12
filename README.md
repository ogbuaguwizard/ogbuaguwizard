<h1 align="center">Francis Ogbuagu</h1>
<h3 align="center">Software Engineer — Web Development, Machine Learning & Digital Products</h3>

<p align="center">
  Building production web platforms and applied ML systems, with a growing focus on digital infrastructure for African cultural and arts institutions.
</p>

<p align="center">
  <a href="https://francis.ogbuaguweb.com"><img src="https://img.shields.io/badge/Portfolio-2F81F7?style=flat-square&logo=firefox-browser&logoColor=white" /></a>
  <a href="https://linkedin.com/in/francisogbuagu"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" /></a>
  <a href="https://www.instagram.com/imfrancisogbuagu"><img src="https://img.shields.io/badge/Instagram-E4405F?style=flat-square&logo=instagram&logoColor=white" /></a>
  <a href="mailto:imfrancisogbuagu@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white" /></a>
</p>

---

## About

Software Engineer with 4+ years across web development, machine learning, and data science, and a First-Class Computer Science degree (CGPA 4.76/5.0, Federal University Lokoja). I build full-stack platforms in **React** and **Laravel**, and applied **computer vision / NLP** systems — currently focused on digital tools for African cultural institutions and heritage archives.

- 🔭 Currently building institutional and event-management platforms for arts organizations, plus ML tools for practical, real-world problems.
- 🌍 Based in Nigeria, working with organizations remotely.
- 📫 Reach me via [LinkedIn](https://linkedin.com/in/francisogbuagu), [Instagram](https://www.instagram.com/imfrancisogbuagu), or [email](mailto:imfrancisogbuagu@gmail.com).

---

## Featured Projects

### 🏗️ Full-Stack Platforms — Live, In Production

**[Art Institution Management Platform](https://github.com/ogbuaguwizard/art-institution-management-platform)** — [Live site](https://peterflemingart.com/)
Full-stack Laravel platform running Peterfleming Arts' day-to-day operations: galleries, exhibitions, artists, events with QR ticketing and check-in, an internship/participant pipeline (application → onboarding → assignments → certificates), an art-supply store with sales tracking, and an early AI-assisted image tool for artists.
- Role-based access via separate admin/user auth guards and Laravel policies (Super Admin / Admin / sector-scoped Moderator)
- Service-layer architecture, automated ticket/PDF/QR generation, Cloudinary media, Mailjet email, GitHub Actions → shared-hosting CI/CD
- **Stack:** Laravel, PHP, Alpine.js, Tailwind CSS, MySQL

**[Music Production & Management Platform](https://github.com/ogbuaguwizard/music-production-and-management-platform)** — [Live site](https://obiblomusic.com/)
Full-stack Laravel platform for a gospel music ministry: performance/recording bookings, a music & video library streamed via Spotify/Audiomack/YouTube, paid music sheets, donations, and events — behind a full admin back office.
- Paystack payment integration for donations and paid content, automated DB backups to Google Drive, CI-gated deploys with a real test suite (login, registration, email verification, password reset, protected routes)
- Privacy-conscious anonymous visitor tracking via fingerprinting (no demographic data collected)
- **Stack:** Laravel, PHP, MySQL, Paystack, Cloudinary

*Both repos are public case-study write-ups of proprietary client work (source is private, as noted in each README) — good for showing scope and architecture decisions to recruiters.*

### 🚧 In Progress

**[African Museum Artifacts API](https://github.com/ogbuaguwizard/african-museum-collections-api)**
Laravel API that pulls artifact data from public museum APIs (starting with the Met), filters for African heritage objects, and normalizes the inconsistent metadata into one unified schema — the foundation for a planned ecosystem of cultural-heritage tools (curator workspace, digital exhibition builder, collections analytics).
- UUID-keyed domain model, duplicate-safe batch importing with progress tracking, Docker-ready, PostgreSQL
- Currently importing from 1 of a planned 9 museum data sources — early stage, actively being built out
- **Stack:** Laravel 13, PHP 8.2+, PostgreSQL, Docker

### 🐍 Python Development

**[Exam Results Management System](https://github.com/ogbuaguwizard/Automated-Grading-System)**
Flask web app for exam officers to upload student results (CSV/Excel) and get automatic GPA/CGPA computation, filtering by level and semester, and per-student performance views.
- Role-based login, Pandas-driven file processing, SQLAlchemy models, responsive Bootstrap UI
- **Stack:** Python, Flask, SQLite, SQLAlchemy, Pandas, Bootstrap

### 🤖 Applied ML / Data Science

**[Trustpilot Sentiment Analyzer](https://github.com/ogbuaguwizard/trustpilot-sentiment-analyzer)** — [Live demo](https://website-sentiment-analyzer.streamlit.app/)
Streamlit app that scrapes live Trustpilot reviews for any website and runs real-time aspect-based sentiment analysis — extracts aspect/opinion pairs, classifies polarity, and visualizes the distribution. Part of a broader research framework for opinion-mining-based website evaluation. **Stack:** Python, Streamlit, BeautifulSoup4, TextBlob, NLTK, Matplotlib

**[G.T.Bank Review Analysis](https://github.com/ogbuaguwizard/G.T.Bank-review-analysis)**
Aspect, opinion, and sentiment extraction from customer reviews of G.T.Bank's services — surfaces specific service pain points rather than a single overall score. **Stack:** Python, PyABSA, Pandas

**[Access Bank Review Analysis](https://github.com/ogbuaguwizard/Access-Bank-analysis-)**
Same aspect-based opinion-mining approach applied to Access Bank Nigeria customer reviews. **Stack:** Python, PyABSA, Pandas

**[ABSA for Teacher Quality Evaluation](https://github.com/ogbuaguwizard/ABSA-for-Teacher-Quality-Evaluation-)** — final year project
Extracts lecturer names, aspects, opinions, and sentiment from student feedback to evaluate teaching quality at scale. **Stack:** Python, spaCy, PyABSA

---

## Professional Experience

**Software Engineer (Contract)** — Peterfleming Art Limited · *Nov 2023 – Present*
Designed and built a Laravel-based institutional management platform: participant portals for interns/students, admin portals for artworks/artists/inventory, and features for event registration, ticketing, and QR-based check-in.

**Software Engineer** — Yela Art Foundation · *2025 – Present*
Leading technology for a foundation supporting emerging visual artists — building systems for programme management, mentorship tracking, and administrative workflows.

**Co-Founder & Full Stack Developer** — Kanta Lokoja · *Mar 2020 – Present*
Co-founded and lead full-stack development for a grassroots football management platform (React, TypeScript) — live scoring, automated fixtures, league tables, match commentary, and statistics tracking, running continuously since 2020.

**Data Scientist Intern** — Impact Computers Lokoja · *Feb 2022 – Oct 2022*
Applied supervised/unsupervised learning (Random Forest, classification, regression) across data preprocessing, feature selection, and model evaluation.

---

## Tech Stack

<p align="left">
  <img src="https://skillicons.dev/icons?i=js,ts,php,python,react,nextjs,laravel,nodejs,mysql,tailwind,git,githubactions" />
</p>

**Languages:** JavaScript (ES6+), TypeScript, PHP, Python, SQL
**Frontend:** React, Next.js, Tailwind CSS, Bootstrap
**Backend & Data:** Laravel, Filament, Node.js, MySQL, RESTful APIs
**ML / Data Science:** Computer Vision, Transfer Learning, NLP (Aspect-Based Sentiment Analysis), ONNX.js, spaCy, PyABSA, Pandas

---

## Awards & Recognition

- 🏆 Best Graduating Student — Federal University Lokoja (2023)
- 🏆 Academic Star of the Year — NACOS, FUL (2023)
- 🏆 Student Tutor of the Year — NACOS, FUL (2023)
- 🏆 Best CGPA Award, 300 Level — NACOS, FUL (2022)

---

## GitHub Stats

<p align="left">
  <img src="https://github-readme-stats.vercel.app/api?username=ogbuaguwizard&show_icons=true&theme=default&hide_border=true&count_private=true" height="165" />
  <img src="https://github-readme-streak-stats.herokuapp.com?user=ogbuaguwizard&theme=default&hide_border=true" height="165" />
</p>

<p align="center">
  <sub>Profile views: <img src="https://komarev.com/ghpvc/?username=ogbuaguwizard&style=flat-square&color=2f81f7" alt="Profile Views" /></sub>
</p>
