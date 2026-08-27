---
layout: page
title: RAG Chatbot
description: A full-stack Retrieval-Augmented Generation web app that answers questions over your uploaded PDFs.
img: assets/img/proj_rag_chatbot.png
importance: 1
category: work
related_publications: false
---

**Tech:** Node.js · MySQL · OpenAI API · Transformers.js · JWT · HTML/CSS/JS
&nbsp;•&nbsp; **Timeline:** Feb 2025 – Jun 2025

## Overview

RAG Chatbot is a full-stack [Retrieval-Augmented Generation](https://en.wikipedia.org/wiki/Retrieval-augmented_generation) web application. You upload PDFs, and the app answers questions about them by retrieving the most relevant passages and feeding them to a language model — so answers stay grounded in your own documents instead of the model's general knowledge.

## What it does

- **Answers questions over uploaded PDFs** using the OpenAI API for response generation and [Transformers.js](https://huggingface.co/docs/transformers.js) for local document embedding and semantic search, so documents are embedded on the server without sending raw text to a third-party embedding service.
- **Secure authentication** with JWT tokens and bcrypt-hashed passwords stored in MySQL, with connection pooling and SQL-injection protection on every query.
- **A full retrieval backend** with routes for file uploads and PDF text extraction, plus persistent vector stores so embedded chunks can be retrieved across sessions.

## How it works

When a PDF is uploaded, the backend extracts its text, splits it into chunks, and embeds each chunk into a vector. At query time, the user's question is embedded the same way, the closest chunks are retrieved by semantic similarity, and those passages are passed to the OpenAI API as context to generate a grounded answer.

<div class="row justify-content-sm-center">
    <div class="col-sm-10 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/proj_rag_chatbot.png" title="RAG Chatbot" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

> Want the code? Add a link to the GitHub repository here once it's public.
