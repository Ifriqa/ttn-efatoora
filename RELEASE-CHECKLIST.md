# Release Checklist

Before publishing a public release:

- [ ] Build Windows MSI.
- [ ] Generate Tauri updater artifact and `.sig` file.
- [ ] Prepare release assets with `scripts/prepare-tauri-release.mjs`.
- [ ] Verify `latest.json` points to the versioned MSI.
- [ ] Verify `latest-stable.json` points to the stable latest MSI.
- [ ] Verify `SHA256SUMS.txt` contains all release assets.
- [ ] Sign the MSI with MG Nova Technology certificate when available.
- [ ] Check installer on a clean Windows VM.
- [ ] Upload all assets to GitHub Releases.
- [ ] Link the stable MSI from https://ifriqa.com/products/ttn-efatoora only when ready for public launch.
