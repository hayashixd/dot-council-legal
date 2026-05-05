---
layout: default
title: Privacy Policy
permalink: /privacy/
---

# Privacy Policy

**Effective Date:** 2026-05-05

This Privacy Policy describes how the dot-council application ("Service") handles information when used by its developer ("we", "us"). The Service is a single-user automation tool operated by Kohei Hayashi.

## 1. Information We Collect

When the developer authenticates the Service with TikTok via OAuth (Login Kit), the Service receives the following information from TikTok:

- **TikTok Open ID and Union ID** — unique identifiers for the authenticated TikTok account, used to associate uploaded content with the correct account.
- **Basic profile information** (`user.info.basic` scope) — display name and avatar URL, used solely to confirm that the authenticated account is the intended target.
- **Access and refresh tokens** — short-lived credentials issued by TikTok that allow the Service to publish content to the authenticated account on behalf of the developer (`video.publish` scope).

The Service does not collect any information from end users of TikTok or any other third party. The Service does not collect, store, or process any data from individuals other than the authenticated developer-owner of the connected account.

## 2. How We Use Information

Information received from TikTok is used exclusively to:

- Publish AI-generated pixel-art videos to the authenticated TikTok account.
- Refresh expired access tokens automatically to maintain unattended operation.
- Verify that the authenticated account matches the intended target before posting.

We do not sell, rent, share, or transfer any information to third parties for any purpose.

## 3. Storage and Security

- Access and refresh tokens are stored locally on the developer's machine in a file outside of any version control system, and are not transmitted to any server other than TikTok's official API endpoints (`open.tiktokapis.com`).
- The Service runs locally and does not maintain a hosted backend that stores user data.

## 4. Data Retention

- Refresh tokens are retained until they expire (365 days from issuance) or until the developer revokes the Service's authorization via TikTok account settings.
- The developer may delete stored tokens at any time, which immediately stops all automated posting and removes all stored credentials.

## 5. Third-Party Services

The Service interacts only with TikTok's official APIs at `open.tiktokapis.com`. Use of TikTok is governed by TikTok's own [Privacy Policy](https://www.tiktok.com/legal/privacy-policy) and [Terms of Service](https://www.tiktok.com/legal/page/row/terms-of-service/en).

## 6. Children's Privacy

The Service is not directed at children under 13 years of age. No information from children is knowingly collected.

## 7. Your Rights

The developer (as the sole user of the Service) may at any time:

- Revoke the Service's access to the authenticated TikTok account via TikTok's account settings page. Revocation immediately invalidates stored tokens.
- Delete all locally stored tokens, which immediately stops the Service from posting to TikTok.

## 8. Changes to This Policy

This Privacy Policy may be updated to reflect changes in the Service or applicable law. The current version is always available at this page. Material changes will be reflected in the Effective Date at the top of this document.

## 9. Contact

For questions about this Privacy Policy or to exercise your rights, contact: <xdhyskh.ppp@gmail.com>
