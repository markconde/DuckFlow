# TODOs for DuckFlow

## Near-term
- [ ] Introduce `Payload` object instead of raw strings between nodes.
- [ ] Add JSON Schema validation for node and pipeline configs.
- [ ] Improve logging: truncate long outputs at INFO, full output at DEBUG.

## Medium-term
- [ ] Support multiple service sections in `settings.json` (OpenAI, DuckDuckGo, Brave, etc).
- [ ] Add error propagation: store errors in payload instead of raising or returning strings.
- [ ] Auto-discover node functions in `node_functions/`.

## Longer-term
- [ ] Add async support for concurrent node execution.
- [ ] Add versioning to pipeline and node JSON configs.
