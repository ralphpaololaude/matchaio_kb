---
id: KB-API-003
title: "Troubleshooting HTTP 403"
category: Api
product: Matcha.io
tags: ["403", "forbidden", "permissions"]
status: published
last_updated: 2026-10-15
---

# Troubleshooting HTTP 403

## Overview

A `403 Forbidden` response means the request was authenticated but is not authorized. Check the API key scopes and the requesting user’s workspace role.

## Recommended steps

Verify the resource belongs to the correct workspace. Ask an administrator to grant the required permission or create a key with an approved scope.

## Additional guidance

Do not repeatedly regenerate keys without verifying the permissions. Include the request ID and resource type when contacting support.

## Contact support

If you still need help, provide the article ID **KB-API-003**, a description of the problem, relevant UTC timestamps, and sanitized request or execution IDs. Never share passwords, access tokens, or payment-card details.
