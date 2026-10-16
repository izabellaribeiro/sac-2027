# Retrospective input review: 36 baseline–variant pairs

Initial judgments were confirmed by Author-A; preparation details are documented in protocol.md. Author-B initially agreed on 28 cases and disagreed on eight. According to the author report, a meeting reached consensus on all 36, retaining every judgment below. Confirmation does not mean that every construction label or intended QUS defect was validated. Output coverage was not assessed.

## Case 01: US_001_syntactic

Project: zooniverse. Profile: syntactic.

**Baseline**
As a user, I want to discover new music recommendations based on my profile history.

**Executed variant**
I want to discover new music recommendations based on my profile history.

**Construction labels (not validation):** workbook `well_formed.no_role`; manifest `well_formed.no_role`.

**Final consensus judgment**
Explicit actor phrase omitted; remainder preserved. Valid structural omission probe; does not establish inability to infer actor.

Author-A: initial confirmation in round 1. Author-B: initially agreed. Final consensus: confirmed; judgment unchanged. Output coverage: not assessed.

## Case 02: US_002_syntactic

Project: zooniverse. Profile: syntactic.

**Baseline**
As a user, I want to discover music based on listening paths of similar users.

**Executed variant**
As a user, I need something about discover music based on listening paths of similar users.

**Construction labels (not validation):** workbook `well_formed.no_means`; manifest `well_formed.no_means`.

**Final consensus judgment**
Discover music action remains in malformed wording. Intended absence of action not established; do not use as a validated missing-action defect.

Author-A: initial confirmation in round 1. Author-B: initially agreed. Final consensus: confirmed; judgment unchanged. Output coverage: not assessed.

## Case 03: US_004_semantic

Project: zooniverse. Profile: semantic.

**Baseline**
As a user, I want to receive content recommendations based on most relevant news events in my area.

**Executed variant**
As a user, I want to receive content recommendations based on most relevant international news events in my strictly local area.

**Construction labels (not validation):** workbook `conflict-free`; manifest `conflict-free`.

**Final consensus judgment**
International and strictly local wording raises scope interpretation concerns but does not establish a contradiction. Do not validate conflict label automatically.

Author-A: initial confirmation in round 1. Author-B: initially agreed. Final consensus: confirmed; judgment unchanged. Output coverage: not assessed.

## Case 04: US_001_semantic

Project: zooniverse. Profile: semantic.

**Baseline**
As a user, I want to discover new music recommendations based on my profile history.

**Executed variant**
As a user, I want to discover new music recommendations based on my profile history under the best available conditions.

**Construction labels (not validation):** workbook `unambiguous`; manifest `unambiguous`.

**Final consensus judgment**
Undefined best available conditions adds vagueness; baseline may already contain other open expressions; no single isolated defect claim.

Author-A: initial confirmation in round 2. Author-B: initially agreed. Final consensus: confirmed; judgment unchanged. Output coverage: not assessed.

## Case 05: US_001_pragmatic

Project: zooniverse. Profile: pragmatic.

**Baseline**
As a user, I want to discover new music recommendations based on my profile history.

**Executed variant**
As a user, I want to discover new music recommendations based on my profile history in accordance with the previously approved project policy.

**Construction labels (not validation):** workbook `complete`; manifest `complete`.

**Final consensus judgment**
Adds reference to policy unavailable to agent; reference alone does not establish a Complete violation.

Author-A: initial confirmation in round 2. Author-B: initially agreed. Final consensus: confirmed; judgment unchanged. Output coverage: not assessed.

## Case 06: US_002_pragmatic

Project: zooniverse. Profile: pragmatic.

**Baseline**
As a user, I want to discover music based on listening paths of similar users.

**Executed variant**
As a user, I want to discover music based on listening paths of similar users using the terminology and conventions from the previous sprint.

**Construction labels (not validation):** workbook `uniform`; manifest `uniform`.

