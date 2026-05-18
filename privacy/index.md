---
title: Privacy Policy
layout: default
---

# Privacy Policy / Zásady ochrany osobních údajů

**Účinnost / Effective date:** 18. května 2026  
**Verze / Version:** 1.0

---

## 🇨🇿 Česká verze

### 1. O tomto dokumentu

Tyto zásady ochrany osobních údajů (dále jen "Zásady") popisují, jaké údaje zpracováváme prostřednictvím nástroje **PPC Analytics Assistant** (dále jen "Nástroj") a jak s nimi nakládáme v souladu s nařízením (EU) 2016/679 (GDPR) a zákonem č. 110/2019 Sb., o zpracování osobních údajů.

### 2. Správce osobních údajů

**Václav Matějček**  
IČO: [01340140]  
Sídlo: [Školní 260, 43163, Perštejn]  
Kontakt: [matejcek.v@gmail.com]

Provozovatel vystupuje pod značkou **Václav Matějček** a poskytuje služby v oblasti správy PPC kampaní jako zpracovatel osobních údajů pro klienty (dále jen "Klienti").

### 3. Co je Nástroj a co dělá

Nástroj je interní analytický asistent pro PPC specialisty. Slouží k:

- načítání výkonnostních dat z reklamních platforem Klientů,
- detekci anomálií a regresí ve výkonu kampaní,
- generování reportů a doporučení pro PPC specialisty,
- analýze vyhledávacích dotazů, kreativ a publik.

**Nástroj pracuje v režimu read-only** — neprovádí žádné automatizované změny v reklamních účtech (úpravy bidů, rozpočtů, kampaní). Veškeré rozhodování a změny provádí PPC specialista manuálně, na základě výstupů z Nástroje.

### 4. Jaké údaje Nástroj zpracovává

Nástroj prostřednictvím autorizovaných API přístupů zpracovává následující kategorie dat:

| Zdroj | Typ dat |
|-------|---------|
| **Google Ads API** | Výkonnost kampaní, klíčových slov, search terms, reklam, publik |
| **Sklik API (Seznam.cz, a.s.)** | Výkonnost kampaní, klíčových slov, reklam |
| **Meta Marketing API** | Výkonnost kampaní, ad setů, kreativ, publik |
| **Google Analytics Data API (GA4)** | Konverzní data, atribuce, segmenty publika |
| **BigQuery / Google Sheets API** | Agregovaná reportová data, pokud jsou autorizována |

**Nástroj nezpracovává:**
- Customer Match seznamy / nahraná publika obsahující PII (e-maily, telefonní čísla, jména)
- Raw data z Enhanced Conversions
- Osobní údaje koncových uživatelů reklamních systémů přímo

Zpracovávaná data jsou převážně agregovaná výkonnostní data, která sama o sobě obvykle nepředstavují osobní údaje ve smyslu GDPR. Pokud výjimečně zpracovávaná data (například search terms) obsahují identifikovatelné osobní údaje, jsou s nimi nakládáno v souladu s těmito Zásadami.

### 5. Účely zpracování a právní základ

| Účel | Právní základ (čl. 6 GDPR) |
|------|----------------------------|
| Plnění smluvních povinností vůči Klientům (správa kampaní) | čl. 6 odst. 1 písm. b) — plnění smlouvy |
| Optimalizace výkonu reklamních kampaní | čl. 6 odst. 1 písm. f) — oprávněný zájem Klienta |
| Reporting a komunikace s Klientem | čl. 6 odst. 1 písm. b) — plnění smlouvy |

### 6. Příjemci údajů a sub-processory

Při poskytování služby Nástroje využíváme následující sub-processory:

| Sub-processor | Účel | Sídlo | Záruky |
|---------------|------|-------|--------|
| **Anthropic, PBC** | LLM (Claude API) pro analýzu a interpretaci dat | USA | Standardní smluvní doložky (SCCs), DPA |
| **Google LLC** | Hostování Google Cloud služeb, Google Ads API | USA | Standardní smluvní doložky (SCCs), DPA |
| **GitHub, Inc.** | Hostování této stránky se Zásadami | USA | Standardní smluvní doložky (SCCs) |
| **Meta Platforms, Inc.** | Meta Marketing API | USA | Standardní smluvní doložky (SCCs) |
| **Seznam.cz, a.s.** | Sklik API | Česká republika | Smluvní vztah dle GDPR |

Aktuální seznam sub-processorů je možné kdykoliv vyžádat na kontaktní e-mail.

### 7. Mezinárodní předávání dat

Některé sub-processory mají sídlo mimo EU/EHP (zejména USA). Předávání je zajištěno na základě:

- Standardních smluvních doložek (SCCs) přijatých Evropskou komisí,
- Data Privacy Framework (kde je aplikovatelný),
- Doplňkových technických opatření (šifrování v přenosu i v klidu).

### 8. Doba uchovávání

| Kategorie dat | Doba uchování |
|---------------|---------------|
| Data zpracovávaná Nástrojem lokálně | **0 dnů** — Nástroj data neuchovává mimo aktivní session |
| Data odesílaná do Anthropic API | **7 dnů** (default, automatické mazání) |
| Reporty a výstupy uložené v interních systémech | Po dobu plnění smlouvy s Klientem, max. 3 roky |
| Logy a auditní záznamy | 12 měsíců |

### 9. Vaše práva

Pokud jste subjekt údajů, jehož data jsou Nástrojem zpracovávána, máte podle GDPR následující práva:

- **Právo na přístup** (čl. 15) — víte, jaká data zpracováváme
- **Právo na opravu** (čl. 16) — můžete žádat opravu nepřesných údajů
- **Právo na výmaz** (čl. 17) — "právo být zapomenut"
- **Právo na omezení zpracování** (čl. 18)
- **Právo na přenositelnost** (čl. 20)
- **Právo vznést námitku** (čl. 21)
- **Právo nebýt předmětem automatizovaného rozhodování** (čl. 22)
- **Právo podat stížnost** u Úřadu pro ochranu osobních údajů (ÚOOÚ, www.uoou.cz)

Pro uplatnění práv kontaktujte: [matejcek.v@gmail.com].

### 10. Bezpečnost

Implementujeme přiměřená technická a organizační opatření, zejména:

- API tokeny a credentials uloženy v secret manageru, nikdy v plaintext repozitáři
- Šifrování v přenosu (TLS 1.2+)
- Princip nejmenších privilegií (least privilege) pro API přístupy
- Read-only přístupy do reklamních účtů, kde je to možné
- Pravidelná rotace credentials

### 11. Změny těchto Zásad

Tyto Zásady můžeme aktualizovat v souvislosti s rozšířením Nástroje, změnou sub-processorů nebo legislativy. Aktuální verze je vždy dostupná na této URL. Verze a datum účinnosti jsou uvedeny v hlavičce dokumentu.

### 12. Kontakt

Pro jakékoliv dotazy ke zpracování osobních údajů:

**Václav Matějček**  
E-mail: [matejcek.v@gmail.com] 
Doručovací adresa: [Školní 260, 43163, Perštejn]

---

## 🇬🇧 English version

### 1. About this document

This Privacy Policy describes how the **PPC Analytics Assistant** tool (the "Tool") processes data, in compliance with Regulation (EU) 2016/679 (GDPR) and Czech Act No. 110/2019 Coll.

### 2. Data Controller

**Václav Matějček**  
Business ID (IČO): [01340140]  
Registered address: [Školní 260, 43163, Perštejn]  
Contact: [matejcek.v@gmail.com]

Operating under the **Václav Matějček** brand, providing PPC campaign management services as a data processor for clients (the "Clients").

### 3. What the Tool does

The Tool is an internal analytics assistant for PPC specialists. It serves to:

- retrieve performance data from Clients' advertising platforms,
- detect anomalies and performance regressions,
- generate reports and recommendations for PPC specialists,
- analyze search terms, creatives, and audiences.

