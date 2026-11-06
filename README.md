# VIBE

    npm install
    npm run dev      # development
    npm run build    # production build into dist/

Deploy: push to GitHub, then on Netlify import the repo (netlify.toml is included).

Music: tracks stream from SoundHelix demo songs (algorithmic music, free to use; https://www.soundhelix.com).
If a URL fails, the app falls back to a built-in synthesized demo sound.
To use your own songs, edit `u:` in the `T` array in src/main.ts (or put mp3 files in `public/` and use "/name.mp3").
