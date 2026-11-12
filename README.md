# Aaditey Pashine site, export

Copy of the rebuilt site as it stood at 01:06 UTC on 12 Nov 2026.
Same version as the live Space link, after the calmer rug and shorter copy edits.

## Open it

Double-click `index.html`. It works on Mac and Windows, no server needed.
Keep `index.html` and the `assets` folder together.

## Edit it by hand

Open `index.html` in any text editor. Search for the text, change it, save, refresh.

- Colours: lines 18 to 23. `--bg` is the background, `--cream` is the main text, `--terra` is the orange accent.
- Hero line: line 169, `music &amp; more`.
- Listen line: line 178, `alternative fusion, bilingual music`.
- Listen links: lines 182 to 195, Spotify, Apple Music, SoundCloud.
- About: lines 200 to 202.
- Songs: lines 236 to 240.
- Photos: lines 213 to 225. Each photo is one `figure` block. To remove a photo, delete its whole `figure` block.
- Email in the footer: line 249.

To swap a photo, replace the file in `assets` with a file of the same name, or change the `src="assets/..."` name in the `figure` block.

## Note on the mic photo

`assets/portrait.jpg` is still in this export. It is the photo of Aadi singing into a mic in warm orange light, first photo in the photos section, caption "live". The stock mic on a desk (`studio.jpg`) was already removed from the site and is not included here.

If Aadi confirms that portrait should go too, delete its `figure` block at lines 212 to 215 in `index.html` and delete `assets/portrait.jpg`.

## Publish it

Wix cannot import this. Two easy routes:

1. Quickest: keep the live Space link and put it in the Instagram bio and as a button on the Wix site.
2. Own hosting: drag this whole folder onto Netlify Drop. It gives you a live link. Then point a domain at it if you have one, using the host's domain settings.

Do not edit the files in `workspace/ts-spaces/aaditey-pashine/` directly. That is the Space source. Edit this copy, or ask Basil to change the Space.
