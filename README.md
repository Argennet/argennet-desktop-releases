# ARGENNET Desktop Releases

This public repository distributes signed Windows Desktop update metadata and installer assets.

- The application source remains in the private `Argennet/argennet` repository.
- `releases.json` is the public update catalog consumed by installed Desktop clients.
- Versioned Windows installers are attached to GitHub Releases in this repository.
- Each catalog entry is validated by the application using Ed25519 signatures and SHA-256.
- Never upload source code, private signing keys, access tokens, or environment files here.

The catalog is intentionally empty until a release has passed installer and update validation.
