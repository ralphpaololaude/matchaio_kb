---
id: KB-API-001
title: "Creating an API key"
category: Api
product: Matcha.io
tags: ["authentication", "api-key", "credentials"]
status: published
last_updated: 2026-10-15
---

# Creating an API key

## Overview

Open **Settings → Developer → API Keys**, select **Create key**, enter a descriptive name, choose the minimum required scopes, and select **Create**. Copy the key immediately; Matcha.io displays its secret only once.

## Recommended steps

Store the key in a secret manager. Send it in requests as `Authorization: Bearer YOUR_API_KEY`. Never commit keys to source control. Revoke compromised keys in **Settings → Developer → API Keys**.

## Additional guidance

A key cannot be recovered after creation. Create a replacement and rotate applications before revoking the old key.

## Contact support

If you still need help, provide the article ID **KB-API-001**, a description of the problem, relevant UTC timestamps, and sanitized request or execution IDs. Never share passwords, access tokens, or payment-card details.
