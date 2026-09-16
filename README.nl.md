[ 🌐 عربي ](README.ar.md) | [ 🇳🇱 Nederlands ](README.nl.md) | [ 🇪🇸 Español ](README.sp.md) | [ 🇬🇧 English ](README.md)

# Bouwkundige calculatie-software & aanbestedingsassemblage-bouwer

![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)
![Platform](https://img.shields.io/badge/Platform-Browser%20%2B%20Excel-green.svg)
![Category](https://img.shields.io/badge/Category-Construction%20Tech-orange.svg)

**Construction Tender Assembly Builder** is een browsergebaseerde applicatie en Excel-calculatiesjabloon die is ontworpen om de voorbereiding van bouwinschrijvingen te automatiseren, de hoeveelhedenstaat (BOQ) te beheren en kostencalculaties te standaardiseren.

Door historische ramingen om te zetten in herbruikbare bedrijfsactiva, verkort deze software voor bouwkundig calculeren de voorbereidingstijd van een inschrijving van weken naar uren. Beschikbaar als gratis webtool of als downloadbare Excel-werkbank voor professionele calculators en hoeveelhedenmeters.

> 🌐 **Free Web Version** → [*Open Estimating Software in Browser*](https://hyvoid.github.io/construction-estimating/)
> 
> 📥 **Excel Template** → [*Download Workbench*](https://theseusworkshop.com/l/prkvr?utm_source=github&utm_medium=GitHub%20README)

## Want to try it?

Dit project maakt deel uit van de Construction Toolkit.

Probeer deze en andere lichtgewicht bouwtools 30 dagen gratis — inclusief tools voor calculeren, inschrijven, jobkostenberekening en dagelijkse operaties.

→ [Try the Construction Toolkit](https://theseusworkshop.com/l/fqtoi/BIDSEASON?utm_source=github&utm_medium=GitHub%20portfolio)

---

# What It Helps You Track

## Overcoming Common Construction Estimating Challenges

Deze werkbank is gebouwd om de meest voorkomende knelpunten in **bouwkundige inschrijvingsvoorbereiding** en **kostentechniek** op te lossen:

*   **Preventing Scope Omissions in BOQ:** Stop met het verliezen van marge door vergeten posten. De aanbestedingmapping-engine kruisverwijst automatisch nieuwe hoeveelhedenstaten (BOQ) met historische databases om de volledigheid van de scope te waarborgen.
*   **Reusing Historical Construction Data:** Stop met het vanaf nul opbouwen van elke inschrijving. Zet eerdere projectramingen om in dynamische, herbruikbare assemblagebibliotheken (Assembly Builder) voor directe ontsluiting.
*   **Mitigating Labor Productivity Risks:** Vermijd verouderde arbeidstarieven. Pas dynamische productiviteitsaanpassingsfactoren toe op historische arbeidsgegevens om aan te sluiten bij de huidige werfomstandigheden en markttarieven.
*   **Standardizing Cost Codes (WBS):** Elimineer herwerk na de aanbesteding. Structureer uw ramingen automatisch met gestandaardiseerde kostencodes, zodat ze direct exporteerbaar zijn naar projectmanagementsoftware zoals Procore.

---

## How to Use the Estimating Workbench: Quick Start Guide

### 1. Setup Construction Cost Parameters
Open de werkruimte **Settings** om uw bedrijfsmatige calculatiebasis te definiëren. Stel gestandaardiseerde regels op voor uw inschrijvingen:
*   **Markup & Overhead:** Definieer doel brutomarges en percentages algemene kosten.
*   **Risk & Contingency:** Stel basisrisicoreserves in voor volatiele bouwmaterialen.
*   **Labor Productivity:** Pas regionale aanpassingsfactoren toe op bouwarbeidstarieven.
*   *Outcome:* Stel deze parameters één keer in om uw master-**kostenramingssjabloonkader** vast te leggen.

### 2. Import Bill of Quantities (BOQ) Data
Integreer uw bestaande aanbestedingsgegevens naadloos, zonder complexe databasemigratie. Plak ruwe data rechtstreeks uit externe takeoff-tools, boekhoudsystemen of klantdocumenten van adviseurs in de aangewezen werkbladen:
*   Tender BOQ (Bill of Quantities)
*   Subcontractor Schedule of Rates (SOR)
*   Material Quantity Takeoffs (QTO)

### 3. Automate Assembly Mapping & Cost Calculation
Schakel over naar de **Estimating Engine**. De werkbank voert automatisch de volgende logica uit:
*   Voert **BOQ-normalisatie** uit en koppelt nieuwe aanbestedingsregels aan uw historische bouwassemblages.
*   Berekent nauwkeurige arbeids-, materiaal- en materieelkosten op basis van uw vooraf gedefinieerde productiviteitsregels.
*   Genereert een aanbesteding-klaar **kostenramingsresultaat** met transparante uitsplitsing van risico en marge.
*   👉 [*Test the Automated Assembly Mapping in Browser*](https://hyvoid.github.io/construction-estimating/)

### 4. Build a Reusable Corporate Estimating Database
Gooi het bestand na indiening van de inschrijving niet weg. Uw nieuwe mappings en aangepaste WBS-assemblages (Work Breakdown Structure) worden direct opgeslagen in de **History Repository**. Het systeem evolueert met elke inschrijving en verandert eenmalige spreadsheets in een permanente **bouwkundige calculatiedatabase**.
*   👉 [*Download the Excel Estimating Workbench for Offline Use*](https://theseusworkshop.com/l/prkvr?utm_source=github&utm_medium=GitHub%20README)

---

# Who This Is For

Deze werkbank is ontworpen voor:

* Bouwkundig calculatoren
* Commercieel managers
* Hoeveelhedenmeters
* Aanbestedingsmanagers
* Kleine en middelgrote bouwbedrijven
* Aannemers die interne calculatiestandaarden opbouwen
* Organisaties die zich voorbereiden op een toekomstige Procore-implementatie

### Primary Use Cases

*   **Quantity Surveyors (QS) & Cost Engineers:** Valideer offertes van onderaannemers snel en voer nauwkeurige hoeveelhedenberekeningen uit tegen historische referentiewaarden.
*   **General Contractors (Main Contractors):** Standaardiseer het interne inschrijvingsproces over meerdere calculatieteams om commercieel risico te verkleinen.
*   **Commercial Managers:** Krijg direct inzicht in margeblootstelling, risicoreserves en toewijzing van algemene kosten vóór indiening van de inschrijving.

Er is geen spreadsheet-expertise vereist.

Open de browserversie of download de Excel-werkmap en begin direct met het opbouwen van herbruikbare calculatieassemblages.

---

## Why I Built This: The "Estimating Memory" Problem

Na het analyseren van honderden bouwinschrijvingen en het werken met commerciële teams, realiseerde ik me een fundamentele waarheid: **de meeste bouwbedrijven lijden niet aan een gebrek aan calculatiesoftware. Ze lijden aan een gebrek aan institutioneel calculatiegeheugen.**

In veel hoeveelhedenmeter- (QS) en calculatieteams ziet de voorbereiding van een inschrijving er nog steeds zo uit:

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

## Traditional Spreadsheets vs. Estimating Workbench

| Estimating Pain Points | Traditional Spreadsheet Methods | Workbench Automated Solution |
| :--- | :--- | :--- |
| **Bid Preparation Time** | Calculatoren besteden dagen aan het handmatig reconstrueren van WBS en assemblages voor vergelijkbare projecten. | Koppelt aanbestedingstructuren automatisch en hergebruikt bestaande assemblages binnen enkele uren. |
| **Cost Accuracy & Variance** | Grote variatie in ramingen afhankelijk van de ervaring van de individuele calculator. | Dwingt gestandaardiseerde kostenbibliotheken en bedrijfsmatige calculatieregels af. |
| **Data Knowledge Loss** | Bedrijfsprijsstelling gaat na indiening van de inschrijving verloren in geïsoleerde bestanden. | Historische assemblages worden permanente, doorzoekbare bedrijfsactiva. |
| **Margin & Risk Visibility** | Verborgen aannames over onvoorzien maskeren de werkelijke margeblootstelling tijdens inschrijvingsreviews. | Risico, onvoorzien en escalatielogica worden expliciet gescheiden van basiskosten. |

---


# About

Ik bouw lichtgewicht beslissingsondersteunende tools voor situaties waarin te veel variabelen spelen om betrouwbaar uit het hoofd te beheren.

De centrale vraag achter elke tool is:

> **Welke informatie moet op één plek bestaan om de volgende beslissing met vertrouwen te kunnen nemen?**

De Construction Tender Assembly Builder & Estimating Workbench is één voorbeeld van deze aanpak: het omzetten van gefragmenteerde calculatiekennis, historische projecten en kostenbibliotheken in een herbruikbaar operationeel beslissingssysteem.

---

# Technical Details

<details>
<summary>For technical reviewers, Excel practitioners, and collaborators</summary>

## Workbook Architecture

| Sheet                 | Function                       |
| --------------------- | ------------------------------ |
| 01_Settings           | Global estimating assumptions  |
| 02_Cost_Library       | Standardized cost database     |
| 03_Assembly_Library   | Reusable estimating assemblies |
| 04_Tender_Import      | Raw tender data                |
| 05_Tender_Mapping     | BOQ normalization and mapping  |
| 06_Assembly_Builder   | Assembly creation engine       |
| 07_Estimate_Engine    | Cost calculations              |
| 08_Risk_Margin        | Risk and pricing analysis      |
| 09_Tender_Output      | Tender deliverables            |
| 10_Procore_Export     | Budget export structures       |
| 11_History_Repository | Corporate estimating knowledge |
| 12_Dashboard          | Management reporting           |

### Data Flow

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

## Three Traps That Catch Even Experienced Estimators

### Trap 1 — Reusing Historical Estimates Without Scope Normalization

Er werd een beslissing genomen:

> Gebruik Project A als basis voor Project B.

De raming leunde op een onopgemerkte aanname:

> Er werd aangenomen dat de scopecategorieën identiek waren.

| Historical | New Tender |
| ---------- | ---------- |
| Excavation | Earthworks |
| Structural | Concrete   |
| Services   | MEP        |

Resultaat:

* 18% van de kosten werd weggelaten.

De redenering is onjuist omdat aanbestedingsterminologie zelden overeenkomt met operationele scopedefinities.

Juiste aanpak:

```text
Tender Item
      ↓
Scope Mapping
      ↓
Assembly Matching
      ↓
Cost Library
```

Juist resultaat:

* Volledigheid van de scope hersteld.
* Variatie in de raming aanzienlijk verminderd.

<details>
<summary>Formula Logic</summary>

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

### Trap 2 — Assuming Historical Productivity Remains Valid

Beslissing:

> Gebruik de arbeidstarieven en productiviteit van vorig jaar.

Onjuiste aanname:

> Productiviteit blijft constant.

Voorbeeld:

| Year     | Productivity |
| -------- | ------------ |
| Previous | 8 m²/hr      |
| Current  | 5.9 m²/hr    |

Resultaat:

* Arbeidskosten 35% te laag voorgesteld.

Juiste aanpak:

```text
Historical Productivity
       ×
Adjustment Factor
       ×
Current Conditions
```

Juist resultaat:

* Arbeidsramingen weerspiegelen de huidige marktomstandigheden.

<details>
<summary>Formula Logic</summary>

```excel
=Base_Productivity
* Adjustment_Factor

=Quantity
/ Adjusted_Productivity
```

</details>

---

### Trap 3 — Applying Margin Before Risk

Beslissing:

> Pas de doelmarge direct toe.

Onjuiste aanname:

> Risicoblootstelling is al weerspiegeld.

Resultaat:

```text
Cost = $10M
Margin = 10%
Bid = $11M
```

Niet-onderkend risico:

```text
Risk Exposure = $1.5M
```

Juiste aanpak:

```text
Base Cost
      +
Risk
      +
Contingency
      +
Margin
```

Juist resultaat:

```text
$10M + $1.5M + 10%
= $12.65M
```

<details>
<summary>Formula Logic</summary>

```excel
=Direct_Cost
+ Risk
+ Contingency

=Adjusted_Cost
* (1+Margin)
```

</details>

---

## Example Scenario

Een aannemer ontvangt een aanbesteding voor de uitbreiding van een ziekenhuis.

Invoer:

| Item                | Value |
| ------------------- | ----- |
| Tender Value        | $48M  |
| BOQ Items           | 1,240 |
| Historical Projects | 42    |
| Existing Assemblies | 680   |

Verwerking:

```text
1240 BOQ items
        ↓
892 auto-mapped
        ↓
278 assembly matches
        ↓
348 manual reviews
```

Ramingresultaat:

| Component      | Cost   |
| -------------- | ------ |
| Materials      | $19.4M |
| Labour         | $11.2M |
| Equipment      | $5.1M  |
| Subcontractors | $7.8M  |
| Overheads      | $1.6M  |
| Risk           | $1.9M  |

Definitieve inschrijving:

```text
Direct Cost:
$45.1M

Margin:
8%

Tender Price:
$48.7M
```

Operationele implicatie:

In plaats van drie weken te besteden aan het reconstrueren van historische ramingen, richt de calculator zich alleen op scope-uitzonderingen en commerciële strategie.

---

## Formula Reference

<details>
<summary>Assembly Mapping</summary>

```excel
XLOOKUP()
INDEX/MATCH()
TEXTAFTER()
TEXTBEFORE()
```

</details>

<details>
<summary>Estimate Calculation</summary>

```excel
SUMIFS()
SUMPRODUCT()
LET()
LAMBDA()
```

</details>

<details>
<summary>Risk Analysis</summary>

```excel
IF()
IFS()
CHOOSE()
SWITCH()
```

</details>

---

## Validation Rules

| Field          | Rule                     | Error Behavior     |
| -------------- | ------------------------ | ------------------ |
| Cost Code      | Must exist in library    | Validation warning |
| Assembly ID    | Must be unique           | Reject entry       |
| Quantity       | Greater than zero        | Highlight error    |
| Productivity   | Within accepted range    | Warning            |
| Margin         | Between 0–50%            | Reject             |
| Escalation     | Between -20% and +50%    | Warning            |
| Tender Mapping | Must resolve to assembly | Exception queue    |
| Procore Export | Valid WBS required       | Export blocked     |

</details>

---

# Other Tools in This Series

* **DTC Inventory Planning Workbench** — Assembly-style inventory planning and replenishment analysis.
* **Marketing Budget Allocation Simulator** — Scenario-based media budget optimization.
* **Project Time & Cost Analytics Console** — Labor allocation and profitability analysis.
* **VAT Compliance Calculation Workbench** — Cross-platform tax reporting and reconciliation.

Meer tools zijn beschikbaar via het GitHub-profiel en de release-repository.

---

# License

Dit project is gelicentieerd onder de **Apache License 2.0**.

Zie het LICENSE-bestand voor details.
