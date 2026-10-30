# StudySpace Class 10 — updated starter
## Run website
Install Node.js LTS, open terminal in this folder, run `npm install`, then `npm run start`. For hosting, run `npm run build` and publish the `dist` folder.
## Android
Run `npm install`, `npm run build`, `npx cap add android` (once), `npm run android:sync`, then `npm run android:open` and build from Android Studio.
## Admin
Admin code: `123123`. Upload PDFs or images (maximum 25 MB) against a subject, book and chapter. Student pages show download buttons for uploaded notes.
## Important
This is a working front-end starter. Notes are stored locally in the browser's IndexedDB and are not shared across phones. The admin code is a demo gate, not secure authentication. For a public multi-user release, add Firebase/Supabase authentication, cloud database and file storage with proper admin permissions. The chapter list is an NCERT-style starter; verify board/course and current CBSE syllabus before exam use.
