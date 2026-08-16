<div align="center">

<img src="./assets/hero.svg" width="100%" alt="Flat illustration of a developer at a desk: a Django model open in a code window, a stack of API servers, a phone running the app and a small accuracy chart">

# Anuj Kumar Kushwaha

**I build the server, the app that talks to it, and the deploy that keeps it up.**

Python and Django on the backend, Flutter on the phone, Postgres underneath.
Whole applications, in public, with tests — not snippets.

<a href="https://github.com/PRiNCeKUsHW/marginalia"><img alt="Latest build: Marginalia" src="https://img.shields.io/badge/latest%20build-Marginalia-58a6ff?style=flat-square&labelColor=0d1117"></a>
<a href="https://www.linkedin.com/in/anuj-kushwaha-76b659210/"><img alt="LinkedIn profile" src="https://img.shields.io/badge/LinkedIn-0d1117?style=flat-square&logo=linkedin&logoColor=4493f8"></a>
<a href="mailto:anuj.kush03@gmail.com"><img alt="Email me" src="https://img.shields.io/badge/Email-0d1117?style=flat-square&logo=gmail&logoColor=ea4335"></a>
<a href="https://portfolio-site-bk5i.onrender.com/"><img alt="Portfolio site" src="https://img.shields.io/badge/Portfolio-0d1117?style=flat-square&logo=render&logoColor=ffffff"></a>

</div>

---

## About

Most of what lives here is a complete application rather than an exercise. The current
one, **Marginalia**, is a writing platform in two halves — a Flutter client and a Django
REST API on Postgres — deployed, documented with Swagger, and covered by 109 API tests
and 35 widget tests. Before it, **HireHorizon** began as a Flask blog and was rewritten
as five Django apps carrying feeds, follows, messaging and notifications.

The other half of the account is applied ML: Keras CNNs that ended up behind Flask forms
instead of stopping at the notebook, plus scikit-learn work on sonar, spam and diabetes
datasets. I gravitate to the unglamorous parts — sending mail when the host blocks SMTP,
picking the right Postgres pooler mode, giving a diff tool a parser you can extend.

---

## Tech Stack

Only what the repositories here actually run on.

