# StudySpace Class 10 — updated starter

## Run website
Install Node.js LTS, open terminal in this folder, run `npm install`, then `npm run start`. For hosting, run `npm run build` and publish the `dist` folder.

## Android
Run `npm install`, `npm run build`, `npx cap add android` (once), `npm run android:sync`, then `npm run android:open` and build from Android Studio.

## Admin
Admin code: `123123`. Upload PDFs or images (maximum 25 MB) against a subject, book and chapter. Student pages show compact rounded note cards, image previews, an animated in-app download confirmation and a download-arrow button. Each download gets a unique filename to avoid the browser's "download again?" duplicate-file prompt in normal cases.

## Important — online sharing
This version still stores admin uploads in the current browser's IndexedDB. That means uploaded notes are **not automatically visible to other students online**. To make every uploaded note public to everyone, connect a cloud backend such as Firebase or Supabase (with secure admin authentication and public read access), or add the note files to the website repository and publish them. Do not put private service keys in `index.html`.

The browser saves downloads to the device's download location. A website cannot force Android Chrome to save directly into the Gallery; image visibility in Gallery depends on the phone's download/media settings. The admin code is a demo gate, not secure authentication. Verify the board/course and current CBSE syllabus before exam use.
