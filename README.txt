Radio Trainer - one installable web app (PWA) with both trainers

index.html   launcher with the two trainers
cw.html      CW (Morse) Trainer
exam.html    Radio Exam Trainer
cheatsheet.html  UK ham radio cheat sheet (two A4 pages, printable)
standalone/  the trainers and cheat sheet as plain single HTML files, unchanged.
             Open any straight from the folder in any browser.

Install: upload everything in this folder (not the zip) to a host such as
GitHub Pages, open the link on your phone or PC, then "Add to Home screen" /
"Install app". On Android, long-press the icon to jump straight to either trainer.

Updating: edit the files, change VERSION at the top of sw.js
(radio-trainer-v1 -> radio-trainer-v2) and upload again.

Test locally:  python -m http.server 8000   then open http://localhost:8000
