# StockWatcher

Manage Ayoub’s personal stock watchlist in this checkout. It is independent of CarBuzz and ValNet.

- GitHub Pages publishes `index.html` from the root of `main`.
- Keep the app dependency-free. The watchlist, Matrix, Dip Radar and Focus Desk share the same page.
- Before pushing, serve this checkout with `python3 -m http.server 8000` and exercise the affected views in a browser with real quote data.