**Final consensus judgment**
Adds unspecified prior-sprint terminology and conventions; no concrete inconsistency establishes Uniform violation.

Author-A: initial confirmation in round 2. Author-B: initially agreed. Final consensus: confirmed; judgment unchanged. Output coverage: not assessed.

## Case 07: US_016_syntactic

Project: planningpoker. Profile: syntactic.

**Baseline**
As a moderator, I want to create a new game by entering a name and an optional description.

**Executed variant**
I want to create a new game by entering a name and an optional description.

**Construction labels (not validation):** workbook `well_formed.no_role`; manifest `REQUIRES_EXPERT_CRITERION`.

**Final consensus judgment**
Explicit moderator phrase removed; does not establish inability to infer actor.

Author-A: initial confirmation in round 3. Author-B: initially agreed. Final consensus: confirmed; judgment unchanged. Output coverage: not assessed.

## Case 08: US_027_syntactic

Project: badcamp. Profile: syntactic.

**Baseline**
As an anonymous user, I want to view a list of user profiles.

**Executed variant**
As an anonymous user, I want to view a list of user profiles and change my payment information.

**Construction labels (not validation):** workbook `atomic`; manifest `REQUIRES_EXPERT_CRITERION`.

**Final consensus judgment**
Profile viewing and payment information changes combined without a stated unifying goal; anonymous actor and personal payment information also raise identity/context uncertainty. Not an isolated single-effect change.

Author-A: initial confirmation in round 3. Author-B: initially agreed. Final consensus: confirmed; judgment unchanged. Output coverage: not assessed.

## Case 09: US_018_semantic

Project: planningpoker. Profile: semantic.

**Baseline**
As a moderator, I want to start a round by entering an item in a single multi-line text field.

**Executed variant**
As a moderator, I want to start a round by entering an item in a single multi-line text field as soon as reasonably possible.

**Construction labels (not validation):** workbook `unambiguous`; manifest `unambiguous`.

**Final consensus judgment**
As soon as reasonably possible adds temporal expectation without a verifiable bound; does not render the capability unintelligible.

Author-A: initial confirmation in round 3. Author-B: initially agreed. Final consensus: confirmed; judgment unchanged. Output coverage: not assessed.

## Case 10: US_026_semantic

Project: badcamp. Profile: semantic.

**Baseline**
As an anonymous user, I want to view a list of sponsors.

**Executed variant**
As an anonymous user, I want to view a list of sponsors promptly and appropriately.

**Construction labels (not validation):** workbook `unambiguous`; manifest `unambiguous`.

**Final consensus judgment**
Promptly and appropriately add undefined speed and appropriateness expectations; not a single isolated concern.

Author-A: initial confirmation in round 3. Author-B: initially agreed. Final consensus: confirmed; judgment unchanged. Output coverage: not assessed.

## Case 11: US_017_pragmatic

Project: planningpoker. Profile: pragmatic.

**Baseline**
As a moderator, I want to invite estimators by giving them a URL where they can access the game.

**Executed variant**
As a moderator, I want to invite estimators by giving them a URL where they can access the game using the terminology and conventions from the previous sprint.

**Construction labels (not validation):** workbook `uniform`; manifest `uniform`.

**Final consensus judgment**
Prior-sprint conventions reference unavailable context without demonstrating inconsistent terminology or format; Uniform violation not established.

Author-A: initial confirmation in round 3. Author-B: initially agreed. Final consensus: confirmed; judgment unchanged. Output coverage: not assessed.

## Case 12: US_027_pragmatic

Project: badcamp. Profile: pragmatic.

**Baseline**
As an anonymous user, I want to view a list of user profiles.

**Executed variant**
As an anonymous user, I want to view a list of user profiles only when the related prerequisite story has been completed.

**Construction labels (not validation):** workbook `independent`; manifest `independent`.

**Final consensus judgment**
Explicit dependency on an unidentified prerequisite story; necessity unknown, so an unequivocal Independent violation is not established.

