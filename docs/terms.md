---
layout: default
title: Terms of Service
description: Terms of Service for AllSky Youtube Uploader.
permalink: /terms
---

## Terms of Service

<div class="effective-date">Effective: March 28, 2026</div>

These Terms of Service ("Terms") govern your use of the AllSky Youtube Uploader software
("the Application", "the Software") and its integration with the YouTube Data API
and other third-party services. By using the Application, you agree to these Terms.

### 1. Acceptance of Terms

By installing, configuring, or using AllSky Youtube Uploader, you agree to be bound by these Terms.
If you do not agree, you should not use the Software.

### 2. Description of Service

AllSky Youtube Uploader is open-source software that runs on a Raspberry Pi to capture sky images
using a fisheye camera. The software provides:

- Continuous day and night sky image capture with automatic exposure control
- Daily timelapse video generation from captured frames
- Keogram and startrail composite generation
- Star identification via astrometric plate solving
- Aircraft and satellite identification using ADS-B data and TLE orbital elements
- Automated upload of timelapse videos to YouTube via the YouTube Data API v3
- A local web interface for configuration, live view, and image history

### 3. License

AllSky Youtube Uploader is distributed under an open-source license. Your use of the source code
is governed by the license included in the
[project repository]({{ site.github_repo }}){:target="_blank" rel="noopener"}.
These Terms apply to the use of the Application's services and integrations, supplementing
(not replacing) the source code license.

### 4. User Responsibilities

**Hardware and Installation**

- You are responsible for the hardware, network, and physical security of your AllSky
  Camera installation, including the Raspberry Pi, camera, enclosure, and any ADS-B receiver.
- You must ensure your outdoor camera installation complies with all applicable local laws,
  including building codes, HOA rules, and any regulations regarding outdoor cameras
  or radio receivers.

**Content**

- You are responsible for all content captured, generated, and uploaded by the Application,
  including timelapse videos, keograms, and startrails.
- While AllSky Youtube Uploader is designed to capture the sky and not people or private property,
  you are responsible for ensuring your installation does not violate others' privacy.
- You must not use the Application to upload content that violates YouTube's
  [Community Guidelines](https://www.youtube.com/howyoutubeworks/policies/community-guidelines/){:target="_blank" rel="noopener"}
  or any other applicable platform terms.

**Google API Usage**

- When using the YouTube upload integration, you must comply with
  [Google's Terms of Service](https://policies.google.com/terms){:target="_blank" rel="noopener"}
  and the
  [YouTube Terms of Service](https://www.youtube.com/t/terms){:target="_blank" rel="noopener"}.
- You must not attempt to circumvent YouTube API quotas, rate limits, or access controls.
- You are responsible for maintaining the security of your Google OAuth credentials stored
  on your Raspberry Pi.

### 5. YouTube API Services

The Application's YouTube upload feature uses the YouTube Data API v3. By using this feature:

- You authorize the Application to upload videos to your YouTube channel on your behalf.
- You agree to the [YouTube Terms of Service](https://www.youtube.com/t/terms){:target="_blank" rel="noopener"}.
- You acknowledge that uploaded videos are subject to YouTube's content policies and may
  be removed by YouTube if they violate those policies.
- You can revoke the Application's access to your YouTube account at any time via
  [Google Account permissions](https://myaccount.google.com/permissions){:target="_blank" rel="noopener"}.

### 6. ADS-B and Satellite Data

The Application may use publicly broadcast ADS-B (Automatic Dependent Surveillance-Broadcast)
transponder signals and publicly available TLE (Two-Line Element) satellite orbital data to
identify aircraft and satellites in sky images. This data is received and used locally on
your device. You are responsible for complying with any local regulations regarding the
reception and use of ADS-B signals in your jurisdiction.

### 7. Disclaimer of Warranties

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED,
INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A
PARTICULAR PURPOSE, AND NON-INFRINGEMENT. THE ENTIRE RISK AS TO THE QUALITY AND
PERFORMANCE OF THE SOFTWARE IS WITH YOU.

Without limiting the above, we do not warrant that: (a) object identification (stars,
aircraft, satellites) will be accurate or complete; (b) timelapse generation or YouTube
uploads will operate without interruption; or (c) the Software will be compatible with
all hardware configurations.

### 8. Limitation of Liability

IN NO EVENT SHALL THE AUTHORS, CONTRIBUTORS, OR COPYRIGHT HOLDERS BE LIABLE FOR ANY
CLAIM, DAMAGES, OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT, OR
OTHERWISE, ARISING FROM, OUT OF, OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR
OTHER DEALINGS IN THE SOFTWARE. THIS INCLUDES, WITHOUT LIMITATION, ANY DIRECT,
INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES, INCLUDING BUT
NOT LIMITED TO DAMAGES ARISING FROM FAILED UPLOADS, INCORRECT OBJECT IDENTIFICATION,
OR HARDWARE DAMAGE.

### 9. Data and Privacy

Your use of the Application is subject to our [Privacy Policy]({{ '/privacy' | relative_url }}),
which describes how the Application handles your data and interacts with Google APIs.
By using the Application, you acknowledge that you have read and understood the Privacy Policy.

### 10. Modifications to the Service

As open-source software, AllSky Youtube Uploader may be updated, modified, or discontinued at any
time by the community. We are not obligated to maintain, support, or update the Software.
Google may also change or discontinue the YouTube Data API, which could affect the upload
functionality.

### 11. Changes to These Terms

We may revise these Terms from time to time. Changes will be posted on this page with
an updated effective date. Your continued use of the Application after changes constitutes
acceptance of the revised Terms.

### 12. Governing Law

These Terms shall be governed by and construed in accordance with the laws of the
jurisdiction in which you reside, without regard to conflict of law principles.

### 13. Contact

Questions about these Terms can be directed to the project maintainers through the
[AllSky Youtube Uploader GitHub repository]({{ site.github_repo }}){:target="_blank" rel="noopener"}
or the community forums.
