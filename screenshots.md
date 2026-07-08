# Screenshot status & capture list

Single source of truth for every image slot in the guide. The old inline `[Screenshot: …]` placeholders have been **removed from the pages**, so nothing renders as raw text on the live site. Use this table to see what is attached, what still needs a capture, where each goes, and what to shoot first.

**Status:** 78 attached · 17 to capture · 2 reuse — 97 slots total. _(updated 8 Jul 2026)_

**Priority:** 🔴 18 must-have (do before go-live) · 30 can follow after go-live.

**Legend** — Status: ✅ in the page · ⬜ needs a fresh capture · ♻️ reuse another slot's image. Priority: 🔴 needed before Stratstone uses the guide · Follow = fine to backfill later · — = already done.

To attach one: capture the screen, save it into `.gitbook/assets/`, then in the listed page add `![](../../.gitbook/assets/your-file.png)` at the listed position, with a blank line before any caption. **Leave the alt text empty** — GitBook renders image alt text as a visible caption, so putting the ID there makes "RA06-2" etc. show under the picture; the ID lives in the trailing HTML comment instead (invisible on the site, still greppable in the repo).

| ID | Page › Section | Position | Status | Priority | Asset / what to capture |
|---|---|---|---|---|---|
| RA01-1 | `01-about-clearinspect` › What you can do | Intro | ✅ Attached | — | `demo-r46.png` |
| RA02-1 | `02-installing-the-app` › Install ClearInspect | Step 5 | ✅ Attached | — | `RA02-1.png` |
| RA02-2 | `02-installing-the-app` › Open the app | Step 2 | ⬜ Capture | Follow | Device home screen showing the ClearInspect icon |
| RA03-1 | `03-signing-in` › Sign in | Step 4 | ✅ Attached | — | `demo-r01.png` |
| RA03-3 | `03-signing-in` › Forgot your password? | Step 3 | ✅ Attached | — | `RA03-3.png` |
| RA03-2 | `03-signing-in` › Accepting the Terms & Conditions | Step 2 | ✅ Attached | — | `demo-r02.png` |
| RA04-1 | `04-the-home-screen` › — | Intro | ✅ Attached | — | `demo-r03.png` |
| RA04-2 | `04-the-home-screen` › Resume an inspection | Step 2 | ⬜ Capture | Follow | Retailer app → home → a card marked "In progress" |
| RA05-2 | `05-changing-the-language` › Change the language | Step 3 | ✅ Attached | — | `RA05-2.png` |
| RA06-1 | `06-start-an-inspection` › Before you start | Step 3 | ✅ Attached | — | `RA06-1-camera.png` + `RA06-1-location.png` |
| RA06-2 | `06-start-an-inspection` › Scan the number plate | Step 1 | ✅ Attached | — | `demo-r04.png` |
| RA06-5 | `06-start-an-inspection` › Scan the number plate | Step 2 | ✅ Attached | — | `demo-r05.jpg` |
| RA06-6 | `06-start-an-inspection` › Scan the number plate | Step 3 | ✅ Attached | — | `demo-r06.png` |
| RA06-3 | `06-start-an-inspection` › Confirm the vehicle details | Step 2 | ✅ Attached | — | `demo-r07.png` |
| RA06-4 | `06-start-an-inspection` › Confirm the vehicle details | Step 2 | ⬜ Capture | Follow | Retailer app → vehicle lookup → "enter manually" fields |
| RA06-7 | `06-start-an-inspection` › Select the bodystyle | Step 2 | ✅ Attached | — | `demo-r08.png` |
| RA07-5 | `07-capturing-exterior-images` › How the guided flow works | Intro | ✅ Attached | — | `demo-r09.jpg` |
| RA07-1 | `07-capturing-exterior-images` › How the guided flow works | Intro | ✅ Attached | — | `demo-r10.jpg` |
| RA07-2 | `07-capturing-exterior-images` › Capture the exterior | Step 6 | ✅ Attached | — | `demo-r11.jpg` |
| RA07-3 | `07-capturing-exterior-images` › Using the Manual toggle | Step 3 | ✅ Attached | — | `demo-r10.jpg` |
| RA07-4 | `07-capturing-exterior-images` › Finishing capture: upload screen | Step 2 | ✅ Attached | — | `demo-r16.jpg` |
| RA08-1 | `08-capturing-interior-images` › How interior capture works | Intro | ✅ Attached | — | `demo-r13.jpg` |
| RA08-2 | `08-capturing-interior-images` › Capture the interior | Step 5 | ✅ Attached | — | `demo-r12.jpg` |
| RA09-1 | `09-capturing-the-instrument-cluster` › Turn the ignition on | Intro | ✅ Attached | — | `demo-r14.jpg` |
| RA09-2 | `09-capturing-the-instrument-cluster` › Capture the cluster | Step 3 | ✅ Attached | — | `demo-r15.jpg` |
| RA09-3 | `09-capturing-the-instrument-cluster` › What the app reads | Intro | ✅ Attached | — | `demo-r17.png` |
| RA10-1 | `10-keys-charging-cable-and-other-captures` › Answer the item questions | Step 4 | ⬜ Capture | Follow | Retailer app → end of capture → the extra-items step |
| RA11-1 | `11-tyre-inspection` › Open the Tyre tab | Step 3 | ✅ Attached | — | `demo-r37.png` |
| RA11-3 | `11-tyre-inspection` › Wheel status legend | Intro | ⬜ Capture | Follow | Retailer app → Tyres section → the 4-tyre match indicator |
| RA11-4 | `11-tyre-inspection` › Reading and editing tyre information | Intro | ✅ Attached | — | `demo-r38.jpg` |
| RA11-9 | `11-tyre-inspection` › Reading and editing tyre information | Step 3 | ✅ Attached | — | `demo-r39.png` |
| RA11-5 | `11-tyre-inspection` › Entering tyre tread depth | Step 4 | ✅ Attached | — | `demo-r41.png` |
| RA11-6 | `11-tyre-inspection` › Confirming tyre and alloy damage | Intro | ✅ Attached | — | `demo-r40.jpg` |
| RA11-7 | `11-tyre-inspection` › Marking a tyre for replacement | Step 2 | ✅ Attached | — | `demo-r40.jpg` |
| RA12-1 | `12-completing-the-checklist` › — | Intro | ✅ Attached | — | `demo-r17.png` |
| RA12-3 | `12-completing-the-checklist` › Instrument cluster readings [1/3 - 3/3] | Intro | ✅ Attached | — | `demo-r18.png` |
| RA12-4 | `12-completing-the-checklist` › Instrument cluster readings [1/3 - 3/3] | Intro | ✅ Attached | — | `demo-r19.png` |
| RA12-5 | `12-completing-the-checklist` › Other Checks [1/7 - 7/7] | Step 3 | ✅ Attached | — | `demo-r20.png` |
| RA12-8 | `12-completing-the-checklist` › Save the checklist | Intro | ✅ Attached | — | `demo-r21.png` |
| RA13-1 | `13-reviewing-damage` › — | Intro | ✅ Attached | — | `demo-r22.png` |
| RA13-2 | `13-reviewing-damage` › The overview screen | Intro | ✅ Attached | — | `demo-r42.png` |
| RA13-3 | `13-reviewing-damage` › Review a section | Step 4 | ✅ Attached | — | `demo-r23.jpg` |
| RA13-15 | `13-reviewing-damage` › Review a section | Step 4 | ✅ Attached | — | `demo-r33.jpg` |
| RA13-9 | `13-reviewing-damage` › Add a damage manually | Step 2 | ✅ Attached | — | `demo-r25.jpg` |
| RA13-12 | `13-reviewing-damage` › Add a damage manually | Step 3 | ✅ Attached | — | `demo-r26.jpg` |
| RA13-13 | `13-reviewing-damage` › Add a damage manually | Step 3 | ✅ Attached | — | `demo-r27.jpg` |
| RA13-4 | `13-reviewing-damage` › Add a damage manually | Step 4 | ✅ Attached | — | `demo-r28.jpg` |
| RA13-14 | `13-reviewing-damage` › Add a damage manually | Step 4 | ✅ Attached | — | `demo-r32.jpg` |
| RA13-10 | `13-reviewing-damage` › Add a damage manually | Step 5 | ✅ Attached | — | `demo-r29.png` |
| RA13-5 | `13-reviewing-damage` › Add a damage manually | Step 6 | ✅ Attached | — | `demo-r30.jpg` |
| RA13-11 | `13-reviewing-damage` › Add a damage manually | Step 7 | ✅ Attached | — | `demo-r31.jpg` |
| RA13-8 | `13-reviewing-damage` › Remove a damage | Step 3 | ✅ Attached | — | `demo-r34.jpg` |
| RA13-16 | `13-reviewing-damage` › Remove a damage | Step 3 | ✅ Attached | — | `demo-r35.jpg` |
| RA13-7 | `13-reviewing-damage` › Finishing the review | Step 3 | ✅ Attached | — | `demo-r44.png` |
| RA14-1 | `14-condition-grading-and-repair-estimate` › — | Intro | ✅ Attached | — | `WD08-9.png` (reuse WD08-9) |
| RA15-1 | `15-completing-and-signing-off` › Sign off | Step 3 | ✅ Attached | — | `demo-r44.png` |
| RA15-3 | `15-completing-and-signing-off` › Sign off | Step 3 | ✅ Attached | — | `demo-r45.png` |
| RA15-2 | `15-completing-and-signing-off` › The in-app report opens | Intro | ♻️ Reuse | 🔴 Must-have | Reuse **RA16-1** — In-app report opens after sign-off |
| RA16-1 | `16-viewing-and-sharing-the-report` › In the app | Intro | ⬜ Capture | 🔴 Must-have | Retailer app → after sign-off → the in-app report |
| RA16-2 | `16-viewing-and-sharing-the-report` › On the web dashboard | Step 5 | ✅ Attached | — | `WD07-1.png` (reuse WD07-1) |
| RA16-3 | `16-viewing-and-sharing-the-report` › On the web dashboard | Step 5 | ✅ Attached | — | `WD08-1.png` (reuse WD08-1) |
| RA16-4 | `16-viewing-and-sharing-the-report` › Download and share | Intro | ♻️ Reuse | 🔴 Must-have | Reuse **WD10-1** — Web: download / share PDF |
| RA17-1 | `17-inviting-a-customer-to-self-inspect` › Send an invite | Step 8 | ✅ Attached | — | `WD05-1.png` (reuse WD05-1) |
| RA17-2 | `17-inviting-a-customer-to-self-inspect` › Track your invites | Intro | ✅ Attached | — | `WD06-1.png` (reuse WD06-1) |
| RA18-3 | `18-working-offline` › Turn Offline Mode on | Intro | ✅ Attached | — | `demo-r04.png` |
| RA18-1 | `18-working-offline` › What works offline | Intro | ✅ Attached | — | `RA18-1.png` |
| RA18-2 | `18-working-offline` › Make sure your data syncs | Intro | ✅ Attached | — | `RA18-2.png` |
| RA20-1 | `20-tips-for-good-captures` › Prepare the vehicle and area | Intro | ⬜ Capture | Follow | A staged photo of a vehicle in a well-lit area with room to walk around (not an app screen) |
| RA20-2 | `20-tips-for-good-captures` › While you capture | Intro | ✅ Attached | — | `demo-r10.jpg` |
| RA20-3 | `20-tips-for-good-captures` › Before and during | Intro | ✅ Attached | — | `RA06-1-camera.png` (reuse RA06-1) |
| RA21-1 | `21-troubleshooting-and-faq` › Capturing images | Intro | ⬜ Capture | Follow | Retailer app → capture → Manual toggle state (may reuse RA07-3) |
| WD01-1 | `01-about-the-web-dashboard` › What you can do | Intro | ✅ Attached | — | `WD03-1-plain.png` (reuse WD03-1, no-box copy) |
| WD02-1 | `02-signing-in` › Step 1: Email and password | Step 3 | ✅ Attached | — | `WD02-1.png` |
| WD02-2 | `02-signing-in` › Step 2: Enter the OTP | Step 3 | ✅ Attached | — | `WD02-2.png` |
| WD02-3 | `02-signing-in` › Signing out | Intro | ✅ Attached | — | `WD02-3.png` |
| WD03-1 | `03-the-home-screen` › — | Intro | ✅ Attached | — | `WD03-1.png` |
| WD03-2 | `03-the-home-screen` › Inspection Summary | Intro | ⬜ Capture | Follow | Web dashboard → home → crop of the Inspection Summary card (Total Inspections + date filter) |
| WD05-1 | `05-creating-an-invite` › Send an invite | Step 8 | ✅ Attached | — | `WD05-1.png` |
| WD05-2 | `05-creating-an-invite` › Send an invite | Step 8 | ✅ Attached | — | `WD05-2.png` |
| WD05-3 | `05-creating-an-invite` › What the customer receives | Intro | ⬜ Capture | Follow | The invite email a customer receives (email-client screenshot) |
| WD06-1 | `06-tracking-invites` › The invite table | Intro | ✅ Attached | — | `WD06-1.png` (see text-fix note) |
| WD07-1 | `07-finding-an-inspection` › Search for an inspection | Step 3 | ✅ Attached | — | `WD07-1.png` |
| WD07-2 | `07-finding-an-inspection` › Filter results | Intro | ⬜ Capture | Follow | Web dashboard → Search → filters (status/date/retailer/inspector) |
| WD08-1 | `08-understanding-the-report` › — | Intro | ✅ Attached | — | `WD08-1.png` |
| WD08-2 | `08-understanding-the-report` › Vehicle header and details tabs | Intro | ✅ Attached | — | `WD08-2.png` (crop of WD08-1) |
| WD08-3 | `08-understanding-the-report` › JLR Topix data (JLR vehicles only) | Intro | ✅ Attached | — | `WD08-3.png` (crop of WD08-1) |
| WD08-4 | `08-understanding-the-report` › Inspection Images | Intro | ✅ Attached | — | `WD08-4.png` (crop of WD08-1) |
| WD08-6 | `08-understanding-the-report` › Tyre information | Intro | ⬜ Capture | Follow | Web dashboard → report → Tyre information section |
| WD08-5 | `08-understanding-the-report` › Assessment / Comparison | Intro | ✅ Attached | — | `WD08-5.png` (crop of WD08-1) |
| WD08-10 | `08-understanding-the-report` › Assessment / Comparison | Intro | ⬜ Capture | Follow | Capture the screen for the *Assessment / Comparison* section (was not in the original capture list) |
| WD08-7 | `08-understanding-the-report` › Checklist responses | Intro | ✅ Attached | — | `WD08-7.png` (crop of WD08-1) |
| WD08-8 | `08-understanding-the-report` › Change log | Intro | ✅ Attached | — | `WD08-8.png` (crop of WD08-1) |
| WD08-9 | `08-understanding-the-report` › Repair estimate | Intro | ✅ Attached | — | `WD08-9.png` (crop of WD08-1) |
| WD09-1 | `09-editing-damages` › Change a repair method | Step 4 | ⬜ Capture | Follow | Web dashboard → report → estimate table → change a **Repair method** cell |
| WD10-1 | `10-sharing-and-downloading` › Download a PDF | Step 3 | ⬜ Capture | 🔴 Must-have | Web dashboard → report → **Download PDF** |
| WD10-2 | `10-sharing-and-downloading` › Share the web report by email | Step 4 | ⬜ Capture | Follow | Web dashboard → report → **Share report** → email dialog |
| WD10-3 | `10-sharing-and-downloading` › Share a PDF by email | Step 4 | ⬜ Capture | Follow | Web dashboard → report → **Share PDF** → email dialog |

