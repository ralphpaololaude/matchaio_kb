---
id: KB-WH-002
title: "Troubleshooting webhook delivery"
category: Webhooks
product: Matcha.io
tags: ["webhook", "delivery", "timeout"]
status: published
last_updated: 2026-10-15
---

# Troubleshooting webhook delivery

## Overview

Open **Settings → Developer → Webhooks**, choose the endpoint, and review its delivery history. Check the HTTP status, latency, and event ID.

## Recommended steps

Verify the endpoint is publicly reachable over HTTPS, responds with `2xx`, accepts the payload size, and validates signatures against the current secret.

## Additional guidance

A timeout or non-2xx response indicates unsuccessful delivery. Fix the receiver, then redeliver from the delivery history when available. Deduplicate by event ID.

## Contact support

If you still need help, provide the article ID **KB-WH-002**, a description of the problem, relevant UTC timestamps, and sanitized request or execution IDs. Never share passwords, access tokens, or payment-card details.
