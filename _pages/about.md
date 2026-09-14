---
layout: about
title: about
permalink: /
subtitle: Computer Science undergrad at <a href='https://ucsd.edu/'>UC San Diego</a> · into full-stack, security &amp; AI

profile:
  align: right
  image: prof_pic.png
  image_circular: false # crops the image to make it circular
  more_info: >

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

Hi, I'm **Haolin**, you can also call me **Jayden**. I'm a Computer Science undergrad at [UC San Diego](https://ucsd.edu/)

Right now I'm a **Full-Stack (Cyber Security) Engineer at VisionX**, working on the backend of a health app that handles sensitive data. I find and fix security holes, tighten up the testing pipeline, and build tools that watch for suspicious activity.

I'm most excited by the mix of **full-stack development, security, and AI**. A few things I've built: a chatbot that answers questions about your PDFs, a command-line password manager with encryption, and an AI video-editing app that earned a published paper.

I love building things that are both helpful and secure. Feel free to look through my [CV]({{ '/cv/' | relative_url }}), or just say hi over my email[jax008@ucsd.edu](mailto:Jax008@ucsd.edu)!

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