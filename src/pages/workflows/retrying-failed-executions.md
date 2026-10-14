---
id: KB-WF-002
title: "Retrying failed executions"
category: Workflows
product: Matcha.io
tags: ["retry", "failed-run", "recovery"]
status: published
last_updated: 2026-10-15
---

# Retrying failed executions

## Overview

Open **Workflows → Executions**, select a failed execution, and choose **Retry** if the action is available.

## Recommended steps

Check whether the workflow performs non-idempotent actions such as charging a card or creating a record. Verify that retrying will not duplicate side effects.

## Additional guidance

If the retry action is unavailable, fix the workflow and start a new run using validated input. Record the original execution ID for troubleshooting.

## Contact support

If you still need help, provide the article ID **KB-WF-002**, a description of the problem, relevant UTC timestamps, and sanitized request or execution IDs. Never share passwords, access tokens, or payment-card details.
