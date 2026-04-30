# Changelog

## [Build 103] — 2026-04-30
- Pricing section copy fix: "Free to start. Easy to keep going." with subtitle that names the actual offer ("Try Sorted free — 10 imports, no card, no account. Hooked? Sorted+ is just $1.99 a month or $17.99 a year") — replaces the misleading "most families never go near the limit" line that didn't fit a 10-import trial

## [Build 102] — 2026-04-30
- Added Pricing section with four tiers (AUD): Free Trial ($0, 10 imports to try), Sorted+ Monthly ($1.99/mo), Sorted+ Annual ($17.99/yr, highlighted as Most Popular · Save 25%), Sorted+ Lifetime ($79.99 once)
- Pricing card grid matches bento/use-case styling; featured Annual card has orange border, filled CTA, and white-on-orange "Most popular" badge
- Added "Pricing" link to nav
- Footnote on Import Boost ($2.99 add-on for Sorted+ subscribers — 125 extra imports for 30 days)
- Updated Schema.org JSON-LD `offers` to an array reflecting the four real App Store Connect product prices in AUD
- Responsive breakpoints: 4-up on desktop, 2-up at ≤860px, 1-up at ≤640px

## [Build 101] — 2026-04-19
- Conversion copy pass: parent-relief tone throughout, less tech language
- New meta title/description: "Never miss a school date again"
- Hero eyebrow, paragraph and cycling words updated
- How it Works, Use Cases and Features sections rewritten for clarity and warmth
- CTA cycle words updated (school/club/family/kinder/weekend); button updated to "Download on the App Store"
- Added "Built by a parent who got sick of missing school dates" trust line in CTA
- Calendar strip label updated to "Works with the calendar you already use"

## [Build 100] — 2026-04-19
- Full website redesign: new Plus Jakarta Sans font replacing system font stack
- Hero rebuilt as 2-column layout — cycling headline left, floating phone mockup right
- Phone mockup gains a subtle float animation and stronger shadow/glow
- Added "AI-powered for busy parents" eyebrow pill and trust signals row to hero
- Features section rebuilt as a 3-column bento grid with dark "Private by design" card
- Use Cases section background changed from #EBF2FF (off-brand blue) to warm #FDF5EE
- How it Works gains arrow connectors between steps; steps have hover lift effect
- Scroll-reveal animations added to all below-fold sections (IntersectionObserver)
- Calendar strip logos gain opacity treatment and hover state
- CTA gradient deepened and gains a radial glow overlay
- Fixed preview server (/tmp/sorted_preview.js) to respect PORT env variable

## [Build 99] — 2026-04-13
- Add EarlyHunt badge to footer with centered layout and hover opacity effect

## [Build 98] — 2026-04-10
- Add demo video that autoplays inside phone mockup, crossfading to screenshot carousel when finished
- Change Use Cases section background to light blue (#EBF2FF) with blue icons (#3A86FF) from brand kit
- Add Newsletter Summaries (Sorted+) feature card
- Update structured data description to reference Sorted+ subscription
