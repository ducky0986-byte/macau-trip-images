# macau-trip-images — maps branch

Route posters for the Macau 2-night/3-day Notion travel pages (Day 1–3).

- `maps/day1_route.png` — Day 1 (11/28): airport → peninsula historic centre → Cotai
- `maps/day2_route.png` — Day 2 (11/29): peninsula south → Panda Pavilion → Coloane → Cotai → Sai Van Lake
- `maps/day3_route.png` — Day 3 (11/30): peninsula → Ruins of St. Paul → Taipa → airport

4400×3025 px each (4K). Built from Google Maps `scale=2` HiDPI tiles (`mt*.google.com/vt/lyrs=m`,
`scale=2`, `hl=ko`, 512×512) stitched at full resolution, with a numbered route overlay, direction
arrows and a Korean legend. Saved as full-colour RGB PNG (no palette quantisation). Map data © Google.
Total for the three posters: about 15.4 MB.

Served with `https://cdn.jsdelivr.net/gh/ducky0986-byte/macau-trip-images@<commit>/maps/day1_route.png`.
This branch exists because the `main` branch (118 photos, 49.7 MB) is already at jsDelivr's 50 MB
package limit, so files added there are refused by the CDN.