Author-A: initial confirmation in round 3. Author-B: initially agreed. Final consensus: confirmed; judgment unchanged. Output coverage: not assessed.

## Case 13: US_017_syntactic

Project: planningpoker. Profile: syntactic.

**Baseline**
As a moderator, I want to invite estimators by giving them a URL where they can access the game.

**Executed variant**
As a moderator, I want to invite estimators by giving them a URL where they can access the game and update their account passwords.

**Construction labels (not validation):** workbook `atomic`; manifest `REQUIRES_EXPERT_CRITERION`.

**Final consensus judgment**
Invitation/access combined with password modification without an explained necessary relationship; who updates passwords is also unclear. Not an isolated single-effect change.

Author-A: initial confirmation in round 4. Author-B: initially agreed. Final consensus: confirmed; judgment unchanged. Output coverage: not assessed.

## Case 14: US_028_syntactic

Project: badcamp. Profile: syntactic.

**Baseline**
As an attendee, I want to have a very clear map where the buildings and rooms are.

**Executed variant**
As an attendee, so that I can make it to class on time.

**Construction labels (not validation):** workbook `well_formed.no_means`; manifest `REQUIRES_EXPERT_CRITERION`.

**Final consensus judgment**
Requested map capability removed; actor retained and benefit clause introduced. Missing requested capability supported, but change is not solely deletion.

Author-A: initial confirmation in round 4. Author-B: initially agreed. Final consensus: confirmed; judgment unchanged. Output coverage: not assessed.

## Case 15: US_019_semantic

Project: planningpoker. Profile: semantic.

**Baseline**
As a moderator, I want to select an item to be estimated or re-estimated.

**Executed variant**
As a moderator, I want to select an item to be estimated or re-estimated quickly.

**Construction labels (not validation):** workbook `unambiguous`; manifest `REQUIRES_EXPERT_CRITERION`.

**Final consensus judgment**
Quickly adds speed expectation without a bound or comparison standard; functionality remains intelligible.

Author-A: initial confirmation in round 4. Author-B: initially agreed. Final consensus: confirmed; judgment unchanged. Output coverage: not assessed.

## Case 16: US_029_semantic

Project: badcamp. Profile: semantic.

**Baseline**
As an attendee, I want to be added to a training waitlist.

**Executed variant**
As an attendee, I want to be added to a training waitlist whenever a place becomes available or unavailable.

**Construction labels (not validation):** workbook `unambiguous`; manifest `REQUIRES_EXPERT_CRITERION`.

**Final consensus judgment**
Both vacancy availability and unavailability become triggers for waitlist entry. Raises business-rule interpretation concerns but does not establish logical contradiction without training rules.

Author-A: initial confirmation in round 4. Author-B: initially agreed. Final consensus: confirmed; judgment unchanged. Output coverage: not assessed.

## Case 17: US_016_pragmatic

Project: planningpoker. Profile: pragmatic.

**Baseline**
As a moderator, I want to create a new game by entering a name and an optional description.

**Executed variant**
As a moderator, I want to create a new game by entering a name and an optional description in accordance with the previously approved project policy.

**Construction labels (not validation):** workbook `complete`; manifest `complete`.

**Final consensus judgment**
Policy reference introduces context unavailable to the agent; Complete violation not automatically established.

Author-A: initial confirmation in round 4. Author-B: initially disagreed. Final consensus: confirmed; judgment unchanged. Output coverage: not assessed.

## Case 18: US_026_pragmatic

Project: badcamp. Profile: pragmatic.

**Baseline**
As an anonymous user, I want to view a list of sponsors.

**Executed variant**
As an anonymous user, I want to view a list of sponsors using the terminology and conventions from the previous sprint.

**Construction labels (not validation):** workbook `uniform`; manifest `uniform`.

