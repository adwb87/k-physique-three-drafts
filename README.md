# K Physique · Three creative directions

Open `index.html` for a visual comparison, or open any draft directly. Each draft is a complete standalone `index.html`, with inline CSS and JavaScript, embedded fonts and embedded photography. There is no installation, build step, CDN dependency or external asset request.

## The drafts

| Draft | Direction | Typography | Motion |
| --- | --- | --- | --- |
| `01-form-light/index.html` | **Form**: ivory, oxblood, sculptural imagery and a personal editorial voice | Bodoni Moda + Manrope | Cinematic image entrance, scroll-linked portrait movement, staggered reveals and a sticky coaching introduction |
| `02-resolve-dark/index.html` | **Resolve**: dark cinematic photography, oversized type and a direct coaching story | Barlow Condensed + Manrope | Real-time WebGL light and grain, scroll-linked imagery, a sticky method story and active chapter markers |
| `03-momentum-colour/index.html` | **Momentum**: cobalt, acid yellow and a layered sports campaign poster | Archivo Black + Archivo | Layered poster entrance, moving type strip, scroll-linked image and symbols, stepped section reveals |

All three include responsive navigation, visible keyboard focus, reduced-motion support, a manual motion toggle, native FAQ disclosures, an interactive goal selector and working application/email links. Momentum also includes an exclusive disclosure selector for visitors who are starting out, restarting or already training.

## Copy and business details

The copy has been rewritten for each direction, using a shorter emotional opening, a clear coaching method, Kalend’s personal story, an educational progress example and transparent terms. Longer answers sit behind disclosures rather than filling the page.

Business facts and original progress photographs were retrieved from [K Physique](https://kphysique.co.uk/) on 30 September 2026. The Birmingham connection comes from your brief. The website describes **online coaching across the UK**, rather than a confirmed in-person Birmingham service, so the drafts preserve that distinction.

The published founding offer is £100/month for the first five clients’ initial twelve weeks, paid as three monthly payments (£300 total). The standard and continuing rate is £150/month. Availability is qualified in each draft; no remaining-place count is invented.

The primary application links lead to `https://kphysique.co.uk/#apply`. Email links use `hello@kphysique.co.uk`. Goal selections prepare a relevant email subject; they are not sent or stored by the page. These drafts do not connect a new application backend or send submissions themselves.

No reviews, qualifications, client counts or guaranteed outcomes have been fabricated. The coach narrative is adapted from Kalend’s published account. Results are illustrated with the original published photographs, without generative alterations.

## Campaign imagery

The three selected campaign images were made with the **built-in image generation tool**, using the published `progression-01-03-720.jpg` body photograph as the edit reference. They are embedded inside their respective HTML files. These are art-directed draft images, not progress evidence or authentic new photo shoots. The campaign notes on the pages make that distinction.

You authorised a provisional face if useful. These compositions retain a crop at the neck, so no invented facial identity is used. A future real portrait can replace the image `src` on the corresponding hero image. The source photograph is still shown unchanged in the evidence sections.

### Final image prompts

**Form**

> Create a tasteful fully clothed athletic campaign edit from this adult personal trainer reference. Dress him in an ivory sleeveless high-neck athletic vest and dark full-length track pants. Keep his body size, pose, arm proportions and visible skin tone exactly faithful to reference. Crop at the neck with no head or face. Waist-up editorial framing, vertical 3:4. Warm ivory plaster studio backdrop, warm late-afternoon side lighting, sculptural fine-art sports portrait, subtle film grain, natural photographic realism, quiet premium aesthetic. No text or logos.

**Resolve**

> Edit supplied photograph to a dark cinematic personal training campaign. Keep this exact person's body silhouette, pose, muscle size and definition, waist and proportions faithfully unchanged, no physique enhancement. No face or head: retain neck crop. Frame chest to upper thigh. Replace domestic room entirely with deep near-black warm charcoal photographic studio backdrop. Position body on right half of a wide 16:9 frame with left half empty darkness for website text. Replace blue shorts with plain dark charcoal training shorts. Directional side lighting, sophisticated black and white with warm highlights, rich sculptural shadows, fine film grain. Preserve the visible physique exactly, only art direct background and lighting. No text or logo.

**Momentum**

> Create a fully clothed premium sportswear campaign edit from this adult trainer reference. Dress him in a fitted cobalt blue sleeveless high-neck training top and dark full-length track pants. Keep his body size, arm proportions, skin tone and stance exactly faithful to the reference. No head or face, image cropped at neck. Waist-up portrait, vertical 3:4. Replace room with a rich cobalt studio background, direct studio flash, graphic clean composition, fashion sports magazine art direction, high contrast. No logos or text, no physique enhancement.

## Implementation notes

- WebGL is progressive enhancement. Resolve retains its photograph and content if WebGL is unavailable.
- Ambient rendering is capped near 30 fps, uses a capped pixel ratio and skips drawing offscreen, in hidden tabs or with motion disabled.
- Scrolling remains native. Reveal animations use transforms and opacity; there is no scroll hijacking.
- Body fonts and display fonts are embedded WOFF2. Campaign images use WebP; original progress photographs retain their JPEG bytes.
- FAQs and the starting-point selector work without JavaScript. Content and application links remain accessible. Optional scripted goal and motion controls are hidden when scripting is unavailable.
- The drafts contain no analytics, cookies or local storage.

See `QA.md` for the final checks. Browser screenshots are in `previews/`.
