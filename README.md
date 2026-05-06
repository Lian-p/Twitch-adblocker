# 🛡️ Twitch Ad-Blocker – Anleitung

## Voraussetzungen
Installiere **[uBlock Origin](https://ublockorigin.com/de)** (⚠️ **nicht** Origin Lite).

---

## Einrichtung
1. Klicke auf das **uBlock Origin-Symbol** in der Browserleiste
2. Öffne die **Einstellungen** (Zahnrad-Icon)
3. Wechsle zum Tab **„Meine Regeln"**
4. Klicke auf **„Aus Datei importieren"** oder füge die Regeln manuell ein
5. Klicke auf **„Dauerhaft speichern"**

---

## Regeln

Füge folgende Zeilen ein:

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
