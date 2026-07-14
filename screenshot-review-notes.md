# ClearInspect guide - screenshot review notes

Internal reference only - intentionally not listed in SUMMARY.md, so GitBook does not publish it on the site. Kept in the repo alongside screenshots.md for the capture/edit history.

Scope: every embedded demo image (54 instances, 44 unique assets) checked against its section heading, nearby prose/steps and caption. Placeholders noted separately.

## Edits applied - 6 Jul 2026

The findings below were reviewed and the following actions applied to the guide (delivered as `clearinspect-retailer-guide-updated.zip`). The original review text is kept unchanged for reference.

**Blur** - plate and VIN regions blurred in 8 assets: demo-r03, r46 (home card reg + VIN), r05 (physical plate), r06 (detected plate text), r07 (plate + VIN form fields), r09, r10 (plate on vehicle), r16 (plates in 3 thumbnails).

**Captions added** (suggested wording): RA06-6, RA07-1, RA09-3, RA11-7, RA12-3, RA12-4, RA12-5, RA18-3, plus the honest caption on RA07-3 ("The Manual toggle sits top right - turn it on to capture yourself").

**Reworded** - RA09-2: cluster capture has no real-time detection, so "wait for green" was removed from the steps; new step says to hold steady with the cluster inside the frame, with a matching caption.

