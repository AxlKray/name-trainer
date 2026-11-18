# Name Trainer

A small, free web tool for teachers to learn their students' names quickly.

Load a class list as PDF (with photos and names). The tool turns it into
cards and lets you practise in four ways.

**Try it:** open the app and click **Load class list (PDF) → Try with example class**
(fictional names and cartoon pictures, from `example/example-class-list.pdf`).

## Modes

- **Flashcards**: see the photo, flip, mark "got it" or "again".
- **Quiz**: photo → pick the right name out of four (or name → photo).
  Every student has to be answered correctly twice.
- **Memory**: match photo and name pairs (4–15 pairs), with moves and time.
- **Typing**: type the first name; case, accents and one typo are forgiven.
  A hint reveals one letter at a time.
- **Students**: list with the share of correct answers per student, correct
  names, add a student who is not in the PDF (with a photo from the camera or a file), practise only the hard ones.

## More

- Learn "First L.", first name only, or first and last name.
  Students with the same first name automatically get their last-name initial.
- **Several classes** stored as tiles – practise one class or several together.
- PDF import detects photos, names and the header automatically; scanned lists
  work with a grid mode.

## Privacy

No login, no ads, no tracking – completely free.
Everything runs in the browser. Class lists, photos and statistics are stored only
in the browser's own local database (IndexedDB) on that device – not in the cache.
The PDF itself is not saved. Nothing is uploaded.

The PDF reader [pdf.js](https://github.com/mozilla/pdf.js) (Mozilla, Apache License 2.0)
is included in the folder `pdfjs`, so the app needs no external server.

## Hosting

Upload `index.html` **together with the folder `pdfjs`** to any web server, or
enable **GitHub Pages** for this repository (Settings → Pages → branch `main`, folder `/`).
If both tools run on the same website, they share the same class list library.

---

© 2026 AxlKray · Switzerland
