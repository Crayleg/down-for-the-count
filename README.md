# Takeaway Knockout

Can't decide? Type anything ("takeaway near Tuart Hill WA", "colours to paint the bedroom", "movies for a cosy night in"), pick 10, 20 or 30, and Gemini (free tier) builds the list. Then the knockout strikes options off one by one until a winner is left.

The API key is never committed. It's stored as the `GEMINI_API_KEY` Actions secret and injected into the page by `.github/workflows/deploy.yml` at deploy time. The key lives in its own free Google Cloud project and is restricted to `https://crayleg.github.io/*` and the Gemini API only.
