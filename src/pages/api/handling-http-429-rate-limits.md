---
id: KB-API-004
title: "Handling HTTP 429 rate limits"
category: Api
product: Matcha.io
tags: ["429", "throttling", "retry"]
status: published
last_updated: 2026-10-15
---

# Handling HTTP 429 rate limits

## Overview

A `429 Too Many Requests` response means a request exceeded an enforced limit. Read the `Retry-After` header when present and wait that many seconds before retrying.

## Recommended steps

Use exponential backoff with jitter, cap retries, and queue non-urgent requests. Avoid parallel retry storms. Log response headers and request IDs for investigation.

## Additional guidance

Do not retry indefinitely. If throttling continues at normal usage, compare traffic with the published limits and contact support.

## Contact support

If you still need help, provide the article ID **KB-API-004**, a description of the problem, relevant UTC timestamps, and sanitized request or execution IDs. Never share passwords, access tokens, or payment-card details.
