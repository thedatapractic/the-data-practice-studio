# Domain knowledge: data management and governance

Torch's working reference for the subject the channel teaches. Read this before drafting anything, and check the script against it before handing to Dan. The purpose is that **the language itself shows expertise**: terms used in the sense a practitioner would recognise, and the right verb for the right noun.

This is part of the stable constitution. It changes only when Aji explicitly asks, and she is the authority on everything in it.

---

## 1. The verbs. This is where the gap shows first

Data has its own verbs, and using a generic one is the fastest way to sound like someone who has read about the field rather than worked in it.

**Data is:** captured, recorded, entered, collected, ingested, stored, processed, transformed, integrated, migrated, validated, profiled, cleansed, reconciled, standardised, curated, governed, stewarded, secured, shared, published, consumed, retained, archived, and eventually destroyed or purged.

**Data is managed. Data is governed.** An organisation is run; a process is run; a query is run. **Data is not "run".**

Worked example of the slip this file exists to prevent:

- Weak: "cleaning it separately at every point is the most expensive way to **run anything**."
- Expert: "cleaning it separately at every point is the most expensive way to **manage data**."

Same sentence, but the second one belongs to the discipline. Apply the same test to every verb in a script: **would a practitioner use this word for this thing?**

Other pairings worth getting right: you *define* a data element, *document* a definition, *assign* ownership, *assure* quality, *enforce* a standard, *apply* a rule, *resolve* an issue, *trace* lineage, *retain* a record, and *dispose of* data at end of life.

## 2. Governance versus management

The distinction practitioners care about most, and the one most explainers blur.

- **Data governance** is the exercise of authority and decision rights over data: who decides, what the policies and standards are, who is accountable, and how disputes are settled. It is about **decision rights and accountability**.
- **Data management** is the execution: the plans, policies, procedures and practices that deliver, control, protect and improve the value of data across its lifecycle. It is the **doing**.

Governance sets the rules; management carries them out. They are not competitors, and governance is not a synonym for security or for bureaucracy.

## 3. The roles, and why they are not interchangeable

- **Data owner** — accountable for a data domain. Decides definitions, access, and what quality is good enough. Normally a senior business role, not IT.
- **Data steward** — day-to-day responsibility for the data in that domain: maintaining definitions, monitoring quality, resolving issues. Usually the subject matter expert closest to the data.
- **Data custodian** — technical care of the data: storage, backup, access implementation, infrastructure. Usually IT.
- **Data subject** — the living individual a piece of personal data is about. A legal term under UK GDPR, not a synonym for "user".

Saying "owner" when you mean "steward" is the kind of imprecision practitioners notice immediately.

## 4. Metadata

**Metadata is data about data**: the context that makes data interpretable. Without it you have values, not information.

- **Business metadata** — what a data element means, who owns it, what the rules are, how it should be used. This is the kind most organisations lack.
- **Technical metadata** — schemas, data types, field lengths, system of record, transformations.
- **Operational metadata** — when a job ran, how many rows loaded, refresh times, failures.

**Metadata management** is the discipline of capturing, maintaining and making that context available. A **data dictionary** or **business glossary** is an artefact produced by it, not a synonym for it.

**Data lineage** is the record of where data came from, what happened to it along the way, and where it ended up. It is what lets you answer "why does this number say that?"

## 5. Data quality: the dimensions, and the distinctions

Quality is measured across dimensions rather than judged as one thing. The commonly used set:

- **Accuracy** — does the value correctly represent the real-world thing it describes?
- **Completeness** — is the data that should be present actually present?
- **Consistency** — does the same fact agree across systems and records?
- **Timeliness** — is it available when it is needed, and does it reflect the right point in time?
- **Validity** — does it conform to the defined format, type, range or rule?
- **Uniqueness** — is each real-world thing represented once, with no duplicates?

**The distinction worth making on camera:** a value can be **valid but inaccurate**. A date of birth of 01/01/1990 passes every format and range rule you can write, and is still wrong if the person was born in 1991. Validation catches the malformed; only a comparison with reality catches the wrong. Practitioners live with this distinction daily and most explainers never mention it.

Related: **data integrity** refers to data remaining complete, consistent and unaltered through storage and transfer, which is not the same as data quality. **Data profiling** is examining data to understand its actual structure, content and quality, usually before anything else. **Data cleansing** is correcting or removing data found to be wrong.

## 6. Master data and reference data

- **Master data** — the core business entities shared across the organisation: customer, student, patient, product, supplier, employee, location. The "nouns" the business runs on.
- **Reference data** — the permitted sets of values used to classify and categorise other data: country codes, status codes, course codes, ethnicity classifications. Usually externally defined or centrally maintained.

**Master data management** is the practice of maintaining a single, agreed version of those core entities so the same customer is not nine different customers across nine systems.

## 7. The data lifecycle

Plan → create or acquire → store and maintain → use → share and publish → archive → destroy.

Two points that matter for scripts. **Decisions made early determine everything downstream**, which is why upstream prevention beats downstream correction. And **destruction is a real, governed stage**, not an afterthought: retention schedules exist, and keeping personal data longer than justified is itself a compliance failure.

## 8. Regulation and ethics, stated correctly

- In the UK the framework is the **UK GDPR** alongside the **Data Protection Act 2018**, not "GDPR" as though the EU regulation applies directly. The EU GDPR still governs EU data.
- **Personal data** is information relating to an identified or identifiable living individual. **Special category data** covers health, ethnicity, religion, sexual orientation and similar, and attracts additional protection.
- **Anonymised** data is irreversibly non-identifying and falls outside the regulation. **Pseudonymised** data has direct identifiers replaced but remains personal data, because re-identification is still possible. Using these two as synonyms is a serious error.
- **Data minimisation** means collecting and supplying only what is adequate, relevant and necessary for the stated purpose.

## 9. Common imprecisions to avoid

- Do not say **database** when you mean **data**. Managing databases is not managing data.
- Do not use **data** and **information** interchangeably without care. Data becomes information when context is added.
- Do not call data governance a **security** function, or reduce it to compliance.
- Do not describe data quality as a **project**. It is an ongoing practice; the garden, not the statue.
- Do not say **"the data are wrong"** in a script unless it reads naturally aloud; UK professional usage treats data as a mass noun and "the data is wrong" is standard in speech.
- Do not claim a specific figure, regulation or standard without a source Aji can verify.

## 10. Where the presenter's own authority sits

Aji's lived expertise is the channel's real credential: regulated clinical and health data, statutory reporting to HESA and the OfS, data quality assurance, moving a team from Access to SQL Server, and her own **Quality by Design** framework of upstream prevention over downstream correction. When a script needs authority, draw on that, and see `presenter-background.md`. Never invent a practitioner anecdote to fill the gap.