---

## Must-have shortlist (do before go-live)

Ten captures, ordered by criticality — several also backfill a ♻️ reuse slot, so shoot once and drop into both:

| # | Capture | Why it matters | Also fills |
|---|---|---|---|
| 1 | WD02-1 + WD02-2 | Dashboard login + OTP entry | — |
| 2 | WD08-1 | Full inspection report | RA16-3 |
| 3 | WD05-1 | Create-invite form | RA17-1 |
| 4 | WD07-1 | Search / find an inspection | RA16-2 |
| 5 | WD03-1 | Dashboard home screen | WD01-1 |
| 6 | RA16-1 | In-app report after sign-off | RA15-2 |
| 7 | RA06-1 | App camera/location permission prompts | RA20-3 |
| 8 | WD10-1 | Download PDF | RA16-4 |
| 9 | WD06-1 | Invite tracking table | RA17-2 |

## Reuse map

RA14-1 = WD08-9 · RA15-2 = RA16-1 · RA16-2 = WD07-1 · RA16-3 = WD08-1 · RA16-4 = WD10-1 · RA17-1 = WD05-1 · RA17-2 = WD06-1 · RA20-3 = RA06-1 · WD01-1 = WD03-1. (RA15-1 and RA20-2 already carry their reused image.)

## Notes

- **Image alt text is intentionally empty** on every embedded image. GitBook shows alt text as a caption, so IDs are stored in a trailing `<!-- ID -->` comment instead. Keep new images the same way.

- **WD08-10** is an extra slot on the *Assessment / Comparison* section of `08-understanding-the-report` not in the original capture list — needs the vehicle-to-vehicle comparison view, or remove the slot if that view is deferred.
- **RA13-1 / RA13-2 build mismatch:** legend reads *Damages* in RA13-1 (demo-r22) vs *Existing Damages* in RA13-2 (demo-r42); page text says "Damages". Align to one build when recapturing.
- **Blurred plates/VINs:** demo-r03, r05, r06, r07, r09, r10, r16, r46.
- **Legacy folder removed:** the old top-level `assets/` staging folder (a duplicate of `.gitbook/assets/`, unused by any page) was deleted. The one asset unique to it, the unplaced spare `demo-r36.png`, went with it — it still exists in the original source zip if ever needed.

## Defer until features ship (no slot yet)

- **Data Review / mismatch tab** — dashboard report → Data Review tab (invite vs customer vs AI).
- **Web add / delete damages** — dashboard report → Edit damages → add/delete.
- **Help wizard** — retailer app → menu → walkthrough and the "?" help icon.
