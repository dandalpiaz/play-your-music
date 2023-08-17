
# Drive Music Player

Play your music files stored in Google Drive.

## Todo

- Use blobs for audio (fix demos, play sequencing, test FF, dynamic mimetype)
- Intro text - can use "root"
- Re-create g-app, no api key, document process here, per-user quota
- Gapless playback using two audio elements
- New access token after an hour?
- Host to GH pages (custom domain?), allow domain in g-app
- Add legal links
- Simple analytics (generate authed url)
- Service worker / PWA / manifest?
- Publish g-app and request verification

### Later

- Add link to GH repo?
- Get audio files in chunks (byte range) for quicker start?
- Scrollbar styles (FF, Safari)
- File picker examples? Use lesser scope?
- Could grab artworks? Add art loop in api query
- Use React audio player?
- Start caching api content, if needed
- Styles for native audio player in Safari
- Light mode? Alternative [styles](https://cdnjs.com/libraries/github-markdown-css)

## Local Development

Run `python3 -m http.server` to start a local web server. 

## References

- [Googel Drive API - JavaScript Quickstart](https://developers.google.com/drive/api/quickstart/js)
- [Google Drive API - Downloading Files](https://developers.google.com/drive/api/v3/manage-downloads)
- [Google Drive API - Token Requests](https://developers.google.com/identity/oauth2/web/guides/use-token-model)
- [Google Drive API - JavaScript Authorization](https://developers.google.com/identity/oauth2/web/reference/js-reference)
- [Google Drive API - Scopes](https://developers.google.com/drive/api/guides/api-specific-auth)
- [React audio player example](https://codesandbox.io/s/react-w877cp)

