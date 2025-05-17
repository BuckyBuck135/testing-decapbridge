---
title: Writen in deployed Decap dashboard
description: Writen in deployed Decap dashboard
author: Geoffrey
date: 2025-05-17T15:08:00.000Z
image: src/assets/images/blog/blog-cover.jpg
imageAlt: Writen in deployed Decap dashboard
tags:
  - post
---
\# Use DecapBridge auth (required)

backend:

  name: git-gateway

  repo: BuckyBuck135/testing-decapbridge

  branch: main

  identity_url: https://auth.decapbridge.com/sites/5605bbe7-08f2-4ce5-bce2-7d97def08bed

  gateway_url: https://gateway.decapbridge.com



\# Quickly see who did what (optional)

  commit_messages:

\    create: Create {{collection}} “{{slug}}” - {{author-name}} <{{author-login}}> via DecapBridge

\    update: Update {{collection}} “{{slug}}” - {{author-name}} <{{author-login}}> via DecapBridge

\    delete: Delete {{collection}} “{{slug}}” - {{author-name}} <{{author-login}}> via DecapBridge

\    uploadMedia: Upload “{{path}}” - {{author-name}} <{{author-login}}> via DecapBridge

\    deleteMedia: Delete “{{path}}” - {{author-name}} <{{author-login}}> via DecapBridge

\    openAuthoring: Message {{message}} - {{author-name}} <{{author-login}}> via DecapBridge



\# Better Decap + Bridge logo (optional)

logo_url: https://decapbridge.com/decapcms-with-bridge.svg



\# Add site links in DecapCMS (optional)

site_url: https://testing-decapbridge.netlify.app
