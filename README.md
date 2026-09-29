# A little love letter for Martha

## Run locally

```sh
npm install
npm run dev
```

## Personalize the media

- Add Martha’s original portrait as `public/images/martha.jpg`. To use a different filename, edit `MARTHA_PHOTO` in `src/media.js`. The page uses the same image in the hero, memory card, and lightbox; adjust `object-position` in `src/style.css` if needed.
- Add a royalty-free instrumental MP3 as `public/audio/romantic-piano.mp3` for the music player. Playback begins only after the Play music button is pressed. The player shows a prompt for the missing file when it is not present.

The hero, memory card, and lightbox use this local image path; no stock or generated photos are used.
