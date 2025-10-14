# egui_json_tree demo app

This demo demonstrates `egui_json_tree` and its capabilities in an `egui`/`eframe` app.

See various use cases implemented in the [/apps](https://github.com/dmackdev/egui_json_tree/tree/main/demo/src/apps) folder, which includes:

- Automatic expansion of arrays/objects and highlighting, based on search term matches.
- Copying JSON paths and values to the clipboard.
- A JSON editor UI.

View this demo online at <https://dmackdev.github.io/egui_json_tree>.

Run it locally via one of the commands below:

```bash
# Native target:
cargo run -p demo --release

# WASM/web target:
trunk serve --release --open
```
