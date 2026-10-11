# Validation · K Physique drafts

Checked on 30 September 2026 in local headless Google Chrome using Playwright, opening the actual standalone HTML files.

## Final results

| Check | Form | Resolve | Momentum |
| --- | --- | --- | --- |
| No page-level JavaScript errors | Pass | Pass | Pass |
| No horizontal overflow at 320, 360, 390, 430, 768, 1024, 1440 and 1920 px | Pass | Pass | Pass |
| Embedded images decode successfully | Pass | Pass | Pass |
| Embedded fonts load successfully | Pass | Pass | Pass |
| No external asset requests | Pass | Pass | Pass |
| Mobile menu opens, closes and dismisses with Escape | Pass | Pass | Pass |
| Native FAQ disclosures work | Pass | Pass | Pass |
| Goal choice updates guidance and email subject | Pass | Pass | Pass |
| Manual animation pause works | Pass | Pass | Pass |
| Reduced-motion rendering works | Pass | Pass | Pass |
| Scroll reveals become visible | Pass | Pass | Pass |
| All internal anchor destinations exist | Pass | Pass | Pass |
| Main content and application remain accessible without JavaScript | Pass | Pass | Pass |
| No mobile overflow without JavaScript | Pass | Pass | Pass |
| WebGL program compiles and links in the browser | N/A | Pass | N/A |
| Starting-point selector opens one answer at a time | N/A | N/A | Pass |

## Visual review and refinements

Reviewed desktop and mobile screenshots, full-page composition and the results/contact sections. Iterations corrected the light draft’s mobile image ordering, mobile type wrapping, dark numerical and heading overflow, narrow-screen colour draft headings and contact colour contrast. The third concept was redesigned into a layered poster to distinguish its composition from the light and dark directions. Fonts were replaced with compressed WOFF2 assets and duplicated variable-font data was consolidated.

The original progress photos remain unchanged; generated campaign imagery is separately identified. Copy and prices were checked against the retrieved live site, with availability caveats retained for the founding offer.

## Scope

The checks above are browser and implementation checks, not an independent WCAG certification or a claim of award recognition. Safari, Firefox and physical-device GPU performance have not been tested. No application or email was submitted. Live application and privacy links use the existing K Physique destinations.
