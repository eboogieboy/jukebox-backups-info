# Jukebox Backups — public OAuth information website

This public repository contains **only the informational website** for the personal Jukebox Backups Google Drive OAuth client.

It never contains backup archives, Google OAuth credentials, private user data, a restic repository password, or Raspberry Pi SSH keys. Actual backup code and operational instructions remain in the private Jukebox environment and the `eboogieboy/jukebox` source repository.

## Pages

- `index.html` — application homepage and Google Drive usage explanation
- `privacy.html` — Google user-data access, storage, sharing, retention and revocation
- `terms.html` — personal-use terms and responsibility
- `style.css` — responsive accessible styling, no JavaScript or trackers

## Publishing

Use the GitHub repository **Settings → Pages → Build and deployment → Deploy from a branch → main / (root) → Save**.

Expected site URLs **once GitHub Pages has actually published**:

- Homepage: https://eboogieboy.github.io/jukebox-backups-info/
- Privacy policy: https://eboogieboy.github.io/jukebox-backups-info/privacy.html
- Terms: https://eboogieboy.github.io/jukebox-backups-info/terms.html

Google Cloud may additionally require verified ownership of the host's domain via Google Search Console before accepting an external production OAuth application. Do not claim a live site or authorised Google OAuth app until those steps have been verified.

## Privacy maintenance

Keep website copy accurate as the backup integration evolves; in particular, reflect the actual OAuth scopes selected and the enabled snapshot retention policy. Do not put tokens, user identities, personal emails or repository passwords in this public repo.
