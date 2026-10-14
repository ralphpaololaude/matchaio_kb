---
id: KB-WH-001
title: "Configuring a webhook"
category: Webhooks
product: Matcha.io
tags: ["webhook", "events", "signing"]
status: published
last_updated: 2026-10-15
---

# Configuring a webhook

## Overview

Navigate to **Settings → Developer → Webhooks → Add endpoint**. Enter an HTTPS destination URL and select the event types to receive.

## Recommended steps

Save the endpoint, copy its signing secret into your secret manager, and verify incoming signatures. Use **Send test event** to validate connectivity.

## Additional guidance

The receiving service should return a `2xx` status promptly. Process long-running tasks asynchronously and handle duplicate deliveries.

## Contact support

If you still need help, provide the article ID **KB-WH-001**, a description of the problem, relevant UTC timestamps, and sanitized request or execution IDs. Never share passwords, access tokens, or payment-card details.
