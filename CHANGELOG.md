# Sovereign City v1.0.2 — Kit Signup Form Connection

## What this release does
Connects the existing Sovereign City Dispatch signup form to the live Cloudflare Worker:

https://sovereigncity-api.sovereigncitydispatch.workers.dev/

## Files changed
- builders.html

## What changed
- Adds a form ID for the Dispatch signup form.
- Adds a user-facing success/error message area.
- Sends the email address to the Cloudflare Worker using a secure POST request.
- Displays: "Welcome, Sovereign Builder. You're now on the list." after a successful signup.
- Keeps the existing design and page layout intact.

## Files NOT changed
- index.html
- manifesto.html
- vault.html
- assets

## Install
Upload `builders.html` to the root of the GitHub repository and replace the existing file.
Commit changes, wait for GitHub Pages to deploy, then test the form on the live site.

- Replaced Phones Collection with v4 minimal decision-first flow.

## 2026-07-24 — Phones Sprint 2
- Replaced generic phone illustrations with original Sovereign City product-style renders.
- Shortened card copy and changed CTAs to “See Why We Recommend It”.
- Renamed “Best Premium” to “Premium Choice”.
- Added a universal recommendation-standards panel beneath all three phones.
- Refined badges, hover motion and visual hierarchy across desktop and mobile.
