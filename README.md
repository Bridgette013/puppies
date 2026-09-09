# Hustlin' Huskies — litter landing page

Single-file static landing page. `index.html` has no build step, no
dependencies, and no JavaScript. The four puppy photos are embedded as
base64 data URIs, so the file works on its own — you can email it, drop it
on any host, or open it straight off a thumb drive.

`img/` holds the full-size originals (EXIF stripped) in case you ever want
to serve real image files instead of the embedded copies.

**Live at https://bridgette013.github.io/puppies/** — GitHub Pages, deployed
from `main` / root.

## Reserving a pup — Stripe deposits

Each pup card has a **Reserve** button wired to a live Stripe Payment Link
that collects a **$300 deposit** (applied toward the $800 price). The links
live in the VVV Digitals / StoreKeyed Stripe account, and each one is capped
to a single payment — so once a pup's deposit is paid, that link closes
itself and can't be paid twice.

**To mark a pup reserved on the page:** open `index.html`, find that pup's
card (search for the name, e.g. `Lucy`), and change its
`<li class="pup" data-status="available" …>` to `data-status="sold"`. That
grays the badge to **Reserved** and turns the button into a non-clickable
**Spoken for**. Commit and push to update the live site.

## Optional additions

Not required — the page is complete as-is — but you can add these if you get
the details:

1. **Which vaccine** specifically was given at 6 weeks (the page just says
   "first round")
2. **Per-pup details** — weights, eye color, markings, temperament are not on
   the cards; add them per pup if you want

## Kept off the page on purpose

Covered in person instead: that these are foster pups, that shots and
deworming were given in-home rather than at a clinic, that rabies has not been
given, and the breed-specific warnings (noise, escaping, recall, shedding,
exercise needs). The page states nothing false — it just doesn't volunteer
these.

## Confirmed (do not change)

| | |
|---|---|
| Kennel | Hustlin' Huskies |
| Breeders | Britne & Chevelle |
| Breed | Siberian Husky |
| Phone | 623-217-1039 |
| Email | hustlinhuskies@vvvdigitals.com |
| Location | Glendale, AZ |
| Whelped | July 18, 2026 |
| Ready | September 12, 2026 (8 weeks) |
| Pups | Lucy (F), Chip (M), Frankie (M), Eddie (M) |
| Price | $800 |
| Deposit | $300, applies to the price |
| Vaccines | First round at 6 weeks — Aug 29, 2026 |
| Deworming | Aug 25 and Sept 8, 2026 |
| Papers | Parents' paperwork being obtained from the owner |