**Removed** - RA11-2 (duplicate of RA11-1), RA11-8 (implied a tyre sign-off the text denies), RA12-2 (duplicate of RA12-1), RA12-6 and RA12-7 (triple-repeat of RA12-5's asset), RA13-6 (third near-identical overview shot). The RA11-2 legend section now points to the image above; demo-r36 is unplaced and kept as a spare.

**Text fix** - RA13-9 step 2 now lists the menu as it appears: Image, Damage, and (once a damage is selected) Closeup, Notes, Method.

**Deferred** - RA13-2 left in place; a note about the Damages vs Existing Damages build inconsistency was added to screenshots.md, whose location table and reuse list were also updated to reflect the removals and blurs.

After these edits: 48 embedded instances remain; open items are the RA13-2 build alignment and the pending captures (RA07-3's toggle-on shot is still worth capturing).

---

Verdicts: OK / Add caption / Improve caption / Add context / Mismatch / Redundant. Suggested captions are written in the guide's voice (italic one-liners).

---

## retailer-app/getting-started/01-about-clearinspect.md

| Slot | Asset | Verdict |
|---|---|---|
| RA01-1 | demo-r46.png | OK |

- RA01-1 - caption is accurate and adds context ("a quick look at the app in use"). Same screen as RA04-1; justified here as an overview teaser. Needs blur (reg + VIN).

## retailer-app/getting-started/03-signing-in.md

| Slot | Asset | Verdict |
|---|---|---|
| RA03-1 | demo-r01.png | OK |
| RA03-2 | demo-r02.png | OK |

- RA03-1 - no caption, but the numbered steps directly above name every element shown (User ID, password, Login). Forgot Password? is visible and covered later on the page.
- RA03-2 - no caption; steps name the tick text and both buttons exactly as shown. Minor: the background screen reads "My Inspections" while page 04 calls the home list "Today's Inspections" - cosmetic, no action needed.

## retailer-app/getting-started/04-the-home-screen.md

| Slot | Asset | Verdict |
|---|---|---|
| RA04-1 | demo-r03.png | OK |

- RA04-1 - the "What you see" list below names everything visible: Today's Inspections, status, reg and VIN, date/time, description, Estimate and Approved amounts, + Create inspection, hamburger menu. Needs blur (reg + VIN).

## retailer-app/inspection/06-start-an-inspection.md

| Slot | Asset | Verdict |
|---|---|---|
| RA06-2 | demo-r04.png | OK |
| RA06-5 | demo-r05.jpg | OK |
| RA06-6 | demo-r06.png | Add caption - APPLIED |
| RA06-3 | demo-r07.png | OK |
| RA06-7 | demo-r08.png | OK |

- RA06-2 - step names the Vehicle details screen and Scan License Plate; both visible. The Offline Mode toggle in shot is explained in the "Working offline?" section above.
- RA06-5 - step matches (guide box, capture, Cancel). Needs blur (plate).
- RA06-6 - Add caption. The step says "then continue" but never names the tick button, the main confirm action in the shot. Suggested caption: `_Verify the detected number - tap the tick to confirm, or Retry to scan again._` Needs blur (plate text).
- RA06-3 - prose lists the exact form fields shown (License Plate Number, VIN, Make, Model, Interior Config) and the Next button. Needs blur (plate + VIN).
- RA06-7 - prose lists the seven bodystyles and both buttons; SUV pre-selected as described.

## retailer-app/inspection/07-capturing-exterior-images.md

| Slot | Asset | Verdict |
|---|---|---|
| RA07-5 | demo-r09.jpg | OK |
| RA07-1 | demo-r10.jpg | Add caption - APPLIED |
| RA07-2 | demo-r11.jpg | OK |
| RA07-3 | demo-r10.jpg | Mismatch - INTERIM FIX (honest caption added; toggle-on recapture still pending) |
| RA07-4 | demo-r16.jpg | OK |

- RA07-5 - caption is accurate and specific (prompt, views list, 0/41 counter). Needs blur (plate).
- RA07-1 - Add caption. It sits directly under RA07-5 with no text between, so the red-vs-green contrast the two images make is never stated. Suggested caption: `_The same view with the overlay green - framing and quality are right, and the app auto-captures._` Needs blur (plate).
- RA07-2 - steps above cover it; the views list and counter (1/41) illustrate step 6.
- RA07-3 - Mismatch. The section says "Turn on the Manual toggle (top right)" but the image shows the Manual toggle OFF - it is also the same asset already used for RA07-1 higher up the page. Replace with a capture showing the toggle on (already in the capture list as RA07-3, REQUIRED). Until then, remove the image or caption it honestly: `_The Manual toggle sits top right - turn it on to capture yourself._`
- RA07-4 - prose quotes the screen title and the "Uploaded 24/24 Images/Videos" line; thumbnails per view visible. Needs blur (plates in thumbnails).

## retailer-app/inspection/08-capturing-interior-images.md

| Slot | Asset | Verdict |
|---|---|---|
| RA08-1 | demo-r13.jpg | OK |
| RA08-2 | demo-r12.jpg | OK |

- RA08-1 - bullets above explain red/green and the shutter; image shows a green door-pad overlay with the shutter, matching the "tap the shutter when green" rule.
- RA08-2 - step 1 names the same views shown in the list (Right Front Door Pad, Tread Plate, Interior). Red overlay state is consistent with "wait for green".

## retailer-app/inspection/09-capturing-the-instrument-cluster.md

| Slot | Asset | Verdict |
|---|---|---|
| RA09-1 | demo-r14.jpg | OK |
| RA09-2 | demo-r15.jpg | Add caption - APPLIED (steps also reworded: no real-time detection on cluster, "wait for green" removed) |
| RA09-3 | demo-r17.png | Add caption - APPLIED |

- RA09-1 - prose quotes the prompt text word for word; Done button visible.
- RA09-2 - Add caption. Steps say "wait for green", but the frame in the shot is white (pre-capture state), which a reader may find confusing. Suggested caption: `_Line the cluster up inside the frame - it turns green when the cluster is framed clearly._`
- RA09-3 - Add caption. The section lists three readings (warning lights, odometer, fuel) but the image shows only the Warning lights page. Suggested caption: `_The Warning lights page (1/3) pre-filled from the cluster image - here Handbrake and Seatbelt were detected._`

## retailer-app/inspection/11-tyre-inspection.md

| Slot | Asset | Verdict |
|---|---|---|
| RA11-1 | demo-r37.png | OK |
| RA11-2 | demo-r37.png | Redundant - REMOVED |
| RA11-4 | demo-r38.jpg | OK |
| RA11-9 | demo-r39.png | OK |
| RA11-5 | demo-r41.png | OK |
| RA11-6 | demo-r40.jpg | OK |
| RA11-7 | demo-r40.jpg | Add caption - APPLIED |
| RA11-8 | demo-r44.png | Redundant - REMOVED |

- RA11-1 - steps name the Overview - Wheels & Tyres screen; the wheel graphic and statuses are visible.
- RA11-2 - Redundant. Identical asset repeated 12 lines after RA11-1 on the same page. The legend bullets (Clean, Mismatch/Damages, Not available, Tyre info incomplete) all describe the first instance perfectly well. Remove this instance and let the legend section refer to the image above.
- RA11-4 - prose matches the left panel exactly (brand, model, size, load and speed rating, tread values below).
- RA11-9 - steps match the Edit Tyre Information dialog and its seven dropdowns, plus Confirm. Trivial demo quirk: the list shows Left Rear Tyre but the dialog is titled Left Front Wheel - ignore or recapture at leisure.
- RA11-5 - Enter Tyre Tread screen with inner/middle/outer values and Save, exactly as the steps describe.
- RA11-6 - tyre and alloy damage markers (EI) visible; section text covers it.
- RA11-7 - Add caption. Same asset as RA11-6, reused 9 lines later. The step says "Tick the Replace Tyre checkbox" but in the shot the checkbox is untitcked and easy to miss at bottom left. Suggested caption: `_The Replace Tyre checkbox (bottom left). Tick it to add the tyre to the repair estimate._` If you would rather not reuse the asset twice on one page, capture the ticked state (RA11-7 is in the capture list as REQUIRED).
- RA11-8 - Redundant. The section explicitly says there is NO separate tyre sign-off and points to page 15, then shows the sign-off dialog anyway (third use of demo-r44 in the guide). Showing it here implies the opposite of the text. Remove.

## retailer-app/inspection/12-completing-the-checklist.md

| Slot | Asset | Verdict |
|---|---|---|
| RA12-1 | demo-r17.png | OK |
| RA12-2 | demo-r17.png | Redundant - REMOVED |
| RA12-3 | demo-r18.png | Add caption - APPLIED |
| RA12-4 | demo-r19.png | Add caption - APPLIED |
| RA12-5 | demo-r20.png | Add caption - APPLIED |
| RA12-6 | demo-r20.png | Redundant - REMOVED |
| RA12-7 | demo-r20.png | Redundant - REMOVED |
| RA12-8 | demo-r21.png | OK |

- RA12-1 - fine as the opening shot ("It opens with the cluster readings"); Next visible top right.
- RA12-2 - Redundant. Identical to RA12-1, 10 lines above on the same page. Remove; the bullets can lean on RA12-3/RA12-4 for the remaining pages.
- RA12-3 - Add caption. Part of an unlabeled three-image stack. Suggested: `_Odometer reading (2/3), pre-filled from the cluster image - edit it if needed._`
- RA12-4 - Add caption. Suggested: `_Fuel Level % (3/3), chosen from the dropdown._`
- RA12-5 - Add caption, and make it carry the two neighbours' jobs (see next). Suggested: `_An Other Checks question. The red asterisk marks a mandatory question; the camera icon attaches an image for context._`
- RA12-6, RA12-7 - Redundant. The same asset appears three times in a row (question, mandatory marker, attach image). One instance with the caption above shows all three things - the asterisk and camera icon are both in the single frame. Remove these two.
- RA12-8 - matches "On the last page, tap Save (top right)"; shows Other Checks 7/7 with Save.

## retailer-app/inspection/13-reviewing-damage.md

| Slot | Asset | Verdict |
|---|---|---|
| RA13-1 | demo-r22.png | OK |
| RA13-2 | demo-r42.png | Mismatch - DEFERRED (left in place; build-inconsistency note added to screenshots.md) |
| RA13-3 | demo-r23.jpg | OK |
| RA13-15 | demo-r33.jpg | OK |
| RA13-9 | demo-r25.jpg | Mismatch - FIXED (step 2 text corrected to the menu as shown) |
| RA13-12 | demo-r26.jpg | OK |
| RA13-13 | demo-r27.jpg | OK |
| RA13-4 | demo-r28.jpg | OK |
| RA13-14 | demo-r32.jpg | OK |
| RA13-10 | demo-r29.png | OK |
| RA13-5 | demo-r30.jpg | OK |
| RA13-11 | demo-r31.jpg | OK |
| RA13-8 | demo-r34.jpg | OK |
| RA13-16 | demo-r35.jpg | OK |
| RA13-6 | demo-r36.png | Redundant - REMOVED (demo-r36 kept in assets as a spare) |
| RA13-7 | demo-r44.png | OK |

- RA13-1 - reasonable opening shot of the DC overview.
- RA13-2 - Mismatch (minor but user-visible). The bullet list says the legend reads "Clean / Damages / Unrecognized", and RA13-1's shot agrees, but this image's legend reads "Clean / Existing Damages / Unrecognized" - two different UI versions on one page. Fix one of two ways: align the bullet to the label in this shot (rename the bullet to **Existing Damages**) and drop RA13-1, or recapture RA13-2 from the same build as RA13-1. The caption itself is accurate.
- RA13-3 - steps name everything in shot: arrows on the right edge, panel dropdown top left, Complete top right, detected damage marker (F).
- RA13-15 - caption is accurate (two damages, dropdown, Complete) and distinguishes it from RA13-3.
- RA13-9 - Mismatch. Step 2 says the menu "also offers **Image** and **Repair**", but the menu in the shot reads Image, Damage, Closeup, Notes, Method (last three greyed out). Suggested text edit for step 2: "Choose **Damage** from the menu. (The menu also offers **Image**, and - once a damage is selected - **Closeup**, **Notes** and **Method**.)"
- RA13-12, RA13-13 - captions accurate for Draw Mode and Zoom Mode; the toggle is visible in both.
- RA13-4 - drawn ring plus the tick, exactly as step 4 says.
- RA13-14 - caption accurate: two markers, lettered A and F.
- RA13-10 - Add Damage dialog fields match step 5 word for word (Select Panel, Select damage, Damage Area Small/Large, Next).
- RA13-5 - Add Repair Method dialog with Save, as step 6 says.
- RA13-11 - prompt text in shot matches the quoted question and both buttons.
- RA13-8 - delete confirmation quote and bin icon match the steps; the damage list on the left illustrates step 1.
- RA13-16 - caption accurate: panel count drops to (1), marker F gone.
- RA13-6 - Redundant. Third near-identical overview screenshot on this page (after RA13-1 and RA13-2), and it does not show what the section needs: the steps say "tap a Damages icon to jump to the damaged part", but no jump or opened part is shown - just the same overview again. Remove, or replace with a capture mid-jump. If RA13-1 is dropped per the RA13-2 note, this one could stay as the section's only overview shot with a caption: `_Tap any marker on the overview to jump straight to that section's images._`
- RA13-7 - dialog text and Sign Off button match the steps exactly.

## retailer-app/inspection/15-completing-and-signing-off.md

| Slot | Asset | Verdict |
|---|---|---|
| RA15-1 | demo-r44.png | OK |
| RA15-3 | demo-r45.png | OK |

- RA15-1 - same asset as RA13-7 on the previous page, but justified: this is the canonical sign-off page and the steps describe exactly this dialog.
- RA15-3 - "An Inspection Submitted confirmation appears" sits directly above the matching shot.

## retailer-app/after/18-working-offline.md

| Slot | Asset | Verdict |
|---|---|---|
| RA18-3 | demo-r04.png | Add caption - APPLIED |

- RA18-3 - justified reuse of the Vehicle details shot (the other use, RA06-2, is about Scan License Plate). But here the eye goes to the big black Scan License Plate button, not the toggle the section is about, and the toggle is shown OFF. Suggested caption: `_The Offline Mode toggle on the Vehicle details screen - turn it on before starting the inspection._`

---

## Blur before publish - DONE (all 8 assets blurred and visually verified, 6 Jul 2026)

All sensitive values trace to one demo vehicle. The registration is a current-format UK plate and the VIN is a valid JLR-format VIN (SAL...), so treat them as real unless confirmed staged; if they are traceable to a real vehicle, blur every occurrence below. No customer names, emails or non-zero prices appear anywhere (estimate amounts show GBP 0).

| Asset | Used at | What to blur |
|---|---|---|
| demo-r03.png | RA04-1 | Reg BK25UBF, VIN SALCA2AN3SH360859 |
| demo-r46.png | RA01-1 | Same card as demo-r03 - reg + VIN |
| demo-r05.jpg | RA06-5 | Number plate in photo |
| demo-r06.png | RA06-6 | Detected plate text (full-screen) |
| demo-r07.png | RA06-3 | License Plate Number and VIN fields |
| demo-r09.jpg | RA07-5 | Plate on vehicle |
| demo-r10.jpg | RA07-1, RA07-3 | Plate on vehicle |
| demo-r16.jpg | RA07-4 | Plates in Front, Bonnet and Front Bumper thumbnails |

Not flagged: odometer value in demo-r15/r17/r18 (not personal data), GBP 0 amounts.

---

## Page-level flags

**Pages where an image would clearly help but none exists yet**

- web-dashboard/inspection-reports/08-understanding-the-report.md - the longest, most reference-heavy page in the guide (12 slots, all placeholders). Highest-value capture target.
- retailer-app/inspection/14-condition-grading-and-repair-estimate.md - describes estimate line items with no visual; RA14-1 reuses WD08-9 once captured.
- retailer-app/after/16-viewing-and-sharing-the-report.md - a seven-bullet description of the report with four empty slots.

**Pages where images cluster with little text between**

- retailer-app/inspection/12-completing-the-checklist.md - 8 images in 39 lines, including a three-image unlabeled stack and the same asset three times in a row. Worst offender; the Redundant/Add caption fixes above resolve it.
- retailer-app/inspection/07-capturing-exterior-images.md - RA07-5 and RA07-1 sit back to back with no prose between; the suggested RA07-1 caption fixes it.
- retailer-app/inspection/13-reviewing-damage.md - 16 images in 103 lines, but most sit inside numbered steps with captions; acceptable once the three overview shots are thinned to one or two.

**Side finding**

- screenshots.md lists RA05-1 (language selector on login) as REQUIRED, but 05-changing-the-language.md contains no placeholder for it - only RA05-2. Add the slot or drop it from the capture list.

**Placeholders still awaiting capture (not reviewed above)**

- retailer-app/getting-started/02-installing-the-app.md: RA02-1, RA02-2
- retailer-app/getting-started/03-signing-in.md: RA03-3
- retailer-app/getting-started/04-the-home-screen.md: RA04-2
- retailer-app/getting-started/05-changing-the-language.md: RA05-2
- retailer-app/inspection/06-start-an-inspection.md: RA06-1, RA06-4
- retailer-app/inspection/10-keys-charging-cable-and-other-captures.md: RA10-1
- retailer-app/inspection/11-tyre-inspection.md: RA11-3
- retailer-app/inspection/14-condition-grading-and-repair-estimate.md: RA14-1
- retailer-app/inspection/15-completing-and-signing-off.md: RA15-2
- retailer-app/after/16-viewing-and-sharing-the-report.md: RA16-1, RA16-2, RA16-3, RA16-4
- retailer-app/after/17-inviting-a-customer-to-self-inspect.md: RA17-1, RA17-2
- retailer-app/after/18-working-offline.md: RA18-1, RA18-2
- retailer-app/help/20-tips-for-good-captures.md: RA20-1, RA20-2, RA20-3
- retailer-app/help/21-troubleshooting-and-faq.md: RA21-1
- web-dashboard: all slots (WD01-1; WD02-1 to 3; WD03-1, 2; WD05-1 to 3; WD06-1; WD07-1, 2; WD08-1 to 10; WD09-1; WD10-1 to 3)

---

## Summary

**Verdict counts (54 embedded instances at review time)**

| Verdict | Count | Status after edits |
|---|---|---|
| OK | 36 | unchanged |
| Add caption | 9 | all applied (incl. RA09-2 reword) |
| Mismatch | 3 | RA13-9 fixed; RA07-3 interim caption, recapture pending; RA13-2 deferred with note |
| Redundant | 6 | all removed |
| Improve caption / Add context | 0 | - |

48 embedded instances remain after the removals.

**Best shape:** 13-reviewing-damage (the add/remove damage flow is fully illustrated, captions accurate), 06-start-an-inspection, 08-capturing-interior-images, 15-completing-and-signing-off - text and images track each other closely.

**Worst shape:** 12-completing-the-checklist (1 duplicate + 1 triple-repeat of the same asset, unlabeled stack), 11-tyre-inspection (2 redundant instances, 1 misleading), 07-capturing-exterior-images (the Manual-toggle mismatch).

**Top edits, in order**

1. ~~Fix the RA07-3 mismatch~~ DONE (interim): honest caption added; capturing the toggle-on state is still the proper fix.
2. ~~Remove the five clear duplicates~~ DONE: RA12-2, RA12-6, RA12-7, RA11-2, RA11-8 all removed (RA13-6 removed too).
3. ~~Correct the RA13-9 step text~~ DONE.
4. Resolve the legend inconsistency on 13-reviewing-damage - DEFERRED by decision; note added to screenshots.md. Still open.
5. ~~Blur the plate and VIN in the 8 assets~~ DONE and visually verified.
6. ~~Add the 9 suggested captions~~ DONE (RA09-2 additionally reworded - no real-time detection on the cluster).

**Still open:** RA13-2 build alignment (item 4), RA07-3 toggle-on recapture, and all pending placeholder captures.

---

## Blur applied to new captures - 8 Jul 2026

New Web Dashboard + Retailer App captures added in the 8 Jul batch. Sensitive regions blurred (Gaussian). These are done - do not re-blur; only flag any NEW exposure.

| Asset | Blurred |
|---|---|
| WD02-1.png | User ID email (vaibhav+cqretailer@clearquote.io) |
| WD02-3.png | Profile name line (vaibhav, CQ Retailer Test); Logout left visible |
| WD05-2.png | First name, last name, email, VIN, engine number, chassis number |
| WD06-1.png | Name column, Registration No column, VIN column |
| WD07-1.png | Vehicle Info column (reg + VIN); "Created by" person names (vaibhav, vishal); "JLR Retailer Internal" left visible |
| WD08-1.png | Report no, Quote ID, Created by, engine number, chassis number. Repair-estimate prices left visible by request |
| RA05-2.png | Menu identity (vaibhav / CQ Retailer Test) |
| RA18-1.png / RA18-2.png | App-home plate D93B80035B |
| RA06-1-location.png | Location map thumbnail |

Kept visible by decision: repair-estimate GBP prices (WD08-1); "JLR Retailer Internal" role label.

## Blur applied to offline-flow captures - 14 Jul 2026

Offline-flow captures added for `18-working-offline` (RA18-4 to RA18-10). Registration on the home-screen cards blurred (Gaussian), matching RA18-1 / RA18-2. Done - do not re-blur; only flag any NEW exposure.

| Asset | Blurred |
|---|---|
| RA18-7.png | Both card regs (D8708T7 Upload Due card, D870085 Completed card) |
| RA18-8.png | Both card regs (D8708T7, D870085); "Unable to initiate upload" toast left visible |
| RA18-9.png | Both card regs (D8708T7 Review Due card, D870085 Completed card) |
| RA18-4.png / RA18-5.png / RA18-6.png / RA18-10.png | No registration or personal data on screen - nothing to blur |

Kept visible by decision: vehicle model names (Range Rover Sport / Velar); GBP 0 estimate values; dates and times.

## Blur applied - exterior manual-capture screen - 14 Jul 2026

`RA07-6.png` (fills the "If your overlay stays white" placeholder on `07-capturing-exterior-images`).

| Asset | Blurred |
|---|---|
| RA07-6.png | Physical number plate on the vehicle (BK25 UBF) and the small "drivepivotal.com" watermark beneath it |

Kept visible by decision: vehicle make/model badges (Discovery / Land Rover); required-views list; background factory setting.
