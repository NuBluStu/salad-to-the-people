# Salad to the People

A one-page site for a rooftop microgreens project on Manhattan's Upper West Side.
Its single job is to get a building manager, owner, or co-op board member to pick
up the phone about roof access.

Static HTML. No build step, no framework, no backend, no third-party requests
except one Google Fonts stylesheet.

## Files

```
index.html      the whole site — markup and CSS in one file
img/            32 photographs, 2 widths each, WebP + JPEG (64 files)
CREDITS.md      photo provenance, licensing, and the caption honesty rule
design/         the three design directions explored before choosing this one
```

`design/` is reference material, not part of the published site. It can be
deleted without affecting anything.

## Before this goes public

**1. The phone number.** `[PHONE]` appears in 9 places and is wired as
`tel:+10000000000`. The page cannot ship with it. Recommend a Google Voice number
rather than a personal cell — a raw mobile on a public page attracts spam
permanently, and a separate line means knowing what a call is before answering.

**2. Weigh a tray.** The page promises a real, measured weight in writing. Weigh
one fully watered 10×20 tray and one loaded rack section. The promise reading as
rigor rather than as a dodge depends on the number existing.

**3. Confirm the two commitments the page makes on your behalf** — a 30-day
termination clause, and the insurance certificate landing before the first tray
goes up. Both are printed as promises. If you won't sign them, they come off the
page; they are also two of the reasons the page gets a call back.

## The rules this page is built on

Break these and the page stops working, because its entire persuasive strategy is
that it is visibly not overselling.

- **Nothing fabricated.** No testimonials, no logos, no press, no awards, no
  invented metrics, and above all **no revenue projection**. The refusal to
  project is the most persuasive thing on the page — a made-up five-year number
  would discount everything above it, and a manager weighing a profit share would
  hold you to it.
- **Never "we".** It is one person. "We" on a one-person page is the fastest way
  to look like a company that isn't there.
- **Every number must be checkable by the reader** (grocery prices on Broadway),
  **biological** (7–10 days seed to cut), **or weighed before publishing**.
- **No photo may imply it shows this operation.** See `CREDITS.md`. Every image is
  captioned `REFERENCE` because there is no roof yet. When real photos exist,
  swap the file and change the token to `W 85TH ST` — both together.
- **Say "I don't know" where it's true.** Winter, insurance requirements, load
  numbers. Every admitted limit buys permission for the confident parts.

## Deploying to GitHub Pages

Push to a repo named `saladtothepeople` under an account/org named
`saladtothepeople`, or enable Pages on any repo and serve from the default
branch root. There is no build step, so no Actions workflow is needed.

## Local preview

```bash
python3 -m http.server 8824
```
