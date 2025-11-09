# BSides 2025

Talk "_app.alert(1) is the new alert(1): PDF files as a vector to inject JavaScript code in web applications_", presented at [**BSides Sofia 2025**](https://securitybsides.bg/) (March 29th, 2025) and [**BSides Krakow 2025**](https://bsideskrakow.pl/) (September 27th, 2025).

### app.alert(1) is the new alert(1): PDF files as a vector to inject JavaScript code in web applications

**Talk:** [BSides Sofia: app.alert(1) is the new alert(1)](https://www.youtube.com/watch?v=86RC5Sha9gU)

**Slides:** [app.alert(1) is the new alert(1): PDF files as a vector to inject JavaScript code in web applications](https://pitch.com/v/appalert1-is-the-new-alert1-krakow-wrwskm)

**Abstract:** PDFs - rise, decline, and revival: a journey across how we have changed our way of viewing and editing PDF files by moving from offline clients to online services, and how this is changing the role of PDF files as attack vectors. Let's explore four CVEs that affected two of the most significant PDF rendering JavaScript libraries in 2024.

**Description:** A talk on how we have moved from local clients (Adobe, etc) to browsers and online services to render, view, edit, and sign PDF files, and how this has changed the role of PDFs in attacks and exploitations. From the false-positive vulnerabilities (CVE-2020-26505, CVE-2023-0108, CVE-2023-5873, and other CVEs that were not vulnerabilities) to vulnerabilities in client-side PDF SDKs. During the talk, we will investigate some cross-site-scripting vulnerabilities exploited in the real world (e.g. bug bounty programs), focusing in particular on PDF.js (CVE-2018-5158, and CVE-2024-4367) and Apryse Webviewer (CVE-2024-4327, and CVE-2024-29359), and how a PDF file can lead to a Remote Code Execution in an open-source project with more than 38k stars. The talk will show how a PDF file can exploit web applications if they don't properly mitigate risks (using Content-Security-Policy, and keeping the dependencies updated).


