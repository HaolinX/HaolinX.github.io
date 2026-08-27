---
layout: page
title: CLI Password Manager
description: A secure command-line credential manager with role-based access control and an AES-256 encrypted vault.
img: assets/img/proj_password_manager.png
importance: 2
category: work
related_publications: false
---

**Tech:** Node.js · MySQL · bcrypt · AES-256-CBC · Inquirer.js
&nbsp;•&nbsp; **Timeline:** Jul 2025 – Aug 2025

## Overview

A secure command-line tool for storing and managing credentials. Every stored password is encrypted at rest, access is gated by role, and the whole thing runs as a friendly interactive prompt in the terminal.

## What it does

- **Role-based access control** with distinct admin and guest roles, so read and write permissions are separated.
- **Encryption at rest:** all stored passwords are encrypted with AES-256-CBC, with keys managed via environment variables rather than hard-coded in the source.
- **bcrypt-hashed admin authentication**, so the master credential is never stored in plaintext.
- **An interactive CLI** built with [Inquirer.js](https://github.com/SBoudrias/Inquirer.js) supporting full CRUD operations over a MySQL-backed credential vault.
- **Clean, modular architecture** with `.env` configuration and disciplined Git practices.

## Why I built it

I wanted a hands-on way to work through the practical side of applied cryptography and access control — key management, choosing an encryption mode, hashing secrets correctly, and keeping configuration out of source control — in a small tool I would actually use.

<div class="row justify-content-sm-center">
    <div class="col-sm-10 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/proj_password_manager.png" title="CLI Password Manager" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

> Want the code? Add a link to the GitHub repository here once it's public.
