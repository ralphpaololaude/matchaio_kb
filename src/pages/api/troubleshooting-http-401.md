---
id: KB-API-002
title: "Troubleshooting HTTP 401"
category: Api
product: Matcha.io
tags: ["401", "unauthorized", "authentication"]
status: published
last_updated: 2026-10-15
---

# Troubleshooting HTTP 401

## Overview

A `401 Unauthorized` response means Matcha.io could not authenticate the request. Confirm the `Authorization: Bearer YOUR_API_KEY` header is present, the key is active, and no extra spaces or quotes were copied.

## Recommended steps

Test with a newly created key using the same endpoint. Check whether the application is using an old environment variable or a revoked credential.

## Additional guidance

If the issue persists, provide support with the request timestamp, endpoint, and request ID. Never send the API key itself.

## Contact support

If you still need help, provide the article ID **KB-API-002**, a description of the problem, relevant UTC timestamps, and sanitized request or execution IDs. Never share passwords, access tokens, or payment-card details.
