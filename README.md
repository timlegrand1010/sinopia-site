# Sinopia website — integrated draft (v3 — depersonalised)

Same restyled look as before (Spectral serif, margin-note labels, sheet/row layout, from your `styles.css` and `assets/Asset_3.svg` / `Asset_6.svg`), but the copy now speaks entirely as **Sinopia**, not as Professor Tim Legrand. Every mention of the name, and every personal credential (ARC Future Fellow, UN advisor role, ICJ citation, AJIA editorship, board seats, book titles, specific past workshop audiences and delivery institutions) has been removed. You said you'd add your own profile back in later — this draft leaves that slot open rather than guessing at how you'll want it framed.

## What's in here

- **index.html** — front page: opening statement, Advice (four services), Research (the sanctions-practice register), Standing (now a short, institutional paragraph about how Sinopia works — no names, no personal credentials), Contact.
- **workshops.html** — rewritten as a topics/capability page ("Training topics & masterclasses") rather than a delivery record: same subject areas as before, but each is now a one-line description of what the session covers, with the institution names and "delivered to EL1–SES Band 2" audience claims removed.
- **styles.css** — unchanged from the previous pass.
- **assets/** — `Asset_3.svg` (wordmark) and `Asset_6.svg` (standalone mark, still unused).

## What I removed

- **academic.html** — deleted. It held the full personal bio, appointments list and five-book bibliography, which no longer has a place in a "what Sinopia can do" site. All nav and footer links to it are gone from the other pages too.
- The Standing section's appointments list (ARC Future Fellow, UN Risk Management Unit role, AJIA editorship, AIIA board seat, Commonwealth Inspector of Transport Security, ICJ citation) — replaced with a short paragraph about Sinopia's positioning and way of working.
- The Research section's "two books... continuing advisory work at United Nations level on sanctions in Somalia and Afghanistan" line, and the Expert Witness entry's "decade of published research" claim — both softened to generic "specialist research" language.
- Every workshop/masterclass and short-course entry's institution name (National Security College, Emergency Management Australia, DFAT Australia Awards) and specific delivered-to audience — replaced with a plain description of the topic.

## Things worth checking

- [ ] **Where your profile goes back in.** There's no `academic.html` or Standing-section bio placeholder right now — when you're ready, let me know whether you want a dedicated profile page restored, folded into Standing, or something else.
- [ ] **Contact email.** Still `contact@sinopia.com.au` — flagging again in case you want `tim.legrand@sinopia.com.au` or something else once your profile is back in.
- [ ] **Nav on mobile.** Your stylesheet still hides the 3rd and 4th menu items under 780px (now "Standing" and "Contact" disappear, since Academic profile is gone from the nav). Worth a look once the nav is finalised.
- [ ] **Fonts/CDN.** styles.css still pulls Spectral from Google Fonts via `@import` — a live external request each page load, fine for GitHub Pages.

Open index.html directly in a browser to preview, or drop the whole folder into your sinopia.com.au GitHub Pages repo to publish.
