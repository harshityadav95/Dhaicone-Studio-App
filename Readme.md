# Dhaicone Studio

Static dark-theme feature website and public binary release destination for [Dhaicone Studio](https://github.com/solvePao/Dhaicone-Studio).

Open `index.html` or serve this directory with `python3 -m http.server`. There are no image assets, external fonts, dependencies, or build step. The footer automatically displays the current year and `solvepao research`.

GitHub Pages publishes the website when `main` changes. GitHub's configured account domain determines the live Pages URL.

## Downloads

[GitHub Releases](https://github.com/harshityadav95/Dhaicone-Studio-App/releases) contains Xcode Cloud-built, Developer ID-signed, notarized DMGs after a successful release. `main` source builds publish previews; `prod` publishes stable releases and the Homebrew cask.

```sh
brew tap solvePao/tap
brew install --cask dhaicone-studio
```

The cask is available in the tap and tracks production Cloud releases. Requires Apple Silicon and macOS 15 or later.

## TestFlight

The source repository's `testflight` and `prod` branches archive the `DhaiconeStudio TestFlight` scheme in Xcode Cloud. Internal testing is managed through App Store Connect. A public TestFlight invitation will be linked here after external beta review and public-link configuration are complete.

See [release setup](https://github.com/solvePao/Dhaicone-Studio/blob/main/docs/RELEASES.md) for branch routing, build numbers, and verification.
