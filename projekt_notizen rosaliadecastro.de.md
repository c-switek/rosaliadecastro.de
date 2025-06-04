
# Projekt-Dokumentation: Wiederaufbau der Website rosaliadecastro.de mit GitHub Pages

## Ausgangslage

- Ursprüngliche Website: [rosaliadecastro.de](http://rosaliadecastro.de) (jetzt archiviert)
- Erreichbar über die Wayback Machine:  
  https://web.archive.org/web/20180420073418/http://rosaliadecastro.de
- Ursprünglich mit WordPress erstellt, gehostet bei Strato
- Durch PHP-Update 2017 unbrauchbar geworden
- Kein technischer Support ohne kostenpflichtigen Vertrag bei Strato → Kündigung
- Die Seite hatte akademisch-literarischen Anspruch und war im deutschsprachigen Raum einzigartig

## Ziel

Die Website soll:
- kostenlos
- werbefrei
- mit akademisch-literarischem Anspruch
- über die alte Domain rosaliadecastro.de
neu aufgebaut werden – mit Hilfe von **GitHub Pages**

## Bereits erledigte Schritte

- ✅ Neues GitHub-Konto erstellt
- ✅ Domain rosaliadecastro.de bei INWX.de registriert
- ✅ Neues Repository `rosaliadecastro.de` auf GitHub erstellt
- ✅ GitHub Pages unter `Settings > Pages` aktiviert
- ✅ CNAME-Datei erstellt mit Inhalt `rosaliadecastro.de`
- ✅ Erste Testdateien hochgeladen (`index.md`)
- ✅ Bild (Porträt) hochgeladen
- ✅ Farbschema nach Wunsch eingerichtet (schwarz, grün, blau)

## Häufige Fragen und Antworten

### Was ist das Hauptverzeichnis meines Repos?
→ Die zentrale Übersicht deiner Dateien unter  
`https://github.com/dein-benutzername/rosaliadecastro.de`  
Dort liegt alles, was online angezeigt wird.

### Was ist eine Commit Message?
→ Eine kurze Beschreibung der Änderung, z. B.:
- `Startseite erstellt`
- `CSS-Farben hinzugefügt`
- `Portrait hochgeladen`

### Was ist GitHub Pages aktivieren?
→ Das bedeutet, dass dein Repository als Website veröffentlicht wird.  
Zu finden unter `Settings > Pages`. Auswahl: Branch `main`, Ordner `/root`.

### Wie kann ich meine alte Seite rekonstruieren?
→ Inhalte (HTML, Texte, Bilder) aus der Wayback Machine kopieren und in neue `.md`- oder `.html`-Dateien auf GitHub einfügen.

### Wie bekomme ich mein Farbschema zurück?
→ Mit eingebettetem CSS z. B.:

```html
<style>
body {
  background-color: black;
  color: #00FF00;
}
h1 {
  color: #0000FF;
}
</style>
```

### Wie erstelle ich eine Subdomain?
→ Beispiel: `texte.rosaliadecastro.de`
1. Neues Repository `texte.rosaliadecastro.de` erstellen
2. CNAME-Datei darin mit Inhalt `texte.rosaliadecastro.de` anlegen
3. DNS-Eintrag bei INWX entsprechend setzen (CNAME)

## Startseiten-Beispiel (index.md)

```markdown
---
title: "Rosalía de Castro"
---

<style>
body {
  background-color: black;
  color: #00FF00;
  font-family: Georgia, serif;
  padding: 20px;
}
h1, h2 {
  color: #0000FF;
}
</style>

# Rosalía de Castro

![Porträt](rosalia_portrait.jpg)

Willkommen auf der literarisch-akademischen Website zu Rosalía de Castro.

> *„Dicen que no hablan las plantas...“*

Diese Seite wird gerade neu aufgebaut – mit Texten, Übersetzungen und historischen Materialien.
```

## Noch offen / Nächste Schritte

- [ ] HTML-Inhalte aus der Wayback Machine übernehmen
- [ ] Unterseiten strukturieren (z. B. `biografie.md`, `werke.md`)
- [ ] Inhalte und Übersetzungen einpflegen
- [ ] Weitere Bilder hochladen (aus Archiv)
- [ ] Subdomain `texte.rosaliadecastro.de` ggf. einrichten
- [ ] Impressum / Kontakt einfügen (z. B. als `kontakt.md`)

---

*Stand: Juni 2025*  
*Diese Datei wurde erstellt zur Dokumentation des Wiederaufbaus der literarisch-akademischen Website zu Rosalía de Castro.*
