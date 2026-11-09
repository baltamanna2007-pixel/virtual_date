Edit all personal content in src/data.js (letters, songs, menu, bouquets, messages).
Open index.html in a browser (needs internet for song previews + fonts), or host the folder (Vercel/Netlify).
SONGS: each song keeps its Spotify link. The player looks the song up on Apple's free preview service (30-second clips) and plays it for real.
For FULL songs, put your mp3 files in an audio/ folder and add  audio:"audio/ruelle.mp3"  to that song in data.js.
ANIMALS: drawn as SVG. For real photos, replace the pet() images by adding PNGs with transparent background (see photos/README in app.js PHOTO map).
PHOTOS: add  photos:{golden:"photos/golden.png",corgi:"photos/corgi.png",kitten:"photos/kitten.png",sleepy:"photos/cat.png",guard:"photos/guard.png"}  to data.js (transparent PNGs) to replace the drawn animals with real photos.
