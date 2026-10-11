# IA#1 Website - Final Touches

Storyboards, asset and styling inventory, and APA 7th edition references for the portfolio website.

## 1. Storyboards

The layouts below show the portfolio homepage at the requested 600px mobile and 950px desktop viewports. Both keep the same content order while adapting the layout to the available width.

### Mobile - 600px viewport

Single-column reading flow, stacked sections, and touch-friendly links.

```text
┌────────────────────────────────────┐
│ Header: ID + social icons           │
├────────────────────────────────────┤
│ Portrait + profile introduction     │
│ Bio + contact link                  │
├────────────────────────────────────┤
│ Skills: stacked                     │
├────────────────────────────────────┤
│ Projects                            │
│ ┌────────────────────────────────┐ │
│ │ Project 1                      │ │
│ └────────────────────────────────┘ │
│ ┌────────────────────────────────┐ │
│ │ Project 2                      │ │
│ └────────────────────────────────┘ │
├────────────────────────────────────┤
│ Resume / Personality / Development  │
├────────────────────────────────────┤
│ Contact form + footer               │
└────────────────────────────────────┘
```

### Desktop - 950px viewport

The profile and contact areas use the wider screen. Skills can appear in a horizontal row, with project previews arranged across the available width.

```text
┌────────────────────────────────────────────────────────────────┐
│ Header: ID + social icons                                       │
├────────────────────────────────────────────────────────────────┤
│ Portrait                 │ Profile introduction + contact link │
├────────────────────────────────────────────────────────────────┤
│ Skills: horizontal row                                          │
├────────────────────────────────────────────────────────────────┤
│ Projects: image, tools, links                                   │
│ ┌─────────────────┐  ┌─────────────────┐  ┌─────────────────┐ │
│ │ Project 1       │  │ Project 2       │  │ Project 3       │ │
│ └─────────────────┘  └─────────────────┘  └─────────────────┘ │
├────────────────────────────────────────────────────────────────┤
│ Contact information                │ Contact form + footer links│
└────────────────────────────────────────────────────────────────┘
```

**Layout notes:** Keep the dark background, light headings, legible body copy, consistent spacing, responsive images, and visible links between Home, Resume, Personality, and Development.

## 2. Asset and Styling Inventory

Color values are transcribed from the supplied stylesheet. HSL values were converted to RGB and hexadecimal.

### Color palette

| CSS token / color | RGB | Hex | Intended use |
|---|---:|---|---|
| `--bg-dk-md` | `0, 0, 0` | `#000000` | Page background |
| `--bg-base-dk-md` | `11, 13, 14` | `#0B0D0E` | Cards, footer, and form surfaces |
| `--bg-light-dk-md` | `23, 25, 28` | `#17191C` | Borders and raised areas |
| `--base-text-dk-md` | `240, 242, 244` | `#F0F2F4` | Primary text on dark surfaces |
| `--text-muted-dk-md` | `165, 178, 192` | `#A5B2C0` | Secondary text |
| `--text-muted-light-md` | `76, 76, 76` | `#4C4C4C` | Muted gray accent and rules |
| `--bg-dark-light-md` | `230, 230, 230` | `#E6E6E6` | Light-mode background token |
| `--bg-base-light-md` | `241, 242, 244` | `#F1F2F4` | Light-mode surface |
| `--bg-light-light-md` | `255, 255, 255` | `#FFFFFF` | Light-mode raised surface |
| `--base-text-light-md` | `13, 13, 13` | `#0D0D0D` | Light-mode primary text |
| `--primary-font-color` | `248, 249, 250` | `#F8F9FA` | Primary font white |
| `--primary-white-color` | `248, 249, 250` | `#F8F9FA` | White backing for social icons |
| `--secondary-white-color` | `233, 236, 239` | `#E9ECEF` | Secondary white |
| `mediumaquamarine` | `102, 205, 170` | `#66CDAA` | Original form-button accent |

### Typography

- **Font family:** DM Sans, sans-serif, loaded through Google Fonts.
- **Root font size:** `62.5%` (10px when the browser default is 16px).
- **Root font weight:** Not explicitly set; the normal browser default is 400.
- **Weights in the supplied CSS:** 400 for body copy and 700 for headings. The Google Fonts request loads a variable range of 100-1000.

### Images, icons, and documents

| Asset | Use and rendered dimensions |
|---|---|
| `github-logo.png`, `linkedin-logo.png`, `instagram-logo.png` | Social icons; CSS width is 30px, with height auto to preserve the source ratio. |
| `main-logo.png` | Favicon; display size is browser-defined. |
| `anthony.png` | Profile portrait; the supplied stylesheet sets no fixed dimensions. |
| `bento-grid-component.png`, `majestic-tech.png`, `blog-post.png`, `profile-card.png` | Project thumbnails; maximum width 350px (`35rem`), height auto. |
| `Anthony_Granston-Tech-Resume-2026.pdf` | Resume PDF embedded and linked from the resume page. |
| DM Sans Google Fonts stylesheet | Shared typeface resource used by the site pages. |

Image sizes above are CSS display sizes. Intrinsic pixel dimensions were not available in the supplied source text.

## 3. References

Clason, G. S. (1988). *The richest man in Babylon*. Signet. https://icrrd.com/public/media/16-05-2021-070111The-Richest-Man-in-Babylon.pdf

Harvard University. (n.d.). *Learn with generative AI*. https://www.harvard.edu/ai/learning-resources/

Harvard University, Office of the Provost. (n.d.). *Guidelines for using ChatGPT and other generative AI tools at Harvard*. https://provost.harvard.edu/guidelines-using-chatgpt-and-other-generative-ai-tools-harvard

Sternod, M. (2026, June 25). *Code, commission, and character: The unstoppable career of Rear Adm. Grace Hopper*. Naval History and Heritage Command. https://www.history.navy.mil/news-and-events/news/2026/code-commission-character-grace-hopper.html

UNESCO. (2023). *Guidance for generative AI in education and research*. https://www.unesco.org/en/articles/guidance-generative-ai-education-and-research

Internal portfolio images and the resume are personal/site files listed in the asset inventory. Source page URLs are retained in the website markup for direct access.
