<div align="center">

<a href="README.md"><img src="assets/lang/en.svg" height="40" alt="English"/></a>&nbsp;<a href="README.de.md"><img src="assets/lang/de-active.svg" height="40" alt="Deutsch"/></a>&nbsp;<a href="README.ar.md"><img src="assets/lang/ar.svg" height="40" alt="العربية"/></a>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0A0A0A,55:047857,100:10B981&height=190&section=header&text=Stock%20Manager%20Pro&fontSize=52&fontColor=ffffff&animation=fadeIn&fontAlignY=46" width="100%" alt="Stock Manager Pro — professionelle Desktop-Bestandsverwaltung für Windows"/>

**Professionelle Desktop-Bestandsverwaltung für Windows**

Lokal-zuerst · barcode-fähig · Cloud-Synchronisierung über mehrere PCs · dreisprachig (EN / DE / AR)

[![Neueste Version](https://img.shields.io/github/v/release/Oranovix/stock-manager-pro?style=flat-square&label=Download)](https://github.com/Oranovix/stock-manager-pro/releases/latest)
[![Plattform](https://img.shields.io/badge/Plattform-Windows%2010%2F11-0078D6?style=flat-square&logo=windows)](https://github.com/Oranovix/stock-manager-pro/releases/latest)
[![Lizenz](https://img.shields.io/badge/Lizenz-Proprietär-blue?style=flat-square)](EULA.md)

[**⬇ Neuestes Installationsprogramm herunterladen**](https://github.com/Oranovix/stock-manager-pro/releases/latest) · [Funktionen](#-funktionen) · [Screenshots](#-screenshots) · [Editionen](EDITIONS.md) · [Änderungsprotokoll](CHANGELOG.md) · [Problem melden](https://github.com/Oranovix/stock-manager-pro/issues)

</div>

---

![Dashboard](assets/scr-dashboard.png)

## Überblick

Stock Manager Pro ist eine professionelle, lokal-zuerst arbeitende Desktop-Anwendung zur Bestandsverwaltung für kleine bis mittlere Reparaturwerkstätten, Einzelhandelsgeschäfte und Lager. Sie liefert eine vollständige Suite für den Geschäftsbetrieb — ein komplettes Kassenterminal (POS), den Lebenszyklus von Bestellungen, Inventuren, Preislisten, ein Lieferanten-CRM, Bestand über mehrere Standorte, **IMEI-genaue Verfolgung einzelner Telefone** und **14 gebrandete PDF-Berichte** — alles aufgebaut auf einer einfriersicheren asynchronen Engine mit einer sauberen, geschichteten Architektur. Die Daten bleiben standardmäßig lokal, mit **optionaler Cloud-Synchronisierung über mehrere PCs**, wenn Sie sie benötigen.

Entwickelt für echte Geschäfte, die genau wissen müssen, **was auf Lager ist, welchen Wert es hat und was heute verkauft wurde** — ohne Server, ohne Abonnement für die Cloud eines Anderen und ohne Internetverbindung.

- **Lokal-zuerst.** Ihre Daten liegen in einer Datenbankdatei auf Ihrem PC. Die App ist offline voll funktionsfähig. Sicherungen erfolgen mit einem Klick, und Exporte (CSV/JSON) sind jederzeit verfügbar.
- **Alles per Barcode.** Erstellen Sie Etiketten, scannen Sie mit jedem USB-Scanner und nutzen Sie den Quick-Scan-Ablauf für Wareneingang, Verkauf und Bestandsprüfungen.
- **Cloud-Synchronisierung über mehrere PCs** (Pro). Zwei oder mehr PCs teilen sich einen Live-Datensatz — der Ladentresen und das Backoffice sehen immer denselben Bestand.
- **Wirklich mehrsprachig.** Jeder Bildschirm in Englisch, Deutsch und Arabisch (volle RTL-Unterstützung), zur Laufzeit umschaltbar.

---

## ✨ Funktionen

### Kern-Inventar
- Einheitliches Inventar über Kategorien, Teiletypen, Telefonmodelle und Farbvarianten hinweg
- **Matrix-Rasteransicht** — tabellenartiger Massenbestand über Modell × Teiletyp × Farbe, mit fixierter Modellspalte, fixierten Kopfzeilen und Wertsummen pro Teiletyp
- **Telefoneinheiten (IMEI-Verfolgung)** — verfolgen Sie ganze Geräte einzeln per IMEI: Speicher, Zustand, Akku %, Ein-/Verkaufspreis, Status (auf Lager / verkauft / reserviert), Barcode-Etiketten, Verkaufshistorie und ein vollständiges Prüfprotokoll *(optionales Modul)*
- Bestand Ein / Aus / Anpassen mit zeitgestempelten Notizen und vollständigem Rückgängig / Wiederholen
- Mindestbestandsschwellen pro Artikel mit Echtzeit-Warnungen bei niedrigem Bestand
- Produktfotos, Ablaufdaten und Garantieverfolgung pro Artikel
- Barcode-Erstellung (Code128/EAN) und Abfangen von USB-Scanner-Eingaben

### Geschäftsmodule
| Modul | Highlights |
|---|---|
| **Verkauf / POS** | Warenkorb-basiertes Kassensystem, Kundensuche, Rabatte, PDF-Belege, Bearbeiten/Stornieren mit automatischer Bestandsrückbuchung |
| **Telefone (IMEI)** | Gerätebestand per IMEI — Bestandsraster Marke × Modell, Scan-zum-Verkauf, Reservierung, Barcode-Etiketten, Verkaufshistorie |
| **Bestellungen** | Lebenszyklus ENTWURF → GESENDET → TEILWEISE → EMPFANGEN, automatischer Wareneingang bei Empfang |
| **Retouren** | Aktionen WIEDEREINLAGERN oder ABSCHREIBEN, Erstattungsverfolgung, Verknüpfung mit Verkauf |
| **Lieferanten** | Lieferanten-CRM, Einkaufspreise, Lieferzeiten, verknüpfte Inventarartikel |
| **Preislisten** | Preiskonfigurationen erstellen, entwerfen, aktivieren und im Bulk anwenden |
| **Inventur** | Zyklusbasierter Vergleich von gezählter vs. System-Menge mit Abweichungsbericht |
| **Kunden** | Kundenprofile, verknüpft mit Verkaufs- und Einkaufshistorie |
| **Standorte** | Bestand über mehrere Standorte mit Umbuchungen zwischen Lagerpositionen |
| **Berichte** | 14 gebrandete PDF-Berichte — Inventar, Bewertung (zu Kosten), niedriger Bestand, Transaktionen, Verkäufe, Kategorieleistung, Inventur, **Telefonbestand & Verkaufshistorie**, Barcode-Etiketten und mehr |

### Plattform
- **Einfriersichere Oberfläche** — jede Datenbankoperation läuft außerhalb des Hauptthreads; die Oberfläche blockiert nie, unabhängig von der Datenmenge
- **Optionale Cloud-Synchronisierung** — teilen Sie einen Live-Datensatz über mehrere PCs; kein Server zu betreiben, pro Installation aktivierbar
- **Optionale Module** — geschäftsspezifische Funktionen (z. B. der Telefon-/IMEI-Tracker) sind pro Installation über Shop-Einstellungen → Module aktivierbar
- **Mehrsprachig** — Englisch, Deutsch (DE), Arabisch (AR) mit Live-Umschaltung und vollem RTL-Layout
- **Vier Themes** — Dunkel, Hell, Pro Dunkel (Smaragd/Anthrazit), Pro Hell (Smaragd/Weiß)
- **Excel-ähnlicher Zoom** — Strg+Scrollen / Strg+Plus/Minus Zoom (50–200 %) mit Fußzeilen-Schieberegler
- **Automatische Updates** — manifestbasierte Versionsprüfung mit SHA256-Verifizierung
- **Automatische Sicherung** — geplante Sicherung mit konfigurierbarer Aufbewahrung
- **Rückgängig / Wiederholen** — jede Bestands- oder Telefonstatus-Operation umkehren
- **Offline-zuerst** — lokale Datenbank (WAL), keine Telemetrie; Cloud-Synchronisierung ist strikt optional

---

## 📸 Screenshots

> Die Screenshots verwenden einen Demo-Datensatz.

### Analyse-Dashboard
Echtzeit-KPI-Karten (Bestandswert zu Kosten, Umsatz, Transaktionen, niedriger Bestand), ein Bestandsgesundheits-Donut, Wert-nach-Marke-Balken und eine Bewertungs-Pivot-Tabelle Marke × Teiletyp — alles asynchron außerhalb des UI-Threads geladen.

![Analyse-Dashboard](assets/scr-dashboard.png)

---

### Matrix-Ansicht
Der Kern-Arbeitsablauf — tabellenartiger Massenbestand über Modell × Teiletyp × Farbe, mit fixierter Modellspalte, Wertsummen pro Teiletyp und Filtern Niedrig / Ausverkauft / Nachbestellen.

![Matrix-Ansicht](assets/scr-displays.png)

---

### Inventar
Durchsuchbare, filterbare Produkttabelle mit KPI-Übersichtskarten (Einheiten, niedriger / kein Bestand, Inventarwert), Statusabzeichen und Inline-Schnellaktionen +1 / −1.

![Inventar](assets/scr-inventory-v2.png)

---

### Telefone — IMEI-Verfolgung
Gerätebestand, verfolgt per IMEI: ein Bestandsraster Marke × Modell nach Speicher, KPIs (gesamt / auf Lager / verkauft / Ø Akku / Bestandswert), Scan-zum-Verkauf, Reservierung und Barcode-Etiketten. *(Optionales Modul.)*

![Telefone](assets/scr-phones.png)

---

### Verkauf & POS
Warenkorb-basiertes Kassensystem mit Produktauswahl, Kundensuche, Rabatten, automatischen PDF-Belegen und Bearbeiten / Stornieren mit Bestandsrückbuchung.

![Verkauf & POS](assets/scr-sales.png)

---

### Berichte
14 professionelle, gebrandete PDF-Berichte für **Teile und Telefone** — Inventar, Bewertung (zu Kosten), niedriger Bestand, Transaktionen, Verkäufe, Kategorieleistung, Inventurblätter, Telefonbestand & Verkaufshistorie, ablaufender Bestand und Barcode-Etiketten.

![Berichte](assets/scr-reports.png)

---

### Transaktionen
Paginiertes Prüfprotokoll der Bestandsbewegungen mit einer Zusammenfassungsleiste EIN / AUS / ANPASSEN / Netto, entprellten Filtern und Mehr-laden-Paginierung.

![Transaktionen](assets/scr-transactions.png)

---

### Bestellungen
Vollständiger Bestell-Lebenszyklus von ENTWURF über GESENDET → TEILWEISE → EMPFANGEN. Der Empfang einer Bestellung löst automatisch einen Wareneingang aus.

![Bestellungen](assets/scr-purchase-orders.png)

---

### Lieferanten
Lieferanten-CRM mit Kontaktdaten, Bewertung, verknüpften Inventarartikeln und Anzahl offener Bestellungen pro Lieferant.

![Lieferanten](assets/scr-suppliers.png)

---

### Inventur
Zyklusbasierte Inventur mit artikelweiser Eingabe der Zählmenge, Abweichungsbericht System-vs.-Gezählt und einer Abschlusszusammenfassung.

![Inventur](assets/scr-audit.png)

---

### Preislisten
Erstellen und verwalten Sie Preiskonfigurationen; wenden Sie einen prozentualen Massenaufschlag an oder übertragen Sie eine Liste direkt in den Live-Bestand.

![Preislisten](assets/scr-price-lists.png)

---

### Retouren
Verarbeiten Sie Retouren mit Aktionen WIEDEREINLAGERN oder ABSCHREIBEN — kehrt die ursprüngliche Transaktion um und erfasst den Erstattungsbetrag.

![Retouren](assets/scr-returns.png)

---

### Quick Scan
Abfangen von USB-Barcode-Scanner-Eingaben mit Befehls-Barcodes (ENTNEHMEN / EINFÜGEN / BESTÄTIGEN) für freihändiges Zählen des Bestands.

![Quick Scan](assets/scr-quickscan.png)

---

### Barcode-Generator
Erstellen und exportieren Sie Code128- / EAN-Barcodes; drucken Sie Etiketten für neuen Bestand im Bulk.

![Barcode-Generator](assets/scr-barcode.png)

---

## 🖥️ Systemanforderungen

| | |
|---|---|
| **Betriebssystem** | Windows 10 oder Windows 11 (64-Bit) |
| **RAM** | 512 MB minimum · 2 GB empfohlen |
| **Speicher** | 250 MB Anwendung + Datenbankspeicher |
| **Administratorrechte** | Nicht erforderlich |
| **Internet** | Für den täglichen Gebrauch nicht erforderlich (Updateprüfung und Cloud-Synchronisierung sind optional) |

---

## Editionen

| | **Free** | **Pro** |
|---|---|---|
| Kern-Inventar, Matrix, Barcodes, POS | ✅ | ✅ |
| PDF-Berichte | 3 Kern | **Alle 14** |
| PCs / Cloud-Synchronisierung | 1 PC, lokal | **Mehrere PCs, geteilte Cloud** |
| Telefone / IMEI-Modul | — | ✅ |
| Bestellungen, Preislisten, Inventuren | Testphase | ✅ |

Vollständiger Vergleich und Zusagen: [EDITIONS.md](EDITIONS.md)

---

## 📦 Installation

1. [Laden Sie das neueste `StockManagerPro-x.y.z-setup.exe` herunter](https://github.com/Oranovix/stock-manager-pro/releases/latest)
2. Führen Sie das Installationsprogramm aus — bestehende Daten bleiben bei Updates erhalten
3. Die App prüft automatisch auf Updates; jede Version wird hier veröffentlicht

Die Daten werden unter `%LOCALAPPDATA%\StockPro\StockManagerPro\stock_manager.db` gespeichert — keine Administratorrechte, kein Konto, keine Internetverbindung für den täglichen Gebrauch erforderlich.

---

## 🚀 Schnellstart

| Aufgabe | Wie |
|---|---|
| Ersteinrichtung | Schließen Sie den Einrichtungsassistenten beim ersten Start ab |
| Produkt hinzufügen | `Strg+N` oder Schaltfläche **+ Produkt hinzufügen** |
| Bestand Ein | Produkt wählen → `Strg+I` |
| Bestand Aus | Produkt wählen → `Strg+O` |
| Bestand anpassen | Produkt wählen → `Strg+J` |
| POS öffnen | Zu **Verkauf / POS** navigieren → Neuer Verkauf |
| Barcode erstellen | Rechtsklick auf Produkt → Barcode erstellen oder `Strg+B` |
| PDF-Bericht exportieren | Zu **Berichte** navigieren oder `Strg+P` |
| Admin-Einstellungen | `Strg+Alt+A` oder das ⚙-Symbol in der Kopfzeile |
| Sprache wechseln | Sprachumschalter in der Kopfzeile (EN / DE / AR) |
| Letzte Operation rückgängig | Rechtsklick auf Transaktion → Rückgängig |
| Aktualisierung erzwingen | `F5` |

---

## 🏗️ Architektur

Stock Manager Pro basiert auf einer streng geschichteten Architektur mit einer einfriersicheren asynchronen Engine — die Oberfläche fragt die Datenbank nie direkt ab und blockiert nie.

```
┌──────────────────────────────────────────────────────────────┐
│  UI-Schicht  —  Seiten · Komponenten · Dialoge · Tabs · Controller │
├──────────────────────────────────────────────────────────────┤
│  Async-Engine  —  WorkerPool · DataWorker · UpdateWorker      │
├──────────────────────────────────────────────────────────────┤
│  Service-Schicht  —  Geschäftslogik (21 Services)             │
├──────────────────────────────────────────────────────────────┤
│  Repository-Schicht  —  reiner SQL-Datenzugriff (13 Repos)    │
├──────────────────────────────────────────────────────────────┤
│  Modell-Schicht  —  reine Domänen-Dataclasses (13 Modelle)    │
├──────────────────────────────────────────────────────────────┤
│  Kern-Schicht  —  Datenbank · Theme · i18n · Config · Logger  │
│  SQLite WAL · Schema V23 · 27 Tabellen · optionale Cloud-Sync │
└──────────────────────────────────────────────────────────────┘
```

**Einfriersichere Async-Engine** — jede Datenbankoperation wird über einen Worker-Pool mit gezielter Abbruchsteuerung und entprellten Filtereingaben außerhalb des Hauptthreads ausgeführt. Der Hauptthread wendet nur Ergebnisse an; er fragt nie ab. Theme-Änderungen werden auf den nächsten Ereignisschleifen-Tick verschoben, um jegliches Einfrieren beim Umschalten zu vermeiden.

**Optimierte Datenbank** — thread-lokaler Verbindungspool, Batch-Einfügungen, Leistungsindizes und abgestimmte Pragmas. Eine vollständige automatische Migrationskette (Schema V1 → V23) läuft bei jedem Start, sodass Upgrades nie manuelle Datenarbeit erfordern. 27 Tabellen decken Inventar, Verkäufe, Bestellungen, Retouren, Lieferanten, Kunden, Standorte, Inventuren, Preislisten, Telefone (IMEI) und deren Prüfprotokolle ab.

---

## 🛠️ Technologie-Stack

| Schicht | Technologie | Zweck |
|---|---|---|
| UI-Framework | **PyQt6** | Native Desktop-GUI |
| Datenbank | **SQLite 3** (WAL + FK) | Lokale relationale Speicherung |
| PDF | **fpdf2** + **PyMuPDF** | Berichte und Belege |
| Barcodes | **python-barcode** | Code128- / EAN-Erstellung |
| Bilder | **Pillow** | Produktfotos, Symbolverarbeitung |
| Paketierung | **PyInstaller** | Windows-Ausführbare Datei |

---

## ⌨️ Tastenkürzel

| Aktion | Kürzel | Aktion | Kürzel |
|---|---|---|---|
| Neues Produkt | `Strg+N` | Barcode erstellen | `Strg+B` |
| Bestand Ein | `Strg+I` | PDF-Bericht exportieren | `Strg+P` |
| Bestand Aus | `Strg+O` | Vergrößern / Verkleinern | `Strg+=` / `Strg+-` |
| Bestand anpassen | `Strg+J` | Zoom zurücksetzen | `Strg+0` |
| Suchen | `Strg+F` | Admin-Einstellungen | `Strg+Alt+A` |
| Produkt löschen | `Entf` | Aktualisierung erzwingen | `F5` |

---

## 🔒 Daten & Datenschutz

Alle Daten bleiben auf Ihrem Computer:

```
%LOCALAPPDATA%\StockPro\StockManagerPro\stock_manager.db
```

- Keine Internetverbindung erforderlich (Updateprüfung ist optional)
- Keine Telemetrie, kein Nutzer-Tracking; Cloud-Synchronisierung ist strikt optional (Ihre eigene Cloud-Datenbank)
- Vollständiges Prüfprotokoll jeder Bestandsbewegung
- Automatische Sicherung mit konfigurierbarer Aufbewahrung
- SQLite-WAL-Modus für Absturzsicherheit

---

## 📈 Versionen

Jede Version wird hier automatisch erstellt und veröffentlicht — Installationsprogramm, `update_manifest.json` (SHA256-verifiziert) und Änderungsprotokoll. Die vollständige Historie pro Version finden Sie in **[CHANGELOG.md](CHANGELOG.md)**.

| Meilenstein | Highlights |
|---|---|
| **2.7.x** | Härtung der Mehr-PC-Cloud-Synchronisierung, Replica-Rollen-Korrekturen, Automatisierung der Release-Pipeline |
| **2.6.x** | Korrektur der Cloud-Sync-Aktivierung, Genauigkeit der Dashboard-Bestandsgesundheit, aktualisierte Screenshots |
| **2.5.x** | 📱 Telefon-Modul (IMEI), optionale Cloud-Synchronisierung, 14 professionelle PDF-Berichte, Barcode-Korrekturen für deutsche Tastaturen |
| **2.3.x** | Einfriersichere Async-Engine, Controller-Refactoring, vollständige Geschäftssuite (POS, Bestellungen, Retouren, Lieferanten, Inventur, Preislisten, Kunden, Standorte) |
| **2.1 – 2.2** | Farbdimension in der Matrix, Barcode-Generator, Quick-Scan-Ablauf |
| **1.0.0** | Kern-Inventar, Barcode-Scannen, mehrsprachige Oberfläche, Offline-SQLite |

---

## Support

- 🐛 [Fehler melden](https://github.com/Oranovix/stock-manager-pro/issues/new?template=bug_report.md)
- 💡 [Funktion vorschlagen](https://github.com/Oranovix/stock-manager-pro/issues/new?template=feature_request.md)
- 💼 Kommerzielle Lizenzierung & Bereitstellung für mehrere Geschäfte: kontaktieren Sie [Oranovix](https://github.com/Oranovix)

---

## 📄 Lizenz

Stock Manager Pro ist kommerzielle Software © 2026 Oranovix / Abdullah Bakir.
Die Installationsprogramme auf dieser Seite sind unter dem [Endbenutzer-Lizenzvertrag](EULA.md) lizenziert.
Ihre Daten bleiben immer Ihre — Export, Sicherungen und Lesezugriff funktionieren in jeder Edition, lizenziert oder nicht.

---

<div align="center">

**[Download](https://github.com/Oranovix/stock-manager-pro/releases/latest)** · **[Fehler melden](https://github.com/Oranovix/stock-manager-pro/issues)** · **[Funktion vorschlagen](https://github.com/Oranovix/stock-manager-pro/issues/new?template=feature_request.md)**

Viel Erfolg bei der Bestandsverwaltung 🚀

</div>
