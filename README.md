# Cory J. Chavis — Website

Open index.html in a browser, or upload this folder's contents to your GitHub repo (main branch) / any host.

- index.html — landing page (book, about, speaking, booking form, email opt-in)
- support.js — runtime the page needs (keep next to index.html)
- assets/ — hero photo, book cover, logo, Author One Sheet PDF

Contact: win@coryjchavis.com · www.coryjchavis.com
Order link: https://www.amazon.com/dp/B0H2V19FH2
Socials: IG · FB · LinkedIn · TikTok — Cory J Chavis
Brand colors: Navy #0F2747 · Gold #C6A15B · Ivory #F7F5F0 · Burgundy #6B1022 · Slate #7D8794
Fonts: Cormorant Garamond (display) + Inter (body), loaded from Google Fonts.

## Forms

The booking form and email opt-in submit to [FormSubmit](https://formsubmit.co)
(free, no account) and deliver to **win@coryjchavis.com**.

One-time activation: the first time either form is submitted after going live,
FormSubmit emails win@coryjchavis.com an activation link. Click it once and all
future submissions arrive automatically. To change the destination address,
edit the two `fetch("https://formsubmit.co/ajax/...")` calls in `index.html`.
