## What and why

<!-- What changes for the user, and why. Link the issue if there is one. -->

## Devices affected

<!-- Which models does this touch? If a control now looks or behaves differently on
one model than another, name the models and say why (see "Cross-Device UI
Consistency" in AGENTS.md). -->

- [ ] MVX2U Gen 1
- [ ] MVX2U Gen 2
- [ ] MV6
- [ ] MV6 Gen 2
- [ ] MV7
- [ ] MV7+

## How it was tested

- [ ] Verification gate passes (`cargo clippy --features probe -- -D warnings && cargo build --all-targets --features probe && cargo fmt --check && cargo test`)
- [ ] Checked in `--demo` for every affected model
- [ ] Tested on real hardware: <!-- model, firmware version, OS -->

## Protocol changes

<!-- Delete if this PR doesn't touch protocol.rs or device.rs. -->

- [ ] New or changed byte values come from a usbmon capture or probe run (attach or describe it)
- [ ] Roundtrip test added in `protocol.rs`
- [ ] README device support table updated
