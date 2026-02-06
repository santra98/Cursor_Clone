**Cursor Landing Page**

🌐 **Live Demo**: [View Resume](https://cursor-landing-page-clone.netlify.app/)

- **File:** [index.html](index.html) — Static clone of Cursor landing page.

**Recreated Sections**
- **Header:** logo SVG, nav links, sign-in and download CTAs.
- **Hero:** headline, primary CTA, hero image.
- **Trusted By:** "Trusted every day" and company logos.
- **Features:** three feature blocks (Agent, Tab/autocomplete, Ecosystem) with images.
- **Testimonials:** testimonial grid with multiple quotes and avatars.
- **Use Cases / Stories:** three use-case cards with images and links.
- **Changelog:** list of recent updates/articles and CTA.
- **Team / About:** team blurb, join CTA, team photo.
- **Final CTA:** large final call-to-action section.
- **Footer:** product/resources/company/legal/connect columns and language selector.

**Fonts and Typography**
- **Font stack:** Arial, Helvetica, sans-serif (declared in `style.css`).
- **Heading weights/sizes:** hero and major headings use lighter/large sizes (examples in CSS: `.hero-heading` 26px, `.final-section h1` 72px, `.testimonial-heading` 36px).

**Color Palette (from `style.css`)**
- **Background (page):** #14120B — primary page background.
- **Card / panel bg:** #1B1913 — panels, feature/testimonial/use-case backgrounds.
- **Borders / subtle lines:** #1F1D17 and #37352F — element borders and subtle accents.
- **Primary text:** #EDECEC — main copy color.
- **Muted text:** #999896 / #999889 / #999881 (used for secondary labels and metadata).
- **Accent / action color:** #F54D00 — links and CTA accents.
- **Language icon fill (small):** rgb(22, 19, 19) (used for language span text color).

**Referenced Assets**
- Hero and feature images: `/assets/HeroImage.png`, `assets/CursorIde-Template1.png`, `assets/CursoeIde-Template2.png` (note: filename typo in HTML), `assets/CursorIde-Template3.png`.
- Use-case images: `assets/frontier1.png`, `assets/frontier2.png`, `assets/Fronteir3.png` (note: inconsistent spelling).
- Avatars and team photos: `assets/diana-hu-avatar.webp`, `assets/shadcn-avatar.webp`, `assets/andrej-karpathy-avatar.webp`, `assets/patrick-collison-avatar.webp`, `assets/theprimeagen-avatar.webp`, `assets/greg-brockman-avatar.webp`, `assets/homepage-team-photo.webp`.
- Many company logo SVGs are included inline in `index.html` (no external files required for them).

