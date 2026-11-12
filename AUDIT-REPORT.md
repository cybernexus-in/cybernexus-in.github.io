# CyberNexus Website Content Audit Report
**Date:** 12 November 2026
**Auditor:** Claude (AI-assisted)
**Scope:** Factual accuracy, legal compliance, responsible content presentation

---

## A. VERIFIED CONTENT RETAINED

| Item | Source | Status |
|------|--------|--------|
| 1930 is India's National Cyber Crime Helpline | i4c.mha.gov.in | VERIFIED |
| CFCFRMS facilitates coordination with banks | i4c.mha.gov.in (initiative.aspx) | VERIFIED |
| I4C is attached office under MHA | i4c.mha.gov.in | VERIFIED |
| NCRP at cybercrime.gov.in | cybercrime.gov.in | VERIFIED |
| Samanvaya platform for cybercrime data sharing | i4c.mha.gov.in | VERIFIED |
| CFCFRMS saved >₹11,158 crore across >32.80 lakh complaints (till 30.06.2026) | PIB PRID 2287674 (user-supplied; PIB returned 403 on verification) | ATTRIBUTED TO MHA |
| N-DISC: 14,064+ cases | PIB PRID 2287674 | ATTRIBUTED TO MHA |
| RBI 3 working day zero liability (current framework) | RBI/2017-18/15, 6 July 2017 | VERIFIED |
| RBI 5 calendar day zero liability (from 1 Jan 2027) | RBI/2026-27/167, 24 June 2026 | VERIFIED |
| Downloading malicious apps = customer negligence (new RBI framework) | RBI amendment para 4(20C)(iv) | VERIFIED |
| Compensation: 85% of net loss or ₹25,000, once in lifetime | RBI amendment para 76T | VERIFIED |
| CERT-In 6-hour reporting applies to organisations, not individual victims | CERT-In Directions 28 April 2022 | VERIFIED |
| BSA Section 63(4) certificate from device custodian, not just forensics firm | Bharatiya Sakshya Adhiniyam 2023 | VERIFIED |
| DPDP Act partially in force; full enforcement by 13 May 2027 | MeitY / official timeline | VERIFIED |

## B. INCORRECT CONTENT CORRECTED

| Original Statement | Issue | Correction |
|---|---|---|
| "from device to courtroom" | Implies guaranteed court admissibility | Changed to "& digital forensics" |
| "Tracking 3 live C2 databases" | Unverified "live" claim | Changed to "Independent cyber fraud investigation" |
| "determine exactly what was compromised" | Overpromises certainty | Changed to "Assess potentially exposed information" |
| "Section 63 BSA compliant documentation - ready for FIR filing" | Claims compliance; overpromises | Changed to "supporting documentation relevant to applicable BSA requirements. Admissibility is determined by the competent court" |
| "We help you file complaints... coordinate with local cyber police stations" | Implies police coordination power | Changed to "Help organising information, preparing complaints... does not register FIRs, exercise police powers or act as legal counsel" |
| "They register your complaint and use CFCFRMS to freeze the scammer's bank account" | 1930 doesn't personally freeze accounts | Changed to "CFCFRMS facilitates coordination with banks for financial intervention" |
| "RBI limits customer liability for unauthorized transactions reported within 3 working days" | Oversimplified; doesn't apply to all scenarios; changes in 2027 | Replaced with full RBI comparison section with both regulatory periods |
| "Within 3 days" for police FIR | Invented universal deadline | Changed to "Follow up" |
| "NCFL weeks to months backlog" | Unsupported generalisation about government | REMOVED - replaced with factual government infrastructure section |
| "Google database access takes weeks" | Unsupported claim | REMOVED |
| "Files chargesheet with basic complaint" | Disparaging government without evidence | REMOVED |
| "Cannot cross-reference scammer networks" | Unsupported claim about police capability | REMOVED |
| "<2% conviction rate" | Unverified statistic | REMOVED |
| "60.8% fraud (NCRB 2021)" | Outdated; NCRB 2024 is latest | REMOVED |
| "Most cyber crimes go unreported" | Unquantified claim | REMOVED |
| "278 devices", "1,553 forms", "370 cards" etc. | Unverified internal statistics displayed publicly | REMOVED - replaced with "Statistics require internal evidence verification" |
| LIVE badges on all 3 databases | Cannot verify continuous monitoring | Changed to "Under investigation" |
| Victim case studies with age, region, financial details | Identifying combinations; consent not verified | Replaced with anonymised fraud scenario patterns |
| Phone numbers, Telegram usernames, names, IPs, panel logins | Personal identifiers publicly displayed | REMOVED - replaced with aggregated anonymised indicators |
| "Scammer network map" | Labels individuals as criminals | Changed to "Threat infrastructure correlation" |
| "Stolen data recovery" skill label | Overpromises | Changed to "Data exposure assessment" |
| "Bank account reset" skill label | Misleading | Changed to "Banking security assistance" |
| "OSINT & scammer tracing" | Labels individuals | Changed to "OSINT & threat investigation" |
| "FIR & cyber cell filing" | Implies power to file FIRs | Changed to "Complaint preparation" |
| "Court-ready evidence" | Overpromises admissibility | Changed to "Digital forensic reporting" |
| "Every case on this site is real and backed by forensic evidence" | Cannot independently verify | Changed to factual description of what CyberNexus does |
| "All evidence preserved for law enforcement" | Unverifiable claim | Changed to proper disclaimer |
| "cybernexus report --format court-ready" (terminal) | Overpromises | Changed to "--format forensic" with "evidence hashes" |
| "Forensic evidence package generated. Ready for filing." | Overpromises | Changed to "Technical forensic report generated with evidence hashes" |

