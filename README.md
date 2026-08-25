# Vinicio Email Signatures

Official repository for Vinicio Adivisory email signature assets, HTML signature files, and supporting resources.

This repository is used to host and maintain the company's official email signatures, including signature designs, clickable social and contact links, production image assets, and source materials used to create future versions.

## Repository Structure

```text
Vinicio-Email-Signatures/
│
├── html/
│   └── Final HTML email signature files
│
├── images/
│   └── Production image assets used directly by the HTML signatures
│
├── source-assets/
│   └── Original logos, photographs, QR codes, and other source materials
│
└── README.md
```

## Current Signatures

The repository currently supports the following CEO email signature versions:

* Arabic Logo Version
* Trademark Logo Version

Each version uses a compact HTML layout designed for use with Gmail and includes clickable links for relevant company and contact platforms.

## HTML Folder

The `/html` folder contains the final HTML files used to display the email signatures.

These files reference the production assets stored in the `/images` folder.

The HTML files should be tested in a browser and in Gmail before being approved for company use.

## Images Folder

The `/images` folder contains only the production assets required by the live HTML signatures.

This includes:

* Signature image slices
* LinkedIn icons
* Instagram icons
* Facebook icons
* Meeting/calendar icons

Do not rename, move, or delete production files without also updating the corresponding HTML file paths.

## Source Assets Folder

The `/source-assets` folder contains the original materials used to create and maintain the signatures.

Examples include:

* Company logos
* Employee photographs
* QR-code images
* Original branding assets

These files are retained for future updates and should not normally be referenced directly by the live HTML signatures.

## Hosting

The repository is intended to work with GitHub Pages so that signature images and HTML files can be accessed publicly by email recipients.

Public accessibility is required because email clients such as Gmail must be able to load the hosted signature images without requiring users to sign in to GitHub.

## Maintenance

When updating an existing signature:

1. Preserve the existing production version until the replacement has been fully tested.
2. Upload new or updated image assets using clear and consistent filenames.
3. Update the corresponding HTML file if image paths or filenames change.
4. Test the rendered HTML page in a browser.
5. Test the signature in Gmail.
6. Send a test email and verify all images, links, and QR codes.
7. Confirm that the signature also displays correctly on mobile devices.

## Future Employee Signatures

As additional employee signatures are created, they should be added using a consistent naming and folder structure.

Each production signature should have:

* Clearly identified HTML file
* Clearly named production image assets
* Original source materials retained separately
* Verified links and contact information
* A completed browser and email-client test before approval

## Important

This repository contains public-facing company branding and email signature assets.

Do not upload confidential documents, private internal company information, passwords, credentials, API keys, or other sensitive information to this repository.
