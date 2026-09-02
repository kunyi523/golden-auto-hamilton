# Golden Auto Service / Golden Auto Repair — unofficial Hamilton pitch sample

A mobile-first one-page website **proposal** for **Golden Auto Service Inc** (also listed as **Golden Auto Repair**) at 35 Parkdale Ave N, Hamilton, ON L8H 5W7.

**This is not the shop’s official website.** It is an unofficial sample prepared as a pitch so the shop can see what a simple site could look like. It is not affiliated with Golden Auto Service Inc or Golden Auto Repair.

There is **no contact form**, no online booking, and no online payment. The page helps people **call**, **get directions**, or optionally email the address printed on PCBO.

Live URL: [https://kunyi523.github.io/golden-auto-hamilton/](https://kunyi523.github.io/golden-auto-hamilton/)

This is a new public repo. It does **not** overwrite [gus-and-son](https://kunyi523.github.io/gus-and-son/) or [stewart-mechanical](https://kunyi523.github.io/stewart-mechanical/).

## How to open

The site is `index.html` with inlined CSS/JS. Open the file in a browser, or visit the Pages URL on a phone.

Optional local server, from this folder:

```bash
python3 -m http.server 8080
```

Then visit http://localhost:8080

## GitHub Pages

Static files live at the **repository root**. Enable branch-based Pages (same pattern as the Stewart Mechanical sample):

1. **Settings → Pages**
2. Build and deployment → Source: **Deploy from a branch**
3. Branch: **main**, folder: **/** (root)
4. Save

GitHub will serve the site at `https://kunyi523.github.io/golden-auto-hamilton/`.

Do not add a GitHub Actions workflow for Pages. Use branch-based Pages from `main`.

## Design

Same one-pager grammar as the other Hamilton pitch samples: sticky header, click-to-call, 56px tap targets, hours, map, no form. Visual language follows the Stewart Mechanical trades sibling (dark canvas, gold/copper CTAs, Inter + JetBrains Mono) rather than the Gus & Son barbershop serif palette — the shop name is Golden, so the gold accent stays.

## What’s on the page

- Shop names as directories print them, Parkdale address, click-to-call (`tel:+19055471112` — **905-547-1112**)
- Thumb-sized **Call** and **Directions** buttons (56px tap targets) plus a mobile sticky bar
- Hours from AutoTechIQ (Mon–Fri 9:00 AM–5:30 PM, Sat 9:00 AM–1:00 PM, Sun closed), with a note that some directories print a different grid
- Google Map embed and Get directions for 35 Parkdale Ave N
- Optional mailto for the PCBO email (`goldenautorepairs@gmail.com`)
- Licensed Unsplash atmosphere photos — **not** photos of this shop
- No invented customer quotes
- A clear footer: unofficial sample, not affiliated

A small script only labels today’s hours in the America/Toronto timezone.

## Facts used (public sources only)

- **Name:** Golden Auto Service Inc / Golden Auto Service on Maps-style directories (AutoTechIQ, MapQuest, AllBiz, Yelp as Golden Auto Centre). PCBO lists **GOLDEN AUTO REPAIR** at the same address.
- **Address:** 35 Parkdale Ave N, Hamilton, ON L8H 5W7
- **Phone (primary):** 905-547-1112 — AutoTechIQ, MapQuest, Yelp, AllBiz, and the listed `goldenautoservice.com` site
- **Phone (also listed):** 905-547-0355 on [PCBO](https://pcbodirectory.ca/listings-details/javid-awan). AllBiz / GOLDEN AUTO CTR directories also print that number as **fax**
- **Email:** goldenautorepairs@gmail.com (PCBO listing for Javid Awan / GOLDEN AUTO REPAIR)
- **Hours:** AutoTechIQ prints Mon–Fri 9:00 AM–5:30 PM, Sat 9:00 AM–1:00 PM, Sun closed (matches the AutotechIQ grid supplied for this pitch). Some aggregator directories print Mon–Fri 9–6 and Sat 10–2 — the page uses the AutoTechIQ grid and says to call to confirm
- **Licence listing:** City of Hamilton public-garage record for 2355823 ONTARIO INC O/A NEW GOLDEN AUTO SERVICE at 35 Parkdale Ave N
- **Website listed:** MapQuest prints http://goldenautoservice.com — that domain was live at research time with the same address and 905-547-1112. This sample is still unofficial and is not that site
- **Rating:** AutoTechIQ / TrustAnalytica report about **4.6** from Google. This page does not quote reviews

## What this page does not do

- Invent customer quotes, names, or star ratings beyond the public 4.6 figure above
- Invent extra services, prices, warranties, or certifications
- Pretend Unsplash garage photos are this bay
- Take bookings or payments
- Copy copy from the Gus & Son or Stewart Mechanical samples as if it were this shop
