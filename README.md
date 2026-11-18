# Observability Flight Recorder

A dependency-free browser lab for synthetic performance marks, slow-task scenarios, trace identifiers, readable event logs, and privacy-safe JSON export.

## Run locally

Open `index.html` or serve the folder with `python3 -m http.server 4173`. No collector, endpoint, account, or network request is required.

## Study path

Record a normal synthetic event, inject a slow task, compare the visual timeline with the ordered list, and inspect the generated trace ID. Then read how a production system would need separate field data, logs, metrics, and traces.

## Inclusive behavior

The list is the source of truth. The canvas is supplemental, controls are keyboard accessible, status changes are announced politely, and the log can be cleared or exported without a visual gesture.

## Measurement boundary

This lab produces local synthetic observations. They are not CrUX, real-user monitoring, SEO scores, or production-health guarantees. Exported data contains only generated values.

## License

MIT. See `LICENSE`.
