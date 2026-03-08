# 🛠 AI App Builder Registry
Detta repository fungerar som en levande utvärdering av AI-verktyg för apputveckling. Syftet är att snabbt kunna avgöra vilket verktyg som är bäst lämpat för specifika projektbehov.

## 🗺 Navigeringsguide
* 📊 **[Jämförelsematris](#-jämförelsematris)** – Snabb överblick av kapabiliteter.
* 📁 **[Detaljerade Verktygsguider](./tools/)** – Djupdykning i varje plattform.
* 🏗 **[Workflows](#-workflows)** – Hur verktygen bäst kombineras.
* ➕ **[Lägg till nytt verktyg](#-instruktion-för-påfyllnad)** – Mall för nya entries.

---

## 📊 Jämförelsematris (Mars 2026)

| Verktyg | Fokus | Stack | UI-Kvalitet | Backend-stöd |
| :--- | :--- | :--- | :--- | :--- |
| **[Lovable](./tools/lovable.md)** | Fullstack MVP | React + Supabase | ⭐⭐⭐⭐⭐ | Högt (Supabase) |
| **Bolt.new** | Web-native dev | Vite + Remix | ⭐⭐⭐⭐ | Medium |
| **v0.dev** | UI/Frontend | Next.js + Shadcn | ⭐⭐⭐⭐⭐ | Lågt (UI-fokus) |
| **Cursor** | Proffskodning | Valfri | ⭐⭐⭐ | Obegränsat |

---

## 🏗 Workflows
Här beskrivs hur olika verktyg samverkar i utvecklingskedjan:

* **Idé & UI-skiss:** Använd **v0.dev** för att snabbt ta fram specifika komponenter.
* **Prototyping & Backend:** Importera komponenter till **Lovable** för att sätta upp databas och autentisering.
* **Skalning & Refactoring:** Exportera koden från Lovable till GitHub och öppna i **Cursor** för avancerad logik.

---

## ➕ Instruktion för påfyllnad
Använd följande mall när du lägger till ett nytt verktyg i mappen `/tools/`:

### Mall: [Verktygsnamn]
* **Kategori:** (Low-code / Pro-code / UI-only)
* **Styrkor:** Vad gör det unikt?
* **Hinder:** Vad saknas?
* **Kostnad:** Prismodell.
* **Personligt omdöme:** (Datum + betyg 1–10).
