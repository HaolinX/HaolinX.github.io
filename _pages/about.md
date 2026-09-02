---
layout: about
title: about
permalink: /
subtitle: Computer Science @ <a href='https://ucsd.edu/'>UC San Diego</a> · Full-Stack &amp; Security Engineer

profile:
  align: right
  image: prof_pic.png
  image_circular: false # crops the image to make it circular
  more_info: >
    <p>La Jolla, California</p>
    <p><a href="mailto:Jax008@ucsd.edu">Jax008@ucsd.edu</a></p>

selected_papers: true # includes a list of papers marked as "selected={true}"
social: false # includes social icons at the bottom of the page

announcements:
  enabled: true # includes a list of news items
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit: 5 # leave blank to include all the news in the `_news` folder

latest_posts:
  enabled: false
  scrollable: true # adds a vertical scroll bar if there are more than 3 new posts items
  limit: 3 # leave blank to include all the blog posts
---

Hi, I'm **Haolin** — I also go by **Jayden**. I'm a Computer Science student at the [University of California, San Diego](https://ucsd.edu/), and I care about building software that is both genuinely useful and secure by design.

Right now I'm a **Full-Stack (Cyber Security) Engineer at VisionX**, where I harden the backend of a health application that handles sensitive data — remediating dependency vulnerabilities, restoring CI security gates in the pull-request workflow, and designing an extensible application-layer security monitoring framework from the ground up.

My interests sit at the intersection of **full-stack development, application security, and applied AI**. I've built a Retrieval-Augmented Generation chatbot that answers questions over uploaded PDFs, a CLI password manager with role-based access control and AES-256 encryption, and an AI-powered video editing app that earned a [U.S. patent](/cv/) and a published conference paper.

Before UC San Diego I studied at San Francisco State University (GPA 3.96/4.00), where I also worked as a Learning Assistant guiding 200+ students through intermediate programming.

Have a look through my [projects]({{ '/projects/' | relative_url }}) and [CV]({{ '/cv/' | relative_url }}), or feel free to reach out by [email](mailto:Jax008@ucsd.edu).


## experience

**Full-Stack (Cyber Security) Engineer — VisionX** · Jun 2026 – Present<br>
Hardening the backend of a health application that handles sensitive data: I remediated 26 dependency vulnerabilities, restored CI security gates across the pull-request workflow, and designed an extensible application-layer security monitoring framework from scratch (pluggable detectors, PHI-safe logging, fail-open execution), growing the test suite from 211 to 290 tests.

**Learning Assistant, CSC 215 — San Francisco State University** · Aug 2024 – Jun 2025<br>
Guided 200+ students through intermediate Java — control flow, data structures, and object-oriented design — and debugged their code one-on-one.

**Research Assistant, SoftCom Lab — Cal Poly Pomona** · Sep 2021 – Jun 2022<br>
Built AI/ML models for mobile video content extraction and deployed them to the cloud for real-time inference.

## projects

**RAG Chatbot** · *Node.js, OpenAI API, Transformers.js, JWT*<br>
A full-stack Retrieval-Augmented Generation web app that answers questions over your uploaded PDFs, using local document embeddings and semantic search, secured with JWT and bcrypt.

**CLI Password Manager** · *Node.js, MySQL, bcrypt, AES-256-CBC*<br>
A secure command-line credential vault with admin/guest role-based access control, AES-256-CBC encryption, and bcrypt-hashed authentication.

**Rz VideoCut** · *Dart, MediaPipe, Python*<br>
An AI-powered cross-platform video editor that automates face-tracking and cropping with MediaPipe (multi-face support). Launched on the App Store and Google Play — and the framework earned a U.S. patent and a published paper.