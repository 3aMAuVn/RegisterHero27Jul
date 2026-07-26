# Brand and Hero Design Refresh

## What changed

- Added a new scalable primary logo: `assets/brand-mark.svg`.
  - Open-book symbol
  - `Ma³` lettering
  - Deep teal and warm gold palette
  - Transparent, tightly cropped SVG suitable for headers and footers
- Replaced the detailed circular emblem in the website header with the compact new mark.
- Added the compact mark to the footer beside the copyright line.
- Replaced the old fixed-size iframe star background on home and interior-page heroes with a responsive CSS star field.
- Replaced fixed-size registration/enquiry banner iframes and the magician-hat graphic with a responsive branded banner using the new mark.
- Removed the four unused, embedded-image hero banner HTML files after their references were replaced.
- Updated favicon, PWA, Android, and Apple touch icons to match the new identity.
- Updated the service-worker cache name and cached logo asset.

## Responsive behaviour

The new hero background uses CSS gradients and repeating star layers rather than a 2047 × 523 fixed canvas. Hero height, typography, feature pills, and calls to action now adapt using `clamp()` and mobile breakpoints.

## Files to retain

`assets/logo.png` remains in the project as the original detailed secondary emblem. It is no longer used as the small primary website mark, but can still be used for certificates, posters, worksheets, social graphics, or other large-format applications.