**Final consensus judgment**
Prior-sprint terminology and conventions not supplied; no concrete inconsistency establishes Uniform violation.

Author-A: initial confirmation in round 4. Author-B: initially disagreed. Final consensus: confirmed; judgment unchanged. Output coverage: not assessed.

## Case 19: US_018_syntactic

Project: planningpoker. Profile: syntactic.

**Baseline**
As a moderator, I want to start a round by entering an item in a single multi-line text field.

**Executed variant**
As a moderator, so that we can estimate it.

**Construction labels (not validation):** workbook `well_formed.no_means`; manifest `REQUIRES_EXPERT_CRITERION`.

**Final consensus judgment**
Requested capability removed; added benefit clause has an undefined it referent; not an isolated single-effect change.

Author-A: initial confirmation in round 5. Author-B: initially agreed. Final consensus: confirmed; judgment unchanged. Output coverage: not assessed.

## Case 20: US_026_syntactic

Project: badcamp. Profile: syntactic.

**Baseline**
As an anonymous user, I want to view a list of sponsors.

**Executed variant**
I want to view a list of sponsors.

**Construction labels (not validation):** workbook `well_formed.no_role`; manifest `REQUIRES_EXPERT_CRITERION`.

**Final consensus judgment**
Explicit anonymous actor removed, including anonymous-access information; does not establish inability to infer user.

Author-A: initial confirmation in round 5. Author-B: initially agreed. Final consensus: confirmed; judgment unchanged. Output coverage: not assessed.

## Case 21: US_016_semantic

Project: planningpoker. Profile: semantic.

**Baseline**
As a moderator, I want to create a new game by entering a name and an optional description.

**Executed variant**
As a moderator, I want to create a new game by entering a name and an optional description under the best available conditions.

**Construction labels (not validation):** workbook `unambiguous`; manifest `unambiguous`.

**Final consensus judgment**
Best available conditions adds unspecified conditions and undefined comparative criterion; main action remains intelligible.

Author-A: initial confirmation in round 5. Author-B: initially agreed. Final consensus: confirmed; judgment unchanged. Output coverage: not assessed.

## Case 22: US_027_semantic

Project: badcamp. Profile: semantic.

**Baseline**
As an anonymous user, I want to view a list of user profiles.

**Executed variant**
As an anonymous user, I want to view a list of user profiles as soon as reasonably possible.

**Construction labels (not validation):** workbook `unambiguous`; manifest `unambiguous`.

**Final consensus judgment**
As soon as reasonably possible adds temporal expectation without a verifiable bound.

Author-A: initial confirmation in round 5. Author-B: initially disagreed. Final consensus: confirmed; judgment unchanged. Output coverage: not assessed.

## Case 23: US_018_pragmatic

Project: planningpoker. Profile: pragmatic.

**Baseline**
As a moderator, I want to start a round by entering an item in a single multi-line text field.

**Executed variant**
As a moderator, I want to start a round by entering an item in a single multi-line text field only when the related prerequisite story has been completed.

**Construction labels (not validation):** workbook `independent`; manifest `independent`.

**Final consensus judgment**
Dependency on an unidentified prerequisite story established; unnecessary dependency or unequivocal Independent violation not established.

Author-A: initial confirmation in round 5. Author-B: initially agreed. Final consensus: confirmed; judgment unchanged. Output coverage: not assessed.

## Case 24: US_028_pragmatic

Project: badcamp. Profile: pragmatic.

**Baseline**
As an attendee, I want to have a very clear map where the buildings and rooms are.

**Executed variant**
As an attendee, I want to have a very clear map where the buildings and rooms are in accordance with the previously approved project policy.

**Construction labels (not validation):** workbook `complete`; manifest `complete`.

**Final consensus judgment**
Reference to unavailable policy adds context need; Complete violation not automatically established; very clear wording inherited from baseline.

Author-A: initial confirmation in round 5. Author-B: initially disagreed. Final consensus: confirmed; judgment unchanged. Output coverage: not assessed.

