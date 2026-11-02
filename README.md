# יוצאים לדרך

Generic Hebrew trip archive. No visitor names, ages, home addresses, or personal photographs.

## Files
- `index.html`: responsive archive and trip renderer; shareable trip URLs use `#trip=TRIP_ID`.
- `data/trips.json`: proposed and completed trips, stop galleries, sources, and reviews.

## Publish
In repository Settings → Pages, choose Deploy from a branch, then `main` and `/ (root)`. Save and wait for GitHub's deployment. Do not treat the repository URL as a live website. Confirm the Pages URL in Settings before sharing.

## Local preview
Run `python -m http.server 8000` in the repository and open the local server. Opening the HTML directly may prevent JSON loading.

## Reviews
Update the trip review object with `summary`, `worked` (array), `improve`, and `next`. Keep proposed plans distinct from actual visits. There is no server-side review submission or automatic saving. Changes require a repository commit.

## Images and publication readiness
The first version references externally hosted demonstration images with source credits. Image licenses have NOT been verified, and external URLs may break. Before enabling public Pages publication, obtain permission or replace images with licensed assets. Credits alone do not grant rights. Food and landscape images are illustrative, not a promise of menus, weather, or seasonal conditions.

## Privacy
Both repository contents and commit history are public. Do not add private notes, personal details, API tokens, or identifiable visitor photos.
