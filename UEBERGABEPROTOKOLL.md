# 🗣️ NOCH BESPRECHEN

# Übergabeprotokoll — Kongress-Seite „UNVERWECHSELBAR"

**Stand:** 07.07.2026
**Projekt:** UNVERWECHSELBAR · Deutschlands Zukunftsplattform im KI-Zeitalter
**Art:** Kostenloser Online-Kongress für den Mittelstand · **17.–19. November 2026**

> 🗣️ **Status: NOCH BESPRECHEN** — Inhalte, Ablauf und offene Punkte müssen noch gemeinsam besprochen werden. Nichts hier ist final.

---

## 1. Alle Links

| Zweck | Link |
|-------|------|
| 🌐 **Live-Kongress-Seite** | https://claudiaconen.github.io/Unverwechselbar-Zukunftsplattform/?v=2 |
| 📝 **Direkt zur Anmeldung** (Anker) | https://claudiaconen.github.io/Unverwechselbar-Zukunftsplattform/#anmelden |
| 🎤 **„Speaker werden"-Seite** | https://claudiaconen.github.io/Unverwechselbar-Zukunftsplattform/speaker.html |
| 📩 **Speaker-Bewerbung** (Anker) | https://claudiaconen.github.io/Unverwechselbar-Zukunftsplattform/speaker.html#bewerben |
| 💻 **GitHub-Repository** | https://github.com/claudiaconen/Unverwechselbar-Zukunftsplattform |

## 2. Seitenstruktur

Der Kongress besteht aus **2 Seiten** (statisches HTML, gehostet über **GitHub Pages**):

1. **`index.html`** — Kongress-Landingpage mit Anmeldebereich
   - Titel: „UNVERWECHSELBAR · Deutschlands Zukunftsplattform im KI-Zeitalter"
   - Zielgruppe: Coaches, Selbstständige, Unternehmer, Start-ups, Mittelstand, Entscheider
   - Anmeldebereich als Anker `#anmelden` („Kostenlos anmelden" / „Ja, ich sichere mir meinen Platz")
   - Hinweis: begrenzte Live-Plätze (erste 500)

2. **`speaker.html`** — „Speaker werden · Mittelstands-Kongress"
   - Bewerbungsbereich als Anker `#bewerben`

## 3. Aktueller Status

- ✅ Landingpage + Speaker-Seite online (GitHub Pages)
- ✅ Anmelde- und Bewerbungsbereich als Seitenanker vorhanden
- ⚠️ **Anmeldeformular ist noch nicht an ein Backend angebunden** (kein `form action` / kein Ziel für die Daten hinterlegt) — Anmeldungen werden aktuell **nicht** irgendwo gespeichert/versendet.

## 4. Noch zu besprechen / offene Punkte

- [ ] **Anmeldeformular anbinden** — wohin sollen die Anmeldungen gehen? (E-Mail, Newsletter-Tool, Zapier, Google-Formular …?)
- [ ] Zahlungs-/Ticketing nötig, oder bleibt der Kongress komplett kostenlos?
- [ ] Speaker-Bewerbungen — wohin sollen die Daten laufen?
- [ ] Finaler Programm-/Ablaufplan der 3 Kongresstage
- [ ] Datenschutz & Impressum für die Kongress-Seite ergänzen
- [ ] Eigene Domain statt github.io-Adresse?

## 5. Technik / Weiterarbeiten

- Reines HTML, kein Build-Prozess. Lokal per Doppelklick auf `index.html` öffnen.
- Änderungen: committen und zu GitHub pushen → GitHub Pages aktualisiert die Live-Seite automatisch.
- `?v=2` in der URL ist ein Cache-Buster (erzwingt frische Version im Browser).

---
*Erstellt als Übergabestand. Status: NOCH BESPRECHEN.*
