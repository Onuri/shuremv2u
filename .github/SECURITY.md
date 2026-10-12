# Security policy

## Supported versions

Only the latest release gets fixes. Update with `brew upgrade shurectl` or
`cargo install shurectl`.

## Reporting a vulnerability

Please don't open a public issue. Report it privately through
[GitHub's private vulnerability reporting](https://github.com/Humblemonk/shurectl/security/advisories/new).

Things worth reporting include:

- Anything that could make shurectl send a packet that damages or bricks a device
- Crashes or hangs caused by data a device sends back, or by a preset file
- Problems in the release pipeline, such as the Homebrew tap update

Include the shurectl version, the device model and firmware, your OS, and steps to
reproduce.