## Case 25: US_006_syntactic

Project: zooniverse. Profile: syntactic.

**Baseline**
As an admin, I want to filter videos based on audio-visual quality metrics.

**Executed variant**
As an admin, I want to filter videos based on audio-visual quality metrics and I want to update the system log database immediately.

**Construction labels (not validation):** workbook `atomic.conjunctions`; manifest `atomic.conjunctions`.

**Final consensus judgment**
Adding log-database updates raises an atomicity concern, but logging may be part of filtering. Independence of the functionalities is not established. Immediately also introduces an unbounded timing expectation.

Author-A: initial confirmation in round 6. Author-B: initially agreed. Final consensus: confirmed; judgment unchanged. Output coverage: not assessed.

## Case 26: US_020_syntactic

Project: planningpoker. Profile: syntactic.

**Baseline**
As a moderator, I want to edit an item in the list of items to be estimated.

**Executed variant**
As a moderator, I need something about edit an item in the list of items to be estimated.

**Construction labels (not validation):** workbook `well_formed.no_means`; manifest `well_formed.no_means`.

**Final consensus judgment**
The wording deteriorates, but edit an item remains present. The intended absence of an action is not established.

Author-A: initial confirmation in round 6. Author-B: initially agreed. Final consensus: confirmed; judgment unchanged. Output coverage: not assessed.

## Case 27: US_007_semantic

Project: zooniverse. Profile: semantic.

**Baseline**
As an admin, I want to get a quick assessment of whether audio material has been edited before the upload.

**Executed variant**
As an admin, I want to get a quick assessment of whether audio material has been edited before the upload under the best available conditions.

**Construction labels (not validation):** workbook `unambiguous`; manifest `unambiguous`.

**Final consensus judgment**
Best available conditions adds undefined conditions. Quick assessment already occurs in the baseline and is not attributable to this change.

Author-A: initial confirmation in round 6. Author-B: initially agreed. Final consensus: confirmed; judgment unchanged. Output coverage: not assessed.

## Case 28: US_021_semantic

Project: planningpoker. Profile: semantic.

**Baseline**
As a moderator, I want to delete an item from the list of items to be estimated.

**Executed variant**
As a moderator, I want to delete an item from the list of items to be estimated when it is no longer relevant.

**Construction labels (not validation):** workbook `unambiguous`; manifest `REQUIRES_EXPERT_CRITERION`.

**Final consensus judgment**
No longer relevant introduces an exclusion condition without an explicit decision-maker or criterion. Clarification may be useful, but judgment may legitimately belong to the moderator; an unequivocal defect is not established.

Author-A: initial confirmation in round 6. Author-B: initially agreed. Final consensus: confirmed; judgment unchanged. Output coverage: not assessed.

## Case 29: US_008_pragmatic

Project: zooniverse. Profile: pragmatic.

**Baseline**
As an admin, I want to automatically validated the ingested contents for copyright infringement.

**Executed variant**
As an admin, I want to automatically validated the ingested contents for copyright infringement using the terminology and conventions from the previous sprint.

**Construction labels (not validation):** workbook `uniform`; manifest `uniform`.

**Final consensus judgment**
Prior-sprint terminology and conventions refer to context not supplied to the agent. Uniform violation is not established. The grammatical issue automatically validated was already in the baseline.

Author-A: initial confirmation in round 6. Author-B: initially agreed. Final consensus: confirmed; judgment unchanged. Output coverage: not assessed.

## Case 30: US_032_pragmatic

Project: badcamp. Profile: pragmatic.

**Baseline**
As an anonymous user, I want to view venue details.

**Executed variant**
As a training coordinator, I want to view venue details.

**Construction labels (not validation):** workbook `Needs QUS mapping`; manifest `REQUIRES_EXPERT_CRITERION`.

