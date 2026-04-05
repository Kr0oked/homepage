# homepage

Source code for [philipp-bobek.de](https://philipp-bobek.de) — a personal portfolio and privacy policies for the
[Compass](https://play.google.com/store/apps/details?id=com.bobek.compass) and
[Metronome](https://play.google.com/store/apps/details?id=com.bobek.metronome) Android apps.

## Tech stack

Pure HTML + [Bootstrap 5](https://getbootstrap.com/) + [Bootstrap Icons](https://icons.getbootstrap.com/), all loaded
via CDN. No build step.

## Development

```bash
python3 -m http.server 8080 --directory docs
```

Then open [http://localhost:8080](http://localhost:8080).

## Deployment

GitHub Pages serves the `docs/` folder on the `master` branch.
