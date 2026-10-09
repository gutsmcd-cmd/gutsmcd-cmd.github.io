# gutsmcd-cmd.github.io

The root of `https://gutsmcd-cmd.github.io/`.

- `/` redirects to the family site, [/free-apps/](https://gutsmcd-cmd.github.io/free-apps/).
- `/.well-known/assetlinks.json` is the Digital Asset Links file that lets the
  M@ Free Apps Android APKs (Trusted Web Activities, `io.github.gutsmcd.*`) open
  their web app full-screen, without a browser address bar.

Each app keeps living in its own repo and is served at `/<repo>/`; this repo
must never contain a folder with the same name as an app repo.

`.nojekyll` is required so GitHub Pages publishes the `.well-known` folder.
