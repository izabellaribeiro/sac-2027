# SAC study — retrospective input review

Release date: 2026-10-16. This add-on contains a retrospective two-coauthor review of **36 baseline–variant pairs from 23 distinct parent stories**. It is separate from the experiment's existing 100-question consensus review and does not replace the original data.

## Scope

- 12 pairs per profile: syntactic, semantic, pragmatic.
- 12 pairs per project label: Zooniverse, PlanningPoker, BADCamp.
- Two human coauthor reviewers, anonymized as Author-A and Author-B.
- Author-B initially agreed on 28/36 cases (77.8%) and disagreed on cases 17, 18, 22, 24, 31, 32, 35 and 36. According to the author report, a subsequent meeting reached consensus on all 36, retaining every existing judgment.
- 36 judgments confirmed; the other 99 variants in the 135-variant pool were not reviewed in this activity.
- No systematic assessment of agent-question targeting or coverage is included.

Balanced pair counts do not imply 36 independent stories, random sampling, or representativeness. Some parent stories contribute more than one profile. Twelve additional, previously unreviewed parents were added after the initial 24-pair review; the final set was not preregistered.

## Files

- `casebook.md`: human-readable original texts, executed variants, construction labels and confirmed judgments.
- `reviewed_pairs.csv` / `.json`: equivalent row-level records; CSV is UTF-8 with BOM for spreadsheet import.
- `protocol.md`: procedure, selection, limitations, and the [preparation and provenance note](protocol.md#preparation-and-provenance).
- `data_dictionary.md`: field meanings and interpretation boundaries.
- `confirmation_record.json`: preserved historical initial confirmation rounds by Author-A.
- `consensus_record.json`: subsequent author-reported second review and meeting consensus.
- `adjudication.csv`: eight initially disputed cases and retained final judgments. Original alternative judgments and disagreement reasons were not provided.
- `CHANGELOG.md`: changes from the initial package.
- `summary.json`: descriptive counts, not detection or validity rates.
- `source_provenance.json`: source hashes and label discrepancies.
- `checksums.sha256`: checksums of package contents.

## Interpretation

A confirmed judgment can identify an explicit actor omission, added vagueness, additional contextual needs, multiple simultaneous changes, or insufficient evidence for the originally assigned defect. Do not count every confirmed row as a valid QUS violation. Retain the complete judgment, including qualifications.

The original labels are preserved. 12 reviewed pairs have different labels in the workbook and construction manifest, including unresolved labels in one source. These discrepancies were not silently repaired. Judgments were based on the displayed texts, not on treating either construction label as a validated reference.

This package documents two-coauthor consensus, not independent blind annotation or an inter-rater reliability study. The second review and meeting outcome are recorded from the author report. The 77.8% figure describes initial endorsement agreement; it is not a reliability coefficient. No kappa is calculated because original alternative ratings were not supplied. The 12 source-label discrepancies are distinct from the eight human-review disagreements. No claim of blindness is made.
