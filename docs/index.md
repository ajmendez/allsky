---
layout: default
title: AllSky Youtube Uploader
description: AllSky Youtube Uploader — publish to YouTube.
---

# AllSky YouTube -- Timelapse Uploader

Provides the required homepage, privacy policy, and terms of service for Google OAuth consent screen.


## Deploy

1. Create a GitHub repository (e.g., `allsky`)
2. Push this code to the `main` branch
3. Enable GitHub Pages (Settings > Pages > Source: `main` branch, root `/`)
4. Set `url` and `baseurl` in `_config.yml` to match your GitHub Pages URL

GitHub Pages builds Jekyll automatically -- no local build step needed.

## Google OAuth Setup

1. Deploy this site to GitHub Pages
2. In Google Cloud Console, go to **APIs & Services > OAuth consent screen**
3. Set **Application home page** to the deployed site URL
4. Set **Privacy policy link** to `/privacy`
5. Set **Terms of service link** to `/terms`
6. Add the GitHub Pages domain as an **Authorized domain**
