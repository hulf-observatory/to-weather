# to-weather

Redirects `weather.hyderabad.urbanobservatory.in`, the old Weather Dashboard, to the Weather and air page,
`https://hyderabad.urbanobservatory.in/live/weather/` (25 Oct 2026). The old app's paths have no match on the new
page, so every address lands on it. `404.html` is the same page, so deep links are caught too. GitHub Pages cannot
send server redirects, so this works in browsers only.
Takes effect once the `weather.hyderabad` DNS record at GoDaddy points at `hulf-observatory.github.io` (CNAME).
