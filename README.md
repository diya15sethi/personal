# Diya Sethi × L'Oréal Professionnel

A cinematic single-page microsite. Built to be dropped into **Lovable** or deployed to **Vercel** with zero build step.

## Folder structure

```
loreal-diya-site/
├── index.html          # the entire site (self-contained)
├── images/             # all photos
│   ├── silks-blue.jpg
│   ├── silks-teal.jpg
│   ├── portrait-flowers.jpg
│   ├── portrait-mirror.jpg
│   ├── portrait-blazer.jpg
│   ├── portrait-gallery.jpg
│   ├── portrait-venue.jpg
│   ├── climbing.jpg
│   ├── shampoo-ritual.jpg
│   ├── products-flatlay.jpg
│   ├── mood-books-shelf.png
│   ├── mood-books-bed.png
│   ├── mood-loreal-display.png
│   └── mood-hair-collage.png
├── videos/
│   └── aerial.mp4
└── README.md
```

## What's inside (chapters)

- **Hero** — Diya Sethi, Mumbai, ambassador reveal
- **I · About** — IT engineer + behavioral science mind
- **II · The Ritual** — L'Oréal Professionnel wash-day + interactive vanity
- **III · The Mane** — mood selector + hairstyle gallery + interactive mirror
- **IV · In Motion** — aerial silks/hoops + video + climbing
- **V · In Thought** — psych books + writing
- **VI · What Beauty Means** — the personal definition
- **VII · Why L'Oréal Professionnel** — brand connection
- **VIII · Honest Portrait** — strengths + growing edges
- **IX · Constellation** — interactive 7-star map
- **Finale** — Because you're worth it

## Interactive elements

- Cursor follows with gold ring on hover
- Preloader with gold fill bar
- GSAP scroll reveals + parallax + Ken-Burns hero
- Clickable vanity products → fun-fact modal
- Hairstyle gallery with mood filter (Soft / Bold / Serene / Fierce)
- Interactive mirror with shimmer sweep on hover
- Fun-fact hotspots (+) scattered across images
- Personality constellation — click stars to reveal facets
- Top progress bar

## Deploy: Vercel (fastest)

1. Zip the entire `loreal-diya-site` folder
2. Go to [vercel.com/new](https://vercel.com/new) → drag the folder in
3. Deploy — you'll get a `*.vercel.app` URL in seconds
4. No build config needed (it's static HTML)

Alternative — drag onto [Netlify Drop](https://app.netlify.com/drop) for the same result.

## Deploy: Lovable

1. Open [lovable.dev](https://lovable.dev) → **New Project** → **Import Files**
2. Upload the entire `loreal-diya-site` folder
3. Lovable will detect the static HTML site
4. Ask Lovable to iterate visually — e.g. *"change the gold to rose gold"*, *"add a testimonial section"*
5. Publish to get a shareable Lovable URL

## How to edit copy in Lovable

All the writing lives in `index.html`. Key search terms to find sections quickly:

- `CHAPTER · I` — About Me copy
- `CHAPTER · VI` — What Beauty Means
- `CHAPTER · VII` — L'Oréal Professionnel rationale
- `CHAPTER · VIII` — Strengths + Growing Edges
- `const facts =` — all popup content in one object; edit the strings

## Swapping images

Drop new photos into `images/` with the same filenames and they'll appear on the site — no code change needed. Ideal aspect ratio is **3:4 portrait** for gallery tiles.

## Tech

- No build step. Single HTML file.
- Tailwind CSS via CDN
- GSAP 3.12 + ScrollTrigger via CDN
- Google Fonts: Cormorant Garamond · Italiana · Inter
- All assets are relative paths — works locally by opening `index.html` in a browser

## Note

This is a personal creative application concept for L'Oréal Professionnel. Not an official brand campaign.
