# .well-known

Repository to host assetlinks for web apps on the Google Play Store that don't have a custom domain.

## Development

1. The package name format is `repo-name.io.github.skedwards88.twa`
2. Upload the asset links to this repo
3. Upload the .aab package to Google Play Store
4. Since Google re-signs the app, after uploading the package go to `App integrity` > `Setup` > `App signing` to geh the new sha 256 fingerprint. Update the asset links in this repo with the new fingerprint.