**Final consensus judgment**
Actor changes from anonymous user to training coordinator. Viewing venue details remains plausible; a defect cannot be established without access rules or backlog context.

Author-A: initial confirmation in round 6. Author-B: initially agreed. Final consensus: confirmed; judgment unchanged. Output coverage: not assessed.

## Case 31: US_030_syntactic

Project: badcamp. Profile: syntactic.

**Baseline**
As a trainee, I want to see which trainings I have signed up for.

**Executed variant**
I want to see which trainings I have signed up for.

**Construction labels (not validation):** workbook `well_formed.no_role`; manifest `well_formed.no_role`.

**Final consensus judgment**
Explicit trainee actor omitted; I have signed up still permits inference of a person enrolled in training.

Author-A: initial confirmation in round 6. Author-B: initially disagreed. Final consensus: confirmed; judgment unchanged. Output coverage: not assessed.

## Case 32: US_036_syntactic

Project: zooniverse. Profile: syntactic.

**Baseline**
As a user, I want to detect the faces of persons present in a video timeline.

**Executed variant**
I want to detect the faces of persons present in a video timeline.

**Construction labels (not validation):** workbook `well_formed.no_role`; manifest `REQUIRES_EXPERT_CRITERION`.

**Final consensus judgment**
Explicit user actor omitted; this does not establish that the capability is unintelligible.

Author-A: initial confirmation in round 6. Author-B: initially disagreed. Final consensus: confirmed; judgment unchanged. Output coverage: not assessed.

## Case 33: US_031_semantic

Project: badcamp. Profile: semantic.

**Baseline**
As an administrator, I want to create and maintain venues.

**Executed variant**
As an administrator, I want to create and maintain venues using a suitable format.

**Construction labels (not validation):** workbook `unambiguous`; manifest `REQUIRES_EXPERT_CRITERION`.

**Final consensus judgment**
Suitable format adds an undefined format expectation: neither the formatted object nor suitable is specified. No more specific QUS criterion is automatically assigned.

Author-A: initial confirmation in round 6. Author-B: initially agreed. Final consensus: confirmed; judgment unchanged. Output coverage: not assessed.

## Case 34: US_037_semantic

Project: zooniverse. Profile: semantic.

**Baseline**
As a user, I want to detect commercial products displayed in a video timeline.

**Executed variant**
As a user, I want to detect commercial products displayed in a video timeline under the best available conditions.

**Construction labels (not validation):** workbook `unambiguous`; manifest `unambiguous`.

**Final consensus judgment**
Best available conditions adds undefined conditions while the principal action remains identifiable.

Author-A: initial confirmation in round 6. Author-B: initially agreed. Final consensus: confirmed; judgment unchanged. Output coverage: not assessed.

## Case 35: US_022_pragmatic

Project: planningpoker. Profile: pragmatic.

**Baseline**
As a moderator, I want to enter the agreed-upon estimate.

**Executed variant**
As a moderator, I want to enter the agreed-upon estimate in accordance with the previously approved project policy.

**Construction labels (not validation):** workbook `complete`; manifest `complete`.

**Final consensus judgment**
Policy reference adds context unavailable to the agent; Complete violation is not automatically established.

Author-A: initial confirmation in round 6. Author-B: initially disagreed. Final consensus: confirmed; judgment unchanged. Output coverage: not assessed.

## Case 36: US_038_pragmatic

Project: zooniverse. Profile: pragmatic.

**Baseline**
As a user, I want to detect broadcaster logos within a video frame.

**Executed variant**
As a user, I want to detect broadcaster logos within a video frame using the terminology and conventions from the previous sprint.

**Construction labels (not validation):** workbook `uniform`; manifest `uniform`.

**Final consensus judgment**
Prior-sprint terminology and conventions refer to unspecified context; insufficient evidence for Uniform violation.

Author-A: initial confirmation in round 6. Author-B: initially disagreed. Final consensus: confirmed; judgment unchanged. Output coverage: not assessed.
