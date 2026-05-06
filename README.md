# 🛡️ Twitch Ad-Blocker – Anleitung

## Voraussetzungen
Installiere **[uBlock Origin](https://ublockorigin.com/de)** (⚠️**nicht** Origin Lite).
> **⚠️Hinweis:** Funktioniert nicht auf Chrome – [Arc](https://arc.net/) ist sowieso die bessere Wahl.

---

## Einrichtung
1. Klicke auf das **uBlock Origin-Symbol** in der Browserleiste
2. Öffne die **Einstellungen** (Zahnrad-Icon)
3. Wechsle zum Tab **„Meine Regeln"**
4. Lade [ublock-dynamische-regeln.txt herunterladen](https://github.com/Lian-p/Twitch-adblocker/raw/refs/heads/main/ublock-dynamische-regeln.txt) und importiere sie über „Aus Datei importieren"
6. Klicke auf **„Dauerhaft speichern"**

---

## Regeln
```
no-cosmetic-filtering: www.twitch.tv true
no-large-media: behind-the-scene false
behind-the-scene * * noop
behind-the-scene * 1p-script noop
behind-the-scene * 3p noop
behind-the-scene * 3p-frame noop
behind-the-scene * 3p-script noop
behind-the-scene * image noop
behind-the-scene * inline-script noop
```
