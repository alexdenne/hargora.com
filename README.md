# hargora.com

The Hargora landing page — preserved from the r/legaltech April Fools 2026
prank (the fictional Harvey × Legora merger). Spun out of the rlegaltech.com
repo on 2026-06-11 because the word keeps earning traffic.

Single self-contained static page (inline styles, no build step). Source of
truth: rlegaltech.com repo commit `6ccc5f428` (`hargora-preview.html` + the
`public/hargora/` assets).

Deploy: static Vercel project, domain hargora.com. Remember to REMOVE the
hargora.com / www.hargora.com domain aliases and redirects from the
rlegaltech-com Vercel project (vercel.json `redirects`) when this goes live,
or the two projects will fight over the domain.

Internal subpage links (About / Products / Blog …) intentionally point at the
retrospective on https://www.rlegaltech.com/hargora/ — this repo is the
landing page only, by design. The "Important disclosures" / "What is real"
sections on the page keep the joke honest.
