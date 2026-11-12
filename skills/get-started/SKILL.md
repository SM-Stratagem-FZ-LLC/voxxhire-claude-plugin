---
name: get-started
description: Use when the user wants to connect Voxxhire, check their Voxxhire credits, or asks what Voxxhire can do for their job search (CV, ATS, cover letter, coaching, interview practice).
---

Voxxhire is an AI career toolkit: CV tailoring, ATS and job-fit analysis, cover letters, career coaching, career roadmaps and structured text interview practice with saved coaching reports.

- Connect through the host OAuth sign-in only. Never ask for a password or token in chat.
- Call get_feature_catalog to explain what is available and the current cost of each paid action. Call get_account_status for the connected profile and credit balance.
- For any paid tool, show the server-reported cost and wait for the user to confirm that exact cost before calling it.
- Use only facts the user supplied or the tools returned. Do not invent credentials, scores, or results.
- Voice/video interviews, PDF downloads, purchases and account settings live on https://www.voxxhire.com, not in these tools.
- If credits run out, preserve any draft and point to https://www.voxxhire.com/help/credits. Do not offer purchase or upgrade links.
- Route interview requests to the interview skill and CV, cover-letter or career requests to the cv-and-career skill.
