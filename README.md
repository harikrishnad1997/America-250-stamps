# America 250 Stamps

A GitHub Pages checklist of all **46 American Revolution parks** in the Passport to Your National Parks® / America 250 set — divided by **region and state**, with a map.

**Live site:** https://harikrishnad1997.github.io/America-250-stamps/
**Full-screen map:** https://harikrishnad1997.github.io/America-250-stamps/map.html

## What's on the site

- Every park as a checklist item, grouped Region → State
- Each park name links to its **Google Maps** location
- An **NPS site** link next to each park goes to its official nps.gov page (all 46 verified live, Oct 23, 2026)
- An embedded **Leaflet / OpenStreetMap** map with all 46 pins, numbered within each region and color-coded:
  - 🔵 Northern — 16 parks
  - 🟠 Central — 19 parks
  - 🟢 Southern — 11 parks

## The list

| Region | Parks | States |
|---|---|---|
| Northern | 16 | Massachusetts (7), New York (9) |
| Central | 19 | Delaware (1), District of Columbia (3), Indiana (1), Kentucky (1), Maryland (1), New Jersey (3), Pennsylvania (6), Virginia (3) |
| Southern | 11 | Arkansas (1), Florida (2), North Carolina (2), South Carolina (6) |
| **Total** | **46** | |

Source: *American Revolution Parks Checklist* (Passport to Your National Parks® – Northern, Central & Southern Regions), supplied as a PDF on Oct 23, 2026.

## Pin notes

- **Washington-Rochambeau Revolutionary Route NHT** (listed under Pennsylvania) is a multi-state trail — pinned at Yorktown, VA, its southern terminus.
- **Overmountain Victory NHT** is a multi-state trail — pinned at Gaffney, SC.
- **Cumberland Gap NHP** spans KY / TN / VA — pinned at the visitor center near Middlesboro, KY.
- **Boston NHP** is a dispersed park — pinned at the Charlestown Navy Yard / Bunker Hill end.
- **Fire Island NS** is pinned at the Wilderness Visitor Center (Smith Point / Mastic Beach end).
- **Charles Pinckney NHS** is listed under Charleston but is in Mount Pleasant, SC; **Kings Mountain NMP** is pinned near Blacksburg, SC.
- **Prince William Forest Park's** town was cut off in the source list — it is at Triangle, VA.

## Files

| File | Purpose |
|---|---|
| `index.md` | The Pages home page — checklist by region and state, with the embedded map |
| `map.html` | Standalone full-screen Leaflet map (all 46 pins, coordinates in the `STOPS` array) |
| `_config.yml` | Jekyll config (`jekyll-theme-cayman`) |

## Publishing

GitHub Pages is enabled on this repo (Deploy from a branch → `main` → `/ (root)`). Pushing a change to `index.md`, `map.html`, or `_config.yml` rebuilds the site in about a minute. The repo is public because GitHub Pages on a free account requires a public repo.

Related: the 3 DC parks on this list (Constitution Gardens, Thomas Jefferson Memorial, Washington Monument) are also on the [DC Stamp Hunt](https://harikrishnad1997.github.io/dc-stamp-hunt-trip/) itinerary for Nov 19–22, 2026.
