# Email Signature Production Images

This folder contains the production image assets used by the official Vinicio Adivisory HTML email signatures.

These files are referenced directly by the HTML files stored in the `/html` folder and are required for the signatures to display correctly in Gmail and other email clients.

## Current Signature Versions

This folder currently supports:

* CEO email signature — Arabic logo version
* CEO email signature — Trademark logo version

## Signature Image Files

### Arabic Logo Version

* `signature-slice-top.png`
* `signature-slice-left-middle.png`
* `signature-slice-bottom.png`

### Trademark Logo Version

* `signature-trademark-slice-top.png`
* `signature-trademark-slice-left-middle.png`
* `signature-trademark-slice-bottom.png`

These image slices combine to form the complete visual email signature.

## Social and Contact Icons

The following SVG files are used by the clickable section of the HTML signatures:

* `icon-linkedin-fixed.svg`
* `icon-instagram-fixed.svg`
* `icon-facebook-fixed.svg`
* `icon-calendar-fixed.svg`

## Important

Do not rename, move, or delete these files without also updating the corresponding URLs inside the HTML signature files.

The HTML signatures depend on the exact filenames and paths contained in this folder.

Original source materials such as company logos, the CEO photograph, and QR-code images should be stored separately in the `/source-assets` folder rather than here.

## Purpose of This Folder

The `/images` folder should contain only files required by the live email signatures.

This helps keep the production assets separate from editable source materials and makes future maintenance easier as additional employee signatures are created.
