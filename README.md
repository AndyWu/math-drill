# Math Drill

A timed, self-generating math practice test — multiplication, addition/subtraction, fractions, and mixed-operation calculations — with selectable topics and a local score history.

All data (name, answers, score history) stays in the browser via `localStorage`; nothing is sent to or stored on a server.

## Files

- `math-drill-standalone.html` — complete, self-contained page. Host this on any static web server (e.g. Apache), or just open it directly in a browser.
- `math-drill.html` — the same app as a body-only fragment, built for publishing as a Claude Artifact (the platform supplies its own `<head>`/wrapper around it). Not meant to be served directly.

## Author

Andy Wu — andycswu@gmail.com
