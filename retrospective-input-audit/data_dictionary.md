# Data dictionary

| Field | Meaning |
|---|---|
| case_number | Order of presentation to the human reviewer, 1–36. |
| pair_id | Stable story identifier joined to the original experimental condition. |
| story_id | Parent-story identifier; repeated across some conditions. |
| project | Original project label; not proof of representative sampling. |
| profile | Original construction profile; retained without relabeling. |
| baseline_text / variant_text | Exact texts reconciled between the input workbook and construction manifest. Existing wording/grammar preserved. |
| construction_label_workbook / construction_label_manifest | Original labels from each source. Neither is a new validated reference. |
| reviewed_judgment | English rendering of the interpretation retained in the final two-coauthor consensus. Primary substantive record. |
| judgment_descriptor | Descriptive indexing label for that interpretation; not a scored, mutually exclusive or independently validated taxonomy. |
| initial_reviewer_id | Author-A, who initially confirmed the proposed interpretations. See the preparation note in protocol.md. |
| reviewer_ids | Author-A and Author-B, the two coauthor reviewers. |
| second_reviewer_initial_status | AGREED or DISAGREED, as reported by Author-A. No alternative ratings are inferred. |
| final_consensus_status | CONFIRMED for all 36 cases following the reported meeting. |
| final_judgment_changed | False for every case: the consensus retained the existing judgment. |
| review_status | CONFIRMED means the interpretation was endorsed, not that the original QUS label was validated. |
| author_a_confirmation_round | Link to the corresponding entry in confirmation_record.json. |
| review_method | Retrospective two-coauthor review and discussion-to-consensus; preparation details are in protocol.md. |
| output_coverage_status | NOT_ASSESSED_IN_THIS_PACKAGE for every row. |

No binary all-purpose valid/invalid field is provided because concern presence, QUS-label validity and single-defect isolation are distinct judgments. Descriptive counts should use explicit denominators and not treat rows as independent parent stories.
