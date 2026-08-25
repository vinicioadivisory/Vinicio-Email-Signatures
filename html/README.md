# HTML Email Signatures

This folder contains the production HTML files used for Vinicio Adivisory CEO email signatures.

Each HTML file combines the hosted signature image assets from the `/images` folder with clickable contact and social media links.

## Current CEO Signature Files

### UAE / FZE Version

`ceo-email-signature-vinicio-adivisory-fze.html`

Official CEO email signature for **Vinicio Adivisory FZE**, representing the UAE branch.

This version uses the approved Arabic/FZE company branding.

### India / Trademark Version

`ceo-email-signature-vinicio-adivisory-india.html`

Official CEO email signature for the India branch of **Vinicio Adivisory**.

This version uses the approved Vinicio Adivisory trademark logo.

## How These Files Work

The HTML files reference production image assets stored in the repository's `/images` folder.

The signature layout includes:

* CEO signature design
* Company branding
* QR code
* CEO LinkedIn
* Company LinkedIn
* Instagram
* Facebook
* Book a Meeting link

The HTML uses a compact table-based layout designed for compatibility with Gmail and common email clients.

## Important

Do not rename, move, or delete files in the `/images` folder without checking and updating the corresponding image URLs inside these HTML files.

When this repository is hosted through GitHub Pages, the HTML files must reference the official company-hosted GitHub Pages image URLs.

Do not replace company-hosted image URLs with links from personal GitHub accounts.

## Editing an Existing Signature

Before changing a production HTML signature:

1. Keep the currently working version available until the replacement has been tested.
2. Make the required HTML or asset changes.
3. Confirm that all image URLs point to the correct company-hosted files.
4. Open the HTML page in a browser and check that the full signature renders correctly.
5. Verify that all clickable links open the correct destinations.
6. Copy the rendered signature into Gmail.
7. Send a test email.
8. Check the received email on desktop and mobile.
9. Confirm that the QR code works correctly.
10. Approve the updated version only after all testing is complete.

## Adding Future Employee Signatures

Future employee email signatures should use clear and consistent filenames.

Recommended format:

`employee-name-email-signature-vinicio-adivisory.html`

If the employee requires a branch-specific version, include the branch identifier where appropriate.

Examples:

`employee-name-email-signature-vinicio-adivisory-fze.html`

`employee-name-email-signature-vinicio-adivisory-india.html`

## Security

These HTML files are intended for public-facing company email signatures.

Do not include:

* Passwords
* API keys
* Login credentials
* Confidential company information
* Private internal documents
* Sensitive employee information

Only approved public company and contact information should be included in production signature files.
