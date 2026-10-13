# Accidental Highlighter

Open a vector PDF score and highlight every note that has an accidental, including notes altered by the key signature. Highlights are saved as standard PDF annotations, so they can be removed here or in Acrobat, Preview or forScore.

Everything runs in your browser. Files are never uploaded.

## Use
Open the page, choose **Open PDF**, then toggle categories, click single notes, and save an annotated PDF, a clean PDF, or a note list.

## Limits
- Vector PDFs only (exported from Sibelius, Dorico, MuseScore, Finale, LilyPond, etc.). Scanned scores need OMR, which is not included.
- Ties are followed within a system only. Ottava lines are not handled.
- For scores with unusual music fonts, use **Symbols map** to assign roles.

## Hosting
Static single file. Enable GitHub Pages (Settings > Pages > Deploy from branch > `main` / root).

## Credits
Loads pdf.js (Apache-2.0) and pdf-lib (MIT) from cdnjs, and fonts from Google Fonts. The sample score is typeset with the Bravura font (c) Steinberg Media Technologies GmbH, SIL Open Font License 1.1.
