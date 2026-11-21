# macau-trip-images — maps branch

Route posters for the Macau 2-night/3-day Notion travel pages (Day 1–3).

- `maps/day1_route.png` — Day 1 (11/28): airport → peninsula historic centre → Cotai
- `maps/day2_route.png` — Day 2 (11/29): peninsula south → Panda Pavilion → Coloane → Cotai → Sai Van Lake
- `maps/day3_route.png` — Day 3 (11/30): peninsula → Ruins of St. Paul → Taipa → airport

3200×2200 px each. Built from Google Maps tiles (`mt1.google.com/vt/lyrs=m`, `hl=ko`) with a numbered
route overlay, direction arrows and a Korean legend. Map data © Google.

Served with `https://cdn.jsdelivr.net/gh/ducky0986-byte/macau-trip-images@<commit>/maps/day1_route.png`.
This branch exists because the `main` branch (118 photos, 49.7 MB) is already at jsDelivr's 50 MB
package limit, so files added there are refused by the CDN.
