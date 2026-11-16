# Kaas Royale: afspraken voor Claude

Evelien maakt dit spel samen met haar zoon van 12. Hij speelt graag Fortnite en Kaasje (de app van de Bankzitters).

- Antwoord in het Nederlands, eenvoudig genoeg voor een 12-jarige. Commits ook in het Nederlands.
- Het hele spel staat in één bestand: `index.html` (canvas en JavaScript, geen frameworks, geen bestanden van buiten).
  Zo blijft het simpel.
- Houd de getallen om mee te spelen bovenaan in `INSTELLINGEN`, met een uitleg erbij. Codecommentaar in het Nederlands.
- Spelen kan via GitHub Pages: https://evelienvegter.github.io/kaas-royale/ (de branch `main` wordt automatisch gepubliceerd).
  Een push naar `main` zet een nieuwe versie online; vraag eerst of dat mag.
- Test na een wijziging: syntaxis en een korte simulatie zonder browser kan met JavaScriptCore
  (`/System/Library/Frameworks/JavaScriptCore.framework/Versions/A/Helpers/jsc`) en een nep-canvas.
  Controleer bij nieuwe obstakels of ze haalbaar zijn bij de begin- en de maximale snelheid, en tel per level
  welke obstakels er echt komen (een fout in `maakObstakel` maakte ooit van alles een boomstam).
- Een nieuw obstakel moet eerlijk zijn: altijd te ontwijken, met een hint de eerste keren.