**The Tool operates in read-only mode** — it performs no automated changes to advertising accounts (no bid, budget, or campaign modifications). All decisions and changes are performed manually by the PPC specialist based on Tool outputs.

### 4. Data processed by the Tool

| Source | Data type |
|--------|-----------|
| **Google Ads API** | Campaign, keyword, search term, ad, audience performance |
| **Sklik API (Seznam.cz, a.s.)** | Campaign, keyword, ad performance |
| **Meta Marketing API** | Campaign, ad set, creative, audience performance |
| **Google Analytics Data API (GA4)** | Conversion, attribution, audience data |
| **BigQuery / Google Sheets API** | Aggregated reporting data, when authorized |

**The Tool does NOT process:**
- Customer Match lists / uploaded audiences containing PII (emails, phone numbers, names)
- Raw Enhanced Conversions data
- Personal data of advertising end-users directly

Processed data is primarily aggregated performance data, which typically does not constitute personal data under GDPR. Where processed data (e.g., search terms) exceptionally contains identifiable personal information, it is handled in accordance with this Policy.

### 5. Purposes and legal basis

| Purpose | Legal basis (Article 6 GDPR) |
|---------|------------------------------|
| Fulfilling contractual obligations to Clients (campaign management) | Art. 6(1)(b) — contract performance |
| Optimizing advertising campaign performance | Art. 6(1)(f) — legitimate interest of the Client |
| Reporting and Client communication | Art. 6(1)(b) — contract performance |

### 6. Recipients and sub-processors

| Sub-processor | Purpose | Location | Safeguards |
|---------------|---------|----------|------------|
| **Anthropic, PBC** | LLM (Claude API) for data analysis and interpretation | USA | SCCs, DPA |
| **Google LLC** | Google Cloud, Google Ads API | USA | SCCs, DPA |
| **GitHub, Inc.** | Hosting of this Policy page | USA | SCCs |
| **Meta Platforms, Inc.** | Meta Marketing API | USA | SCCs |
| **Seznam.cz, a.s.** | Sklik API | Czech Republic | GDPR contract |

A current list of sub-processors is available upon request.

### 7. International data transfers

Some sub-processors are based outside the EU/EEA (notably the USA). Transfers are safeguarded by:

- Standard Contractual Clauses (SCCs) adopted by the European Commission,
- Data Privacy Framework (where applicable),
- Supplementary technical measures (encryption in transit and at rest).

### 8. Data retention

| Data category | Retention period |
|---------------|------------------|
| Data processed locally by the Tool | **0 days** — Tool does not store data outside active session |
| Data sent to Anthropic API | **7 days** (default, automatic deletion) |
| Reports stored in internal systems | For contract duration, max. 3 years |
| Logs and audit records | 12 months |

### 9. Your rights

As a data subject under GDPR, you have the following rights:

- **Right of access** (Art. 15)
- **Right to rectification** (Art. 16)
- **Right to erasure** (Art. 17) — "right to be forgotten"
- **Right to restriction of processing** (Art. 18)
- **Right to data portability** (Art. 20)
- **Right to object** (Art. 21)
- **Right not to be subject to automated decision-making** (Art. 22)
- **Right to lodge a complaint** with the Czech DPA (ÚOOÚ, www.uoou.cz)

To exercise these rights, contact: [matejcek.v@gmail.com].

### 10. Security

We implement appropriate technical and organizational measures, including:

- API tokens and credentials stored in a secret manager, never in plaintext repositories
- Encryption in transit (TLS 1.2+)
- Principle of least privilege for API access
- Read-only access to advertising accounts where possible
- Regular credential rotation

### 11. Changes to this Policy

This Policy may be updated to reflect Tool expansion, sub-processor changes, or legislation. The current version is always available at this URL. Version and effective date are shown in the document header.

### 12. Contact

For any questions about personal data processing:

**Václav Matějček**  
E-mail: [matejcek.v@gmail.com]  
Postal address: [Školní 260, 43163, Perštejn]