## C. UNVERIFIED CONTENT REMOVED OR HIDDEN

| Item | Reason | Action |
|---|---|---|
| All database-specific statistics (devices, forms, cards, SMS, OTPs, clients) | No internal evidence documentation provided | HIDDEN - note says "require internal evidence verification" |
| Live Firebase data fetching JavaScript | Publicly fetches from scammer databases; statistics unverified | REMOVED entirely |
| 5 victim case studies with personal details | No consent verification; identifying combinations | REPLACED with anonymised scenario patterns |
| 8 partially-redacted phone numbers | Public personal identifiers | REMOVED |
| Telegram usernames (@lalu829298, @Union_1209_bot) | Public personal identifiers | REMOVED |
| Telegram IDs (8233836584, 8582331009) | Public personal identifiers | REMOVED |
| IP addresses (152.59.XXX.XXX, 47.31.XXX.XXX) | Approximate; cannot establish identity | REMOVED |
| Name "Sonu Kumar" | Public personal identifier | REMOVED |
| Panel login "bill1000z" | Operational access information | REMOVED |
| "Operating region: Bihar-Jharkhand corridor" | Based on approximate IP geolocation | REMOVED |
| "Full unredacted data shared with cybercrime.gov.in" | Cannot verify submission occurred | REMOVED |
| N-DISC as I4C component | Not found on I4C public website (found in PIB) | KEPT with MHA/PIB attribution |

## D. ITEMS REQUIRING OWNER VERIFICATION BEFORE PUBLICATION

### D1. Database Statistics
**What's needed:** For each of the 3 databases, provide:
- Source of data and date of collection
- Collection method and authorisation basis
- Whether records are unique or duplicated
- Whether data is historical or currently active
- Whether personal data is involved
- Evidence documentation (screenshots, hashes, timestamps)

**Current state:** Statistics are hidden with a note. Once documented, they can be restored with proper labels (e.g. "Historical analysis — collected [date]" instead of "LIVE").

### D2. Victim Case Studies
**What's needed:** For each case to be published:
- Documented supporting evidence
- Appropriate consent from the victim
- Anonymisation review (no identifying combinations of age + region + dates + financial exposure)

**Current state:** Replaced with generic fraud scenario patterns. Real cases can be added back with proper documentation.

### D3. MHA/PIB Statistics
**What's needed:** Verify PIB PRID 2287674 figures independently (our automated check returned HTTP 403). The figures are currently displayed with explicit MHA attribution.

### D4. Malware Variant Details
**What's needed:** For each variant to display full analysis:
- SHA-256 hash
- Package name and APK version
- First observed and analysis dates
- Static/dynamic analysis findings
- Confidence level

**Current state:** Variant names retained with general descriptions and clear caveats. Full technical details maintained in internal records only.

### D5. Law Enforcement Submission
**What's needed:** If you want to claim data was shared with law enforcement, provide:
- Date of submission
- Agency submitted to
- Acknowledgement reference (if any)
- Whether disclosure is lawfully permissible

**Current state:** All such claims removed. Can be restored with documentation.

### D6. N-DISC / Pratibimb Terminology
**What's needed:** N-DISC and Pratibimb were cited in the PIB release but not found on the I4C public website. The current content uses N-DISC with MHA/PIB attribution. Verify these are current official terms.

---

## NEW SECTIONS ADDED
1. **RBI Customer Protection** — Two-column comparison of current and 2027 frameworks with verified RBI notification sources
2. **Privacy Policy** — Covers collection, purpose, consent, storage, sharing, retention, rights, applicable law
3. **Disclaimer** — Not a law firm, no government affiliation, no guaranteed outcomes, evidence admissibility, threat intelligence limitations, regulatory information caveat
4. **Methodology & Sources** — APK analysis methods, C2 investigation, data assessment approach, statistics disclaimer, official sources with URLs

## TECHNICAL CHANGES
- Removed live Firebase data fetching JavaScript (was publicly querying scammer C2 databases)
- Updated navigation links (Services, First Response, RBI Rights, Intelligence, About, Contact)
- Updated meta description
- Updated terminal animation to use accurate language
- Credential warning added to contact form
- Footer updated with Privacy Policy, Disclaimer, Methodology links and proper disclaimers
- Zero console errors confirmed
- Mobile responsiveness preserved
- Form validation still working (tested)
- No sensitive URLs in plain text (obfuscation preserved for contact form)

## NOT PUSHED TO LIVE
All changes are local only. Awaiting owner review and approval before pushing.
