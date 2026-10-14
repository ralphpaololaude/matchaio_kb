---
id: KB-API-005
title: "API rate limits"
category: Api
product: Matcha IO API
tags: ["limits", "quotas", "api"]
status: published
last_updated: 2026-10-15
---

# API rate limits

## Overview

For this fictional FlowDesk environment, the standard API allowance is **120 requests per minute per workspace**. A short burst can still trigger throttling.

## Recommended steps

Inspect the `X-RateLimit-Limit`, `X-RateLimit-Remaining`, and `X-RateLimit-Reset` response headers where available. Implement client-side pacing and caching.

## Additional guidance

Limits may differ by plan or endpoint. The workspace administrator can review its effective allowance under **Settings → Usage → API**.

## Contact support

If you still need help, provide the article ID **KB-API-005**, a description of the problem, relevant UTC timestamps, and sanitized request or execution IDs. Never share passwords, access tokens, or payment-card details.
