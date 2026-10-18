[ 🌐 عربي ](README.ar.md) | [ 🇩🇪 Deutsch ](README.de.md) | [ 🇫🇷 Français ](README.fr.md) | [ 🇳🇱 Nederlands ](README.nl.md) | [ 🇪🇸 Español ](README.sp.md) | [ 🇬🇧 English ](README.md)
# Baukalkulationssoftware & Tender-Assembly-Builder
<img width="1425" height="790" alt="image" src="https://github.com/user-attachments/assets/ae9b71b7-b444-4cc5-8caa-1b92d94af7f2" />

![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)
![Platform](https://img.shields.io/badge/Platform-Browser%20%2B%20Excel-green.svg)
![Category](https://img.shields.io/badge/Category-Construction%20Tech-orange.svg)

Der **Construction Tender Assembly Builder** ist eine browserbasierte Anwendung und eine Excel-Kalkulationsvorlage zur Automatisierung der Angebotserstellung im Bauwesen, zur Verwaltung von BOQ (Bill of Quantities / Leistungsverzeichnis) und zur Standardisierung von Kostenberechnungen.

Durch die Umwandlung historischer Kalkulationen in wiederverwendbare Unternehmensressourcen verkürzt diese Software zur Angebotskalkulation im Bauwesen die Zeit der Angebotserstellung von Wochen auf Stunden. Verfügbar als kostenloses Webtool oder als herunterladbare Excel-Workbench für professionelle Kalkulatoren und Quantity Surveyor.

> 🌐 **Kostenlose Web-Version** → [*Kalkulationssoftware im Browser öffnen*](https://hyvoid.github.io/construction-estimating/)
> 
> 📥 **Excel-Vorlage** → [*Workbench herunterladen*](https://theseusworkshop.com/l/prkvr?utm_source=github&utm_medium=GitHub%20README)

---

## Was es für Sie überwacht

## Überwindung häufiger Herausforderungen bei der Baukalkulation

Diese Workbench wurde entwickelt, um die häufigsten Engpässe bei der **Angebotserstellung im Bauwesen** und im **Kostenengineering** zu lösen:

*   **Vermeidung von Lücken im BOQ-Leistungsumfang:** Verlieren Sie keine Marge mehr durch übersehene Positionen. Die Ausschreibungs-Mapping-Engine gleicht neue Leistungsverzeichnisse (BOQ) automatisch mit historischen Datenbanken ab, um die Vollständigkeit des Leistungsumfangs sicherzustellen.
*   **Wiederverwendung historischer Baudaten:** Beginnen Sie nicht jedes Angebot von Null. Wandeln Sie vergangene Projektkalkulationen in dynamische, wiederverwendbare Assembly-Bibliotheken (Assembly Builder) für sofortigen Abruf um.
*   **Minimierung von Risiken der Arbeitsproduktivität:** Verwenden Sie keine veralteten Lohnsätze. Wenden Sie dynamische Produktivitätsanpassungsfaktoren auf historische Arbeitsdaten an, um aktuellen Baustellenbedingungen und Marktsätzen zu entsprechen.
*   **Standardisierung von Kostencodes (WBS):** Eliminieren Sie Nacharbeit nach der Angebotsabgabe. Strukturieren Sie Ihre Kalkulationen automatisch mit standardisierten Kostencodes, die sich sofort in Projektmanagement-Software wie Procore exportieren lassen.

---

## So verwenden Sie die Kalkulations-Workbench: Schnellstart-Anleitung

### 1. Einrichtung der baulichen Kostenparameter
Öffnen Sie den Arbeitsbereich **Settings**, um Ihre unternehmensweite Kalkulationsbasis zu definieren. Legen Sie standardisierte Regeln für Ihre Angebote fest:
*   **Aufschläge & Gemeinkosten:** Definieren Sie Ziel-Bruttomargen und Gemeinkostenprozentsätze.
*   **Risiko & Eventualität:** Legen Sie Basisrisikozuschläge für volatile Baumaterialien fest.
*   **Arbeitsproduktivität:** Wenden Sie regionale Anpassungsfaktoren für Baulohnsätze an.
*   *Ergebnis:* Legen Sie diese Parameter einmal fest, um Ihr Master-**Kostenkalkulations-Framework** zu etablieren.

### 2. Import von BOQ-Daten (Leistungsverzeichnis)
Integrieren Sie Ihre bestehenden Ausschreibungsdaten nahtlos ohne komplexe Datenbankmigration. Fügen Sie Rohdaten direkt aus externen Takeoff-Tools, Buchhaltungssystemen oder Beraterunterlagen des Auftraggebers in die dafür vorgesehenen Arbeitsblätter ein:
*   Tender BOQ (Bill of Quantities)
*   Subcontractor Schedule of Rates (SOR)
*   Material Quantity Takeoffs (QTO)

### 3. Automatisierung von Assembly-Mapping & Kostenberechnung
Wechseln Sie zur **Estimating Engine**. Die Workbench führt automatisch die folgende Logik aus:
*   Führt eine **BOQ-Normalisierung** durch und ordnet neue Ausschreibungspositionen Ihren historischen Baugruppen (Assemblies) zu.
*   Berechnet präzise Arbeits-, Material- und Gerätekosten auf Basis Ihrer vordefinierten Produktivitätsregeln.
*   Erzeugt ein ausschreibungsreifes **Kostenkalkulationsergebnis** mit transparenter Aufschlüsselung von Risiko und Marge.
*   👉 [*Automatisiertes Assembly-Mapping im Browser testen*](https://hyvoid.github.io/construction-estimating/)

### 4. Aufbau einer wiederverwendbaren unternehmensweiten Kalkulationsdatenbank
Verwerfen Sie die Datei nach der Angebotsabgabe nicht. Ihre neuen Mappings und benutzerdefinierten WBS (Work Breakdown Structure)-Assemblies werden direkt im **History Repository** gespeichert. Das System entwickelt sich mit jedem Angebot weiter und verwandelt Einmal-Tabellenkalkulationen in eine dauerhafte **Baukalkulationsdatenbank**.
*   👉 [*Die Excel-Kalkulations-Workbench für die Offline-Nutzung herunterladen*](https://theseusworkshop.com/l/prkvr?utm_source=github&utm_medium=GitHub%20README)

---

## Für wen dies gedacht ist

Diese Workbench ist konzipiert für:

* Baukalkulatoren
* Commercial Manager
* Quantity Surveyor
* Tender-Manager
* Kleine und mittlere Bauunternehmen
* Auftragnehmer, die interne Kalkulationsstandards aufbauen
* Organisationen, die sich auf eine künftige Procore-Implementierung vorbereiten

### Primäre Anwendungsfälle

*   **Quantity Surveyor (QS) & Kosteningenieure:** Schnelle Validierung von Subunternehmerangeboten und präzise Mengenermittlung anhand historischer Baselines.
*   **Generalunternehmer (Hauptauftragnehmer):** Standardisierung des internen Angebotsprozesses über mehrere Kalkulationsteams hinweg zur Reduzierung des kommerziellen Risikos.
*   **Commercial Manager:** Sofortige Transparenz über das Margen-Exposure von Angeboten, Risikozuschläge und Gemeinkostenverteilung vor der Angebotsabgabe.

Keine Tabellenkalkulations-Expertise erforderlich.

Öffnen Sie die Browser-Version oder laden Sie die Excel-Arbeitsmappe herunter und beginnen Sie sofort mit dem Aufbau wiederverwendbarer Kalkulations-Assemblies.

---

## Warum ich dies entwickelt habe: Das Problem des „Kalkulationsgedächtnisses"

Nach der Analyse hunderter Bauangebote und der Zusammenarbeit mit kommerziellen Teams erkannte ich eine grundlegende Wahrheit: **Die meisten Bauunternehmen leiden nicht wirklich an einem Mangel an Kalkulationssoftware. Sie leiden an einem Mangel an institutionellem Kalkulationsgedächtnis.**

In vielen Quantity-Surveying- (QS) und Kalkulationsteams sieht der Workflow der Angebotserstellung noch immer so aus:

```text
New BOQ Received
      ↓
Review Architectural Drawings
      ↓
Search Siloed Spreadsheets & Old Files
      ↓
Copy Previous Project Estimate
      ↓
Manually Modify Cost Rates
      ↓
Submit Tender (with hidden commercial risks)
```
---

## Traditionelle Tabellenkalkulation vs. Kalkulations-Workbench

| Kalkulations-Schmerzpunkte | Traditionelle Tabellenkalkulationsmethoden | Automatisierte Workbench-Lösung |
| :--- | :--- | :--- |
| **Zeitaufwand der Angebotserstellung** | Kalkulatoren verbringen Tage mit dem manuellen Wiederaufbau von WBS und Assemblies für ähnliche Projekte. | Ordnet Ausschreibungsstrukturen automatisch zu und wiederverwendet bestehende Assemblies in Stunden. |
| **Kostengenauigkeit & Abweichung** | Große Kalkulationsunterschiede je nach Erfahrung des einzelnen Kalkulators. | Erzwingt standardisierte Kostenbibliotheken und unternehmensweite Kalkulationsregeln. |
| **Verlust von Datenwissen** | Unternehmenspreiswissen geht nach der Angebotsabgabe in isolierten Dateien verloren. | Historische Assemblies werden zu dauerhaften, durchsuchbaren Unternehmensressourcen. |
| **Margen- & Risikotransparenz** | Verborgene Eventualitätsannahmen verdecken die tatsächliche Margen-Exposure bei Angebotsprüfungen. | Risiko-, Eventualitäts- und Eskalationslogik werden von den Basiskosten getrennt. |

---

## Über mich

Ich entwickle leichtgewichtige Entscheidungsunterstützungs-Tools für Situationen, in denen zu viele bewegliche Teile im Kopf zuverlässig zu managen sind.

Die zentrale Frage hinter jedem Tool ist:

> **Welche Informationen müssen an einem Ort vorhanden sein, um die nächste Entscheidung sicher zu treffen?**

Der Construction Tender Assembly Builder und die Kalkulations-Workbench sind ein Beispiel für diesen Ansatz: die Umwandlung fragmentierten Kalkulationswissens, historischer Projekte und Kostenbibliotheken in ein wiederverwendbares operatives Entscheidungssystem.

---

## Technische Details

<details>
<summary>Für technische Prüfer, Excel-Praktiker und Mitarbeiter</summary>

## Workbench-Architektur

| Sheet                 | Funktion                       |
| --------------------- | ------------------------------ |
| 01_Settings           | Globale Kalkulationsannahmen  |
| 02_Cost_Library       | Standardisierte Kostendatenbank |
| 03_Assembly_Library   | Wiederverwendbare Kalkulations-Assemblies |
| 04_Tender_Import      | Rohdaten der Ausschreibung    |
| 05_Tender_Mapping     | BOQ-Normalisierung und Mapping |
| 06_Assembly_Builder   | Assembly-Erstellungs-Engine   |
| 07_Estimate_Engine    | Kostenberechnungen            |
| 08_Risk_Margin        | Risiko- und Preisanalyse      |
| 09_Tender_Output      | Ausschreibungslieferungen     |
| 10_Procore_Export     | Budget-Exportstrukturen       |
| 11_History_Repository | Unternehmens-Kalkulationswissen |
| 12_Dashboard          | Managementberichte            |

### Datenfluss

```text
Tender Import
        ↓
Tender Mapping
        ↓
Assembly Builder
        ↓
Cost Library
        ↓
Estimate Engine
        ↓
Risk/Margin
        ↓
Tender Output
        ↓
Procore Export
```

---

## Drei Fallen, die auch erfahrene Kalkulatoren ereilen

### Falle 1 — Wiederverwendung historischer Kalkulationen ohne Scope-Normalisierung

Es wurde eine Entscheidung getroffen:

> Projekt A als Basis für Projekt B verwenden.

Die Kalkulation beruhte auf einer unbemerkten Annahme:

> Die Leistungsbereiche wurden als identisch angenommen.

| Historisch | Neue Ausschreibung |
| ---------- | ---------- |
| Aushub | Erdarbeiten |
| Tragwerk | Beton   |
| Haustechnik | MEP        |

Ergebnis:

* 18 % der Kosten wurden ausgelassen.

Die Begründung ist falsch, da die Terminologie von Ausschreibungen selten mit operativen Definitionen des Leistungsumfangs übereinstimmt.

Korrekter Ansatz:

```text
Tender Item
      ↓
Scope Mapping
      ↓
Assembly Matching
      ↓
Cost Library
```

Korrektes Ergebnis:

* Vollständigkeit des Leistungsumfangs wiederhergestellt.
* Kalkulationsabweichung deutlich reduziert.

<details>
<summary>Formellogik</summary>

```excel
=XLOOKUP(Tender_Item,
Mapping_Table[Tender],
Mapping_Table[Assembly])

=SUMIFS(Costs[Amount],
Costs[Assembly],
Current_Assembly)
```

</details>

---

### Falle 2 — Annahme, dass historische Produktivität weiterhin gültig bleibt

Entscheidung:

> Die Lohnsätze und die Produktivität des letzten Jahres verwenden.

Fehlerhafte Annahme:

> Die Produktivität bleibt konstant.

Beispiel:

| Jahr     | Produktivität |
| -------- | ------------ |
| Vorherig | 8 m²/hr      |
| Aktuell  | 5.9 m²/hr    |

Ergebnis:

* Arbeitskosten um 35 % unterschätzt.

Korrekter Ansatz:

```text
Historical Productivity
       ×
Adjustment Factor
       ×
Current Conditions
```

Korrektes Ergebnis:

* Arbeitskalkulationen spiegeln aktuelle Marktbedingungen wider.

<details>
<summary>Formellogik</summary>

```excel
=Base_Productivity
* Adjustment_Factor

=Quantity
/ Adjusted_Productivity
```

</details>

---

### Falle 3 — Anwendung der Marge vor dem Risiko

Entscheidung:

> Zielmarge direkt anwenden.

Fehlerhafte Annahme:

> Das Risiko-Exposure ist bereits berücksichtigt.

Ergebnis:

```text
Cost = $10M
Margin = 10%
Bid = $11M
```

Unerkanntes Risiko:

```text
Risk Exposure = $1.5M
```

Korrekter Ansatz:

```text
Base Cost
      +
Risk
      +
Contingency
      +
Margin
```

Korrektes Ergebnis:

```text
$10M + $1.5M + 10%
= $12.65M
```

<details>
<summary>Formellogik</summary>

```excel
=Direct_Cost
+ Risk
+ Contingency

=Adjusted_Cost
* (1+Margin)
```

</details>

---

## Beispielszenario

Ein Auftragnehmer erhält eine Ausschreibung für eine Krankenhauserweiterung.

Eingabe:

| Position                | Wert |
| ------------------- | ----- |
| Ausschreibungswert        | $48M  |
| BOQ-Positionen           | 1.240 |
| Historische Projekte | 42    |
| Bestehende Assemblies | 680   |

Verarbeitung:

```text
1240 BOQ items
        ↓
892 auto-mapped
        ↓
278 assembly matches
        ↓
348 manual reviews
```

Kalkulationsergebnis:

| Komponente      | Kosten   |
| -------------- | ------ |
| Material      | $19.4M |
| Arbeitskräfte | $11.2M |
| Geräte      | $5.1M  |
| Subunternehmer | $7.8M  |
| Gemeinkosten      | $1.6M  |
| Risiko           | $1.9M  |

Finales Angebot:

```text
Direct Cost:
$45.1M

Margin:
8%

Tender Price:
$48.7M
```

Operative Implikation:

Anstatt drei Wochen mit dem Wiederaufbau historischer Kalkulationen zu verbringen, konzentriert sich der Kalkulator nur auf Ausnahmen im Leistungsumfang und auf die kommerzielle Strategie.

---

## Formelreferenz

<details>
<summary>Assembly-Mapping</summary>

```excel
XLOOKUP()
INDEX/MATCH()
TEXTAFTER()
TEXTBEFORE()
```

</details>

<details>
<summary>Kalkulationsberechnung</summary>

```excel
SUMIFS()
SUMPRODUCT()
LET()
LAMBDA()
```

</details>

<details>
<summary>Risikoanalyse</summary>

```excel
IF()
IFS()
CHOOSE()
SWITCH()
```

</details>

---

## Validierungsregeln

| Feld          | Regel                     | Fehlerverhalten     |
| -------------- | ------------------------ | ------------------ |
| Kostencode      | Muss in der Bibliothek existieren    | Validierungswarnung |
| Assembly-ID    | Muss eindeutig sein           | Eintrag ablehnen       |
| Menge       | Größer als null        | Fehler hervorheben    |
| Produktivität   | Innerhalb des akzeptierten Bereichs    | Warnung            |
| Marge         | Zwischen 0–50 %            | Ablehnung             |
| Eskalation     | Zwischen -20 % und +50 %    | Warnung            |
| Tender-Mapping | Muss einer Assembly zugeordnet werden | Ausnahmenwarteschlange    |
| Procore-Export | Gültiges WBS erforderlich       | Export blockiert     |

</details>

---

## Weitere Tools dieser Serie

* **DTC Inventory Planning Workbench** — Assembly-basierte Bestandsplanung und Nachschubanalyse.
* **Marketing Budget Allocation Simulator** — Szenariobasierte Medienbudget-Optimierung.
* **Project Time & Cost Analytics Console** — Arbeitskräftezuteilung und Profitabilitätsanalyse.
* **VAT Compliance Calculation Workbench** — Plattformübergreifende Steuerberichterstattung und -abstimmung.

Weitere Tools sind über das GitHub-Profil und das Release-Repository verfügbar.

---

## Lizenz

Dieses Projekt ist unter der **Apache License 2.0** lizenziert.

Siehe die Datei LICENSE für Details.
