---
layout: default
title: Privacy Policy
description: Privacy Policy for AllSky Youtube Uploader use of the YouTube Data API and Google user data.
permalink: /privacy
---

## Privacy Policy

<div class="effective-date">Effective: March 28, 2026</div>

This Privacy Policy describes how AllSky Youtube Uploader ("the Application", "we", "our") handles
information when you use the software and its integration with the YouTube Data API and
other Google services.

### 1. What the Application Does

AllSky Youtube Uploader is open-source software that runs locally on a Raspberry Pi. It captures
sky images, generates daily timelapse videos, and can upload those videos to your
YouTube channel using the **YouTube Data API v3**.

### 2. Information We Collect

AllSky Youtube Uploader runs entirely on your local device. We do not operate any external servers
that collect or store your data.

When you enable the YouTube upload feature, the Application accesses:

- **Google Account Identity** -- your name and email address, used to authenticate
  and display which account is connected in the local web interface.
- **OAuth 2.0 Tokens** -- an access token and refresh token, stored locally on
  your Raspberry Pi's filesystem to maintain your authenticated session.

The Application uses the following Google API scope:

- `youtube.upload` -- allows uploading videos to your YouTube channel. This scope
  does *not* grant access to read, modify, or delete existing videos or any other
  YouTube data.

### 3. How We Use Your Information

Information obtained through the YouTube Data API is used exclusively to:

- Authenticate your Google account for video uploads.
- Upload timelapse videos that the Application generates from your sky captures.
- Set video metadata (title, description, privacy status) based on your configured templates.
- Display your connected account name in the local AllSky web interface.

We do not use your data for advertising, analytics, profiling, training machine learning
models, or any purpose unrelated to uploading your timelapse videos.

### 4. Data Storage and Security

- All OAuth credentials and tokens are stored as files on your Raspberry Pi's local filesystem.
- No personal data or tokens are transmitted to any server operated by AllSky Youtube Uploader developers.
- All communication with Google APIs uses HTTPS (TLS) encryption.
- Uploaded videos are stored on YouTube's servers under your Google account, subject to
  [Google's Privacy Policy](https://policies.google.com/privacy){:target="_blank" rel="noopener"}.
- You are responsible for securing physical and network access to your Raspberry Pi.

### 5. Data Sharing

We do not sell, rent, lease, or share your personal information with any third party.
The only third-party service that receives data from the Application is YouTube/Google,
and only when you explicitly configure and authorize the upload feature.

Video content you upload becomes subject to
[YouTube's Terms of Service](https://www.youtube.com/t/terms){:target="_blank" rel="noopener"}
and may be visible to others depending on the privacy setting you choose (public, unlisted,
or private).

### 6. Google API Services User Data Policy

AllSky Youtube Uploader's use and transfer of information received from Google APIs adheres to the
[Google API Services User Data Policy](https://developers.google.com/terms/api-services-user-data-policy){:target="_blank" rel="noopener"},
including the **Limited Use** requirements:

- The Application only requests the `youtube.upload` scope -- the minimum necessary
  for its upload functionality.
- Access to Google user data is limited to the practices explicitly disclosed in this
  Privacy Policy.
- Google user data is not transferred to any third party, except as necessary to upload
  videos to YouTube at your direction.
- Google user data is not used for serving advertisements.
- No human reads your Google user data unless (a) you provide affirmative consent,
  (b) it is necessary for security purposes (e.g., investigating abuse), or (c) it is
  required by applicable law.

### 7. YouTube API Services

By using the YouTube upload feature, you also agree to be bound by the
[YouTube Terms of Service](https://www.youtube.com/t/terms){:target="_blank" rel="noopener"}.
You can learn more about Google's privacy practices at the
[Google Privacy Policy](https://policies.google.com/privacy){:target="_blank" rel="noopener"} page.

### 8. Sky Image Content

AllSky Youtube Uploader captures images of the sky from a fixed outdoor location. These images may
incidentally contain:

- Aircraft (identified by ADS-B transponder data, which is publicly broadcast)
- Satellites and space objects (tracked using public TLE orbital data)
- Landscape features at the horizon (trees, buildings, terrain)

The camera is pointed upward and is not designed to capture identifiable images of people
or private property. All captured images and generated videos are stored locally on your
Raspberry Pi until you choose to upload them.

### 9. Your Choices and Rights

- **Revoke access** -- Disconnect the YouTube integration at any time through the
  AllSky web interface, or revoke access in your
  [Google Account permissions](https://myaccount.google.com/permissions){:target="_blank" rel="noopener"}.
- **Delete local data** -- OAuth tokens are stored as files on your Pi and can be
  deleted at any time.
- **Manage uploads** -- Videos uploaded to YouTube are under your full control through
  [YouTube Studio](https://studio.youtube.com){:target="_blank" rel="noopener"}. You can edit,
  unpublish, or delete them at any time.
- **Disable uploads** -- The YouTube upload feature is optional and can be disabled
  in the AllSky settings without affecting any other functionality.

### 10. Children's Privacy

AllSky Youtube Uploader is not directed at children under the age of 13. We do not knowingly collect
personal information from children.

### 11. Changes to This Policy

We may update this Privacy Policy from time to time. Changes will be posted on this page
with an updated effective date. Continued use of the Application after changes constitutes
acceptance of the revised policy.

### 12. Contact

If you have questions about this Privacy Policy, please open an issue on the
[AllSky Youtube Uploader GitHub repository]({{ site.github_repo }}){:target="_blank" rel="noopener"}
or contact the project maintainers through the community forums.
