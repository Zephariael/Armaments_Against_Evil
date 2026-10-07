ARMAMENTS AGAINST THE EVIL ONE - home-screen app
===============================================

What is in this folder
  index.html             the app itself (all 100 readings are inside it)
  manifest.webmanifest   name, colours and icons for the home screen
  sw.js                  lets the app open with no internet
  icons/                 the candle icons

1. PUT IT ONLINE (free, about ten minutes, once)
   An app like this has to live on a real website (https). GitHub Pages is free.
   a. Make a free account at github.com.
   b. Click "New repository". Name it, for example: armaments. Choose Public. Create.
   c. Click "uploading an existing file". Drag in index.html, manifest.webmanifest,
      sw.js and the whole icons folder. Click "Commit changes".
   d. Open Settings > Pages. Under "Build and deployment", choose
      "Deploy from a branch", branch "main", folder "/ (root)". Save.
   e. Wait a minute or two. The page shows your address, for example:
      https://yourname.github.io/armaments/
   Note: a GitHub Pages site is public. Anyone with the link can open it.

2. PUT IT ON HER IPHONE
   a. Open the address in Safari.
   b. Tap the Share button (square with an arrow), then "Add to Home Screen", then Add.
   c. Open it once from the new candle icon while online. After that it works
      with no internet, and it shows a new reading every day.

3. CHANGING THE TEXT LATER
   Edit index.html, then in sw.js change  armaments-v8  to  armaments-v9  (and so on).
   Upload both. Her phone picks up the new copy the next time she opens it online.
