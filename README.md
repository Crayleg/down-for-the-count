# Takeaway Knockout

Can't decide on takeaway? Search for nearby places with the Google Places API (New), then let the knockout strike them off one by one until a winner is left.

The API key is never committed. It's stored as the `GOOGLE_PLACES_API_KEY` Actions secret and injected into the page by `.github/workflows/deploy.yml` at deploy time. The key is restricted to this site's address and the Places API (New) only.
