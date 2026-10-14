# Appendices: Review of Your Google Doc Notes

# Appendix A: Coverage of Your Google Doc Notes

Each domain section was expanded from the Review Manual text, so most bullets are new ORM-derived detail. The 📓 count is the number of items already in your notes.

| Domain | Bullet items | Already in your notes 📓 | Verdict |
|---|---|---|---|
| D1 Auditing Process | ~1,190 | ~127 | Best covered (sampling, controls, planning, QA) |
| D2 Governance & Mgmt | ~1,420 | ~66 | Good on strategy and governance, thin on the rest |
| D3 Acquisition & Development | ~1,390 | ~4 | **Almost no notes yet** |
| D4 Operations & Resilience | ~1,730 | ~35 | BCP/DR/backup partly covered, operations barely |
| D5 Protection of Assets | ~2,510 | ~31 | **Largest domain, thinnest coverage** |

**Priority gaps**, by exam weight (D4 and D5 are 26% each):
1. D5: cryptography/PKI, IAM and access control types, network security, attacks, incident response, forensics.
2. D4: networking/OSI, database management, BCP testing and DR strategies (RTO/RPO/MTD, site types).
3. D3: the whole domain (SDLC, testing, changeover, application controls, project management).
4. D2: risk analysis methods, COBIT detail beyond the goals cascade, privacy, vendor management.

# Appendix B: Issues Found in the Google Doc

These are the things I'd fix before building on it. Your own prompt asks for deduplication and fact-checking.

**Duplicates**
- The MCQ "importing market price data from external data providers" appears twice (once with `[!!]`, once without).
- Key Terminologies lists several terms twice: Agile Auditing, Service Level Agreement, Strategic Alignment, Discovery sampling, ISACA Standards/Guidelines vs Standards/Guidelines.
- Key Concepts repeats ideas, such as "Inherent risk" and "Corrective controls", in several bullets.

**Empty definitions** in Key Terminologies: Agile Auditing (first entry), Traditional Auditing, Due Diligence, Atomicity in DBMS, RTO, RPO. A fuller definition for Agile Auditing exists further down the list.

**Unresolved or contradictory items**
- The MCQ on backups (every two weeks, no backup policy) is marked both `[HDA Ans]: Absence of a policy` and `[Maybe Actual Ans]: Insufficient frequency`. It needs a final ruling backed by ORM wording.
- Several questions carry `[!!]` or `[Most probable]` as answer markers, but no answer is given for many MCQs. For example, the first questions have options only and no marked key.
- The FTP vs HTTP question ("greatest risk") is marked `[Most probable]`, which suggests the answer is uncertain.
- The SDLC question has `[!!]` on the requirement-definition answer. Check that the correct option isn't "design", depending on ORM wording.

**Misplaced items**
- Hot-site and diverse-routing notes sit in Key Concepts without a domain heading. They belong in D4 (4.13 and 4.16).
- "Regulatory data quality is the highest audit priority" is a data-governance item (D2) but sits among audit-planning bullets.
- The PKI, DR-test and IAM MCQs are in a D1/D2-heavy block.

**Wording to double-check against the ORM**
- "Auditors should be consulted during SDLC requirement definitions": check that the ORM frames this as advising on controls without impairing independence.
- "Hot site storage capacity must match primary sites for replication": check the exact ORM phrasing.

# Appendix C: Where Your Notes Don't Fit the ORM Structure

Items in your notes that cross several ORM sections, and where I placed them:

| Your note | Placed in | Also relevant to |
|---|---|---|
| Incident Management Lifecycle (RA → BIA → BCP → DRP) | 4.12.0 | 2.5, 4.15, 4.16 |
| BYOD "threat defines the control" | 5.9.5 | 5.6, 5.8.6, 5.4.6 |
| COBIT goals cascade | 2.2.1 | 2.10 |
| Audit sampling framework | 1.6.2 | 3.5 |
| Pseudonymisation | 2.6.3 | 1.8.4 (AI training data) |
| SOX | 2.1.3 | 1.3.2 |
| Atomicity | 4.11.3 | 3.5.3 |

# Appendix D: Sources
- ORM 28th Ed. table of contents: backbone and numbering for all five domains.
- Your Google Doc "CISA Notes": the 📓 markers and the item-level granularity.
- ➕ items: general CISA knowledge, to be verified against the ORM.

# Appendix E: Verification Status

- **Fact-check:** about 1,590 added points with low word-overlap against the Review Manual text were checked one by one: ~1,566 matched, 5 were corrected, ~18 were marked ➕ (not in the manual).
- **Error in the manual itself:** the ORM says a 99.9% availability SLA allows "about three and a half days" of downtime a year. The correct figure is ~8.8 hours (3.5 days fits 99%). Corrected in D4.
- **Figure text:** all 585 pages were re-read by OCR. Only 20 pages had figure text missing from the first extraction. 50 bullets were added from 11 of them; 17 of those are marked ➕ because the surrounding text doesn't confirm them.
- **Not independently verified:** the ~1,000 added points that already had strong word-overlap with the manual were not individually re-read. Case-study answers are stubs in the manual text and are not expanded here.
