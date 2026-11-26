# Simplii releases

The Simplii installer and desktop app download from here. This repo holds no code, only release files:

- `latest.json`: the signed update list for the desktop app.
- `simplii-desktop-<version>.exe`: the app itself.
- the signed install list that `simplii-setup.exe` reads.

Every list is signed with an Ed25519 key that lives outside all repositories. The app refuses a list whose signature, expiry or SHA-512 does not match, so a file changed here by hand is never installed.

Stable addresses (always the newest release):

- `https://github.com/GOC-Productions/simplii-releases/releases/latest/download/latest.json`
