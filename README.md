# Homepage Balthasar Waylab

Diese Dateien reichen für eine Seite auf GitHub Pages.

- `index.html` ist die ganze Seite (Layout, Texte und Skript in einer Datei)
- `.nojekyll` sagt GitHub, dass nichts umgebaut werden muss

## Veröffentlichen in fünf Schritten

1. Auf github.com einloggen und oben rechts auf das Plus klicken, dann «New repository». Name zum Beispiel `balthasar-mobilitaet`, Sichtbarkeit «Public», dann «Create repository».
2. Im neuen Repository auf «uploading an existing file» klicken. `index.html` und `.nojekyll` hineinziehen und mit «Commit changes» speichern.
3. Auf «Settings», dann links auf «Pages». Bei «Source» «Deploy from a branch» wählen, Branch `main`, Ordner `/ (root)`, dann «Save».
4. Nach ein bis zwei Minuten erscheint oben die Adresse, meist `https://DEINNAME.github.io/balthasar-mobilitaet/`.
5. Eine eigene Adresse wie `balthasar-mobilitaet.ch` kaufst du bei einem Schweizer Anbieter. Bei «Custom domain» in den Pages-Einstellungen trägst du sie ein. Die Anleitung des Anbieters nennt die DNS-Einträge.

## Vor dem Start ausfüllen

Ganz unten in `index.html` stehen im Skript fünf Einstellungen.

| Einstellung | Was hinein muss |
|---|---|
| `CONTACT_MAIL` | Geschäftliche E-Mail-Adresse |
| `ADDRESS` | Postadresse für das Impressum, Privatadresse oder Postfach |
| `HOSTING` | Bleibt bei GitHub Pages. Bei einem Schweizer Anbieter dessen Namen eintragen |
| `FORM_ENDPOINT` | Adresse eines Formulardienstes, zum Beispiel von Formspree. Leer lassen, dann kopieren Besucher den Text und senden ihn selbst per E-Mail |
| `LEGAL_DRAFT` | Auf `false` setzen, sobald Impressum und Datenschutz juristisch geprüft sind |

Der Name der HSLU steht bewusst nicht auf der Seite. Klär das mit der HSLU, bevor du sie nennst.

## Hinweise

- Das Repository ist öffentlich. Lege dort keine privaten Dokumente ab.
- Die Schriften laden von Google Fonts. Das steht in der Datenschutzerklärung. Wer das nicht will, hostet die Schriften selbst.
- Impressum und Datenschutz sind Entwürfe und keine Rechtsberatung.
