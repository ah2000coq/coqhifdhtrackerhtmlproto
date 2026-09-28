SUNDAY QURAN CLASS - HIFDH TRACKER
==================================

Open index.html in Chrome, Edge or Safari. No internet or installation needed.

Pages
  index.html     Roster / class register
  register.html  Register a student
  profile.html   Student profile (edit, remove)
  progress.html  Hifdh progress - record new sabaq (surah + ayah range, or pages)
  murajah.html   Murajah progress - record revision (page to page, or surah to surah)
  history.html   Every entry for a student, with chart
  backup.html    CSV export, JSON backup/restore, demo data, erase

First time?  Any page with no students shows "Load demo students" -
one click and you can try everything.

Data is saved in the browser on this computer only. Keep all the .html
files together in one folder, and use Backup regularly.

Firefox, or data not carrying between pages?
  Firefox keeps a separate store for each local file. Either use Chrome/Edge,
  or run the included mini server (needs Node.js):
      node serve.js
  then open http://localhost:8080
