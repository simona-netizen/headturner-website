# Headturner website: draft preview

Single-page site for [Headturner](https://www.linkedin.com/in/thilaksarda/), built by Otto from the Figma design.

**This is a draft for review, not the live site.** Some content is placeholder and must be replaced before launch:

- Testimonials: fictional quotes, people and AI-generated portraits
- Results cards and hero proof point: dummy numbers
- "Ads I've made": fictional ads (source: `assets/source/ads.html`)
- Pipeline report: illustrative mockup (source: `assets/source/pipeline-report.html`)
- Logo strips: to be confirmed, with official logo files
- Privacy page: draft, needs company details and review
- Links: booking link and meetup sign-up URL still to come

## Run locally

```sh
python3 -m http.server 8765
```

Then open http://localhost:8765.

## Update the upcoming event

In `index.html`, change `data-event-date` (YYYY-MM-DD) and `data-event-place` on the event section. The date tile fills itself in, and the block hides the day after the event.
