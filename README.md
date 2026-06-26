# San Francisco — Two Days & a Road Trip North

A self-contained, single-page field guide: a routed two-day walk through San
Francisco grouped so you never double back, followed by the northbound van leg
up the Marin coast and into redwood country.

## What's inside

- **Editorial layout** with custom typography (Bricolage Grotesque, Newsreader,
  Spline Sans Mono) and a fog-and-bridge color palette.
- **Scrollytelling map** — a sticky [Leaflet](https://leafletjs.com/) map that
  follows along as you scroll, highlighting each stop for the two city days.
- **14 stops** across Day 1 (the West Side), Day 2, and the road trip north,
  each with timing, neighborhood, notes, and an **Open in Maps** link.
- **Field notes** and per-leg tips (biking the Presidio, the drive between the
  two northern stops, the Avenue of the Giants detour).
- **Embedded photography** — all images are inlined as data URIs, so the page is
  a single fully portable file.
- **Responsive & accessible** — collapses to one column on mobile and respects
  `prefers-reduced-motion`.

## Run it

It's a static page. Open `index.html` directly, or serve the folder:

```bash
python3 -m http.server 8000
# then open http://localhost:8000
```

> An internet connection is needed for the Google Fonts, the Leaflet library,
> and the OpenStreetMap map tiles. The page's own photos are embedded and load
> offline.

## Structure

| File         | Purpose                                                  |
| ------------ | -------------------------------------------------------- |
| `index.html` | The entire site — markup, styles, images, and map script |

The page is intentionally a single file so it can be dropped anywhere (static
host, GitHub Pages, email attachment) and just work.
