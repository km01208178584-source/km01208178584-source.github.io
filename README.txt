Pyramid Clinic TWA - GitHub Pages root-domain fix

IMPORTANT: The app URL is a GitHub Pages PROJECT site:
https://km01208178584-source.github.io/Clinic/

Digital Asset Links MUST be hosted at the DOMAIN ROOT, not inside /Clinic/:
https://km01208178584-source.github.io/.well-known/assetlinks.json

Therefore, upload the contents of this ZIP to the ROOT of the GitHub Pages USER SITE repository named:
km01208178584-source.github.io
Do not upload these files into the Clinic repository's /Clinic path and expect the domain-root URL to work.

This ZIP includes:
- .well-known/assetlinks.json
- _config.yml to make GitHub Pages/Jekyll include the hidden .well-known directory

After publishing, verify the exact URL above returns HTTP 200 and displays the JSON (not 404 or an HTML page). The JSON package name and signing certificate fingerprint were checked against the supplied signing.keystore.

Keep signing.keystore and its passwords private. Never upload them to GitHub.
