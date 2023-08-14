
# Drive Music Player

Play your music files stored in Google Drive.

## Todo

- Redo how track grabs audio (test other account)
- Host to GH pages (no custom domain), allow domain in g-app
- Check tab accessibility (details focus on load)
- Move focus to next track on track end
- Create documentatian on Google API setup, rename app? No API key needed?
- Gapless playback using two audio elements
- Match other browser native audio player?
- New access token after an hour?
- Simple analytics (generate authed url)
- Service worker / PWA / manifest?
- Add legal links, link to GH repo
- Publish g-app and request verification

### Later

- Catch refresh w/ JS, warn about reauth
- Scrollbar styles
- File picker examples? Use lesser scope?
- Temporarily store access token to keep alive on refresh?
- Could grab artworks?
- Use React audio player?

## Local Development

Run `python3 -m http.server` to start a local web server. 

## References

- [JavaScript Quickstart for Google Drive API](https://developers.google.com/drive/api/quickstart/js)
- [Google API key restrictions](https://cloud.google.com/docs/authentication/api-keys#api_key_restrictions)
- [React audio player example](https://codesandbox.io/s/react-w877cp)
- https://stackoverflow.com/questions/11103582/how-do-you-detect-when-html5-audio-has-finished-playing-more-than-once
- https://developers.google.com/identity/oauth2/web/reference/js-reference
- https://developers.google.com/identity/oauth2/web/guides/use-token-model
- https://developers.google.com/drive/api/guides/api-specific-auth