| | |
|:--|:--|
| **Languages** | ![Python](https://img.shields.io/badge/Python-0d1117?style=flat-square&logo=python&logoColor=3776AB) ![Dart](https://img.shields.io/badge/Dart-0d1117?style=flat-square&logo=dart&logoColor=0175C2) ![JavaScript](https://img.shields.io/badge/JavaScript-0d1117?style=flat-square&logo=javascript&logoColor=F7DF1E) ![HTML and CSS](https://img.shields.io/badge/HTML%2FCSS-0d1117?style=flat-square&logo=html5&logoColor=E34F26) ![C++](https://img.shields.io/badge/C%2B%2B-0d1117?style=flat-square&logo=cplusplus&logoColor=649AD2) |
| **Backend** | ![Django](https://img.shields.io/badge/Django-0d1117?style=flat-square&logo=django&logoColor=44B78B) ![Django REST Framework with SimpleJWT](https://img.shields.io/badge/DRF%20%2B%20SimpleJWT-0d1117?style=flat-square&logo=jsonwebtokens&logoColor=D63AFF) ![Flask](https://img.shields.io/badge/Flask-0d1117?style=flat-square&logo=flask&logoColor=ffffff) ![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-0d1117?style=flat-square&logo=sqlalchemy&logoColor=D71F00) |
| **Mobile** | ![Flutter](https://img.shields.io/badge/Flutter-0d1117?style=flat-square&logo=flutter&logoColor=47C5FB) ![Riverpod](https://img.shields.io/badge/Riverpod-0d1117?style=flat-square&logo=dart&logoColor=6F5CFF) ![Hive](https://img.shields.io/badge/Hive-0d1117?style=flat-square&logo=databricks&logoColor=FFB300) |
| **AI / ML** | ![TensorFlow](https://img.shields.io/badge/TensorFlow-0d1117?style=flat-square&logo=tensorflow&logoColor=FF6F00) ![Keras](https://img.shields.io/badge/Keras-0d1117?style=flat-square&logo=keras&logoColor=D00000) ![scikit-learn](https://img.shields.io/badge/scikit--learn-0d1117?style=flat-square&logo=scikitlearn&logoColor=F7931E) ![OpenCV](https://img.shields.io/badge/OpenCV-0d1117?style=flat-square&logo=opencv&logoColor=8B7BF7) ![pandas](https://img.shields.io/badge/pandas-0d1117?style=flat-square&logo=pandas&logoColor=ffffff) |
| **Data** | ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-0d1117?style=flat-square&logo=postgresql&logoColor=6C9BE8) ![SQLite](https://img.shields.io/badge/SQLite-0d1117?style=flat-square&logo=sqlite&logoColor=6AB7E8) ![Supabase](https://img.shields.io/badge/Supabase-0d1117?style=flat-square&logo=supabase&logoColor=3FCF8E) |
| **Shipping** | ![Render](https://img.shields.io/badge/Render-0d1117?style=flat-square&logo=render&logoColor=ffffff) ![Gunicorn](https://img.shields.io/badge/Gunicorn-0d1117?style=flat-square&logo=gunicorn&logoColor=499848) ![Cloudflare Tunnel](https://img.shields.io/badge/Cloudflare%20Tunnel-0d1117?style=flat-square&logo=cloudflare&logoColor=F38020) ![Git](https://img.shields.io/badge/Git-0d1117?style=flat-square&logo=git&logoColor=F05032) |

---

## Featured Projects

<table>
<tr>
<td width="50%" valign="top">

### [Marginalia](https://github.com/PRiNCeKUsHW/marginalia)

A publishing app in two halves: a Flutter client and a Django REST backend. Essays with
categories and full-text search, `@handles`, following and a Following feed, comments,
in-app notifications, and an author dashboard showing views, likes and comments with
week-over-week change.

**Tech** · Flutter · Riverpod · Hive · Django 6 · DRF · SimpleJWT · PostgreSQL (Supabase) · Render

**Why it's interesting** — one product, two codebases, shipped end to end: signup by
one-time code sent over an HTTP mail API because the host blocks SMTP, pooler-aware
database settings, and 144 tests between the API and the app.

[Live API docs](https://marginalia-hp35.onrender.com/api/docs/) · free tier, so give it a minute to wake

</td>
<td width="50%" valign="top">

### [HireHorizon](https://github.com/PRiNCeKUsHW/HireHorizon)

A text-first social publishing platform built as five Django apps — long-form posts,
feed, follow, like, comment with replies, repost, bookmark, `@mentions`, private
messaging, notifications, and a trending Explore page based on 7-day engagement.

**Tech** · Django 5 · PostgreSQL / SQLite · WhiteNoise · Gunicorn · Cloudflare Tunnel

**Why it's interesting** — it accepts no image uploads anywhere, on purpose, which
removes a whole class of moderation and security work; and it can self-host from an
Android phone under Termux, public over a Cloudflare quick tunnel.

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [Covid-19 Detection from X-Rays](https://github.com/PRiNCeKUsHW/covid19-detection-using-x-ray-image)

A convolutional network trained on chest X-ray images in a notebook, exported to
`covid.h5`, then put behind a Flask form: upload a scan with the patient's details, the
image is resized and normalised with OpenCV, and the prediction comes back on screen.

**Tech** · TensorFlow / Keras · OpenCV · Flask · WTForms

**Why it's interesting** — the model does not stop at the notebook; it ends up as
something a person can actually use.

</td>
<td width="50%" valign="top">

### [File Diff Engine](https://github.com/PRiNCeKUsHW/file-compare)

A Django tool for comparing two data files. Upload a baseline and a current JSON, YAML or
XML file and get every new, removed and modified entry as a filterable table plus a
downloadable CSV report.

**Tech** · Django · PyYAML · Gunicorn · WhiteNoise

**Why it's interesting** — parsers live in a registry, so supporting a new format is one
function and one dictionary entry, which is exactly how an internal tool should age.

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [Dog Image Classifier](https://github.com/PRiNCeKUsHW/Dog_and_classification)

An image classifier trained with Keras `ImageDataGenerator`, saved as
`classification.h5` and wrapped in a small Flask app that serves predictions from an
upload.

**Tech** · TensorFlow / Keras · Flask

**Why it's interesting** — the same train-then-serve loop repeated on a different
dataset, which is how the habit stuck.

</td>
<td width="50%" valign="top">

### [Flask Blog](https://github.com/PRiNCeKUsHW/Flask-blog)

A multi-user blog: registration and login with hashed passwords, rich-text post editing
through CKEditor, threaded comments, Gravatar avatars, SQLAlchemy models and a Procfile
for deployment.

**Tech** · Flask · SQLAlchemy · Flask-Login · Flask-WTF · CKEditor

**Why it's interesting** — this is the app HireHorizon grew out of; the Django rewrite
still ships an `import_legacy` command that carries this database across.

</td>
</tr>
</table>

Smaller experiments live alongside these: [classic ML notebooks](https://github.com/PRiNCeKUsHW/data-science-and-ml)
(gradient descent, linear and logistic regression), [spam mail detection](https://github.com/PRiNCeKUsHW/Spam-mail-prediction),
[sonar rock vs. mine](https://github.com/PRiNCeKUsHW/Rock-and-mine), [diabetes prediction with an SVM](https://github.com/PRiNCeKUsHW/Diabetics-svm-ML)
and a [Flipkart scraping notebook](https://github.com/PRiNCeKUsHW/flipkart-scrap).

---

## Developer Journey

<div align="center">
<img src="./assets/journey.svg" width="100%" alt="Timeline: 2022 first static sites and C++ exercises, 2023 machine learning notebooks with scikit-learn and pandas, 2024 Flask apps serving Keras models, 2026 Django platforms and a Flutter client">
</div>

Static pages and C++ assignments came first, then a year of notebooks, then Flask apps
that served the models those notebooks produced, and now Django platforms with a Flutter
front end. The early repositories are still here — the record is not tidied up.

---

## Activity

<div align="center">

<img width="62%" alt="Profile summary for PRiNCeKUsHW: commits, pull requests, issues and contributed repositories" src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=PRiNCeKUsHW&theme=github_dark">

<img width="31%" alt="Repositories per language for PRiNCeKUsHW" src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=PRiNCeKUsHW&theme=github_dark">
<img width="31%" alt="Most committed language for PRiNCeKUsHW" src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=PRiNCeKUsHW&theme=github_dark">

<img width="88%" alt="Contribution chart for PRiNCeKUsHW" src="https://ghchart.rshah.org/58a6ff/PRiNCeKUsHW">

</div>

---

## Currently Building

- **Marginalia** — this month's commits are on the author dashboard and view counting, merged through pull requests on the repo.
- **HireHorizon** — trimming the desktop interface down now that the Django rewrite has settled.
- **Dart and Flutter** — the newest language in this account, and where the next few builds are heading.

---

<div align="center">

## Have an interesting idea? Let's build it.

Backend, mobile client, or the deploy in between — I'm reachable here.

<a href="https://www.linkedin.com/in/anuj-kushwaha-76b659210/"><img alt="LinkedIn profile" src="https://img.shields.io/badge/LinkedIn-0d1117?style=for-the-badge&logo=linkedin&logoColor=4493f8"></a>
<a href="mailto:anuj.kush03@gmail.com"><img alt="Email anuj.kush03 at gmail.com" src="https://img.shields.io/badge/anuj.kush03%40gmail.com-0d1117?style=for-the-badge&logo=gmail&logoColor=ea4335"></a>
<a href="https://portfolio-site-bk5i.onrender.com/"><img alt="Portfolio site" src="https://img.shields.io/badge/Portfolio-0d1117?style=for-the-badge&logo=render&logoColor=ffffff"></a>
<a href="https://github.com/PRiNCeKUsHW?tab=repositories"><img alt="All repositories" src="https://img.shields.io/badge/All%20repos-0d1117?style=for-the-badge&logo=github&logoColor=ffffff"></a>

<sub>Every project above is public — clone it and run it; the commands are in each README.</sub>

</div>
