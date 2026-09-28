# CarLens – PWA v2 (scan history, share, alternatives)

## Run / test
1. Host these files over HTTPS (Netlify, Vercel, GitHub Pages, Firebase Hosting – all free).
2. Open the URL on your phone, tap ⚙ Settings, paste your Gemini API key.
   Get one at https://aistudio.google.com/apikey

## Make the APK
1. Go to https://www.pwabuilder.com and enter your hosted URL.
2. Package for Android -> download the APK/AAB.

## Security
The key is typed by the user and saved in localStorage on their device. Never hard-code
your own key into these files: anyone who unzips the APK can extract it.
