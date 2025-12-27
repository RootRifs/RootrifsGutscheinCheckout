# Gutscheincode Eingabe im letzten Bestellschritt

![Shopware v6.6.x – v6.7.x](https://img.shields.io/badge/Shopware-v6.6.x--v6.7.x-blue?style=for-the-badge&logo=shopware)
![License](https://img.shields.io/badge/license-MIT-green?style=for-the-badge)

Erweitert den Shopware-Checkout um ein zusätzliches Gutscheincode-Eingabefeld im letzten Bestellschritt. Ideal, wenn der Code erst spät zur Hand ist oder im Warenkorb vergessen wurde.

## 🚀 Funktionen

* **Gutschein-Feld im Checkout:** Code-Eingabe direkt vor dem Abschluss der Bestellung ("Zahlungspflichtig bestellen").
* **Bessere Usability:** Reduziert Kaufabbrüche durch ein fehlendes oder leicht zu übersehendes Gutscheinfeld im Standard-Warenkorb.
* **Nahtlose Integration:** Fügt sich optisch perfekt in den Shopware 6 Standard-Checkout ein.
* **Kompatibel:** Voll unterstützt für Shopware Versionen **6.6.x bis 6.7.x**.

## 🛠 Installation

### Per Composer (Empfohlen)

Öffne dein Terminal im Shopware-Wurzelverzeichnis und führe folgenden Befehl aus:

```bash
composer require rootrifs/gutschein-checkout
bin/console plugin:refresh
bin/console plugin:install --activate RootrifsGutscheinCheckout
```

### Manuelle Installation (ZIP-Datei)

Falls du Composer nicht nutzt, kannst du das Plugin auch klassisch als ZIP-Datei installieren. Lade dazu die aktuellste Version von [rootrifs.de/plugins](https://rootrifs.de/plugins) herunter.

#### Weg A: Über die Shopware Administration (Einfachster Weg)
1. Logge dich in dein Shopware Backend ein.
2. Navigiere zu **Erweiterungen > Meine Erweiterungen**.
3. Klicke auf den Button **Erweiterung hochladen**.
4. Wähle die heruntergeladene `RootrifsGutscheinCheckout.zip` aus.
5. Suche das Plugin in der Liste und klicke auf **Installieren** und anschließend auf den Schalter zum **Aktivieren**.

#### Weg B: Manuell per FTP/SFTP
1. Entpacke die ZIP-Datei auf deinem Rechner.
2. Kopiere den entpackten Ordner `RootrifsGutscheinCheckout` in das Verzeichnis `custom/plugins/` deiner Shopware-Installation.
3. Leere ggf. den Cache und installiere das Plugin


## 💡 Vorteile

* **Höhere Conversion-Rate:** Klare und schnelle Eingabemöglichkeit im entscheidenden Moment.
* **Keine Template-Anpassungen:** Installation ohne manuelles Ändern von Theme-Dateien.
* **Native Logik:** Nutzt die Standard-Gutscheinlogik von Shopware für maximale Stabilität.

## 📞 Support & Kontakt

Hast du Fragen oder benötigst Unterstützung bei der Einrichtung?

* **Website:** [rootrifs.de](https://rootrifs.de/plugins)
* **Kontakt:** [Kontaktformular](https://rootrifs.de/kontakt)
* **GitHub:** [Repository](https://github.com/RootRifs/RootrifsGutscheinCheckout.git)

---
Erstellt mit ❤️ von **RootRifs**.