# Koydo Anvil Releases

Signed release binaries for the Koydo Anvil mobile testing platform — drivers,
SDKs, Docker images.

Live dashboard: https://anvil.koydo.app

## Artifacts

Each GitHub Release contains:

- The signed platform binary (`.ipa`, `.apk`, `.tar.gz`, etc.)
- A cosign v3 signature bundle alongside each binary
- The ephemeral cosign public key used to sign the release (`cosign.pub`)
- Debug symbols (`.dSYM.zip`) for iOS builds

See each release's notes for install + verification commands.

## License

Proprietary. Koydo internal dogfooding. Not distributable externally until the
first public App Store / TestFlight build (`v0.1.0`).
