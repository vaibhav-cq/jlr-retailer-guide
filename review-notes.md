# Review notes

Open items and inconsistencies noted during the guide review. None of these break the published site. They are things to fix or revisit later.

## Comparison section removed

The **Assessment / Comparison** section has been trimmed to **Assessment** only. What was taken out:

- The "/ Comparison" part of the heading in `web-dashboard/inspection-reports/08-understanding-the-report.md`, plus the paragraph describing the repeat-inspection comparison view.
- The **Comparison** glossary entry in `shared/glossary.md`, and the trailing comparison sentence on the **Assessment table** entry.
- The "(or Existing Damages when vehicle comparison is enabled)" note on the **Damage review** glossary entry.

The Comparison feature is real product behaviour: when a vehicle with the same licence plate is inspected again, a Comparison section replaces the assessment section and compares the current inspection against the previous one, with filters for New damages, Existing Damage, Repaired, Clear and Unrecognized. It was removed because it is out of scope for the current pilot.

**If this feature is enabled for retailers in future, the section and its glossary entries will need to be added back.** Screenshot slot `WD08-10` was reserved for the comparison view and is still listed in `screenshots.md`.

## Tracker vs page mismatch: demo-r42.png

`demo-r42.png` is marked Attached in `screenshots.md` for the reviewing-damage overview slot, but it is not actually embedded in `12-reviewing-damage.md`. Either add the image to the page or change the slot status in the tracker.

## Orphaned assets

23 images sit in `.gitbook/assets/` but are not referenced by any page. Most match capture slots still open in `screenshots.md` (for example `RA14-*`, `RA18-*`) or look like spare demo frames (`demo-r01` to `demo-r04`, `demo-r46`). Worth a cleanup pass once the remaining captures are placed.

## Slot ID exceptions after renumbering

The tyre page moved to position 13, and its slot IDs were renumbered from `RA11-*` to `RA13-*`. Two slots were kept as `RA11-10` and `RA11-11` on purpose, because those IDs are also the asset filenames (`RA11-10.png`, `RA11-11.png`) that we agreed to leave unchanged. So the tyre page (`13-tyre-inspection`) still owns two `RA11`-prefixed slots. This is intentional, recorded here so it is not read as an error.

## Tyre tread feature: test findings and open points

Documented on the tyre page from testing: tread readings accept up to 20 mm, entry is allowed to two decimal places, and a reading of 3 mm or below is shown in red to flag low tread.

Open points to confirm against the source of truth (the Figma prototype, or Arjun and Devnarayan):

- The 3 mm red threshold is an observed value, not a documented one. Neither the tyre tread PRD nor the tyre info detection PRD states the number; they only describe the wheel icon turning red when tread is below an "acceptable limit". Confirm whether 3 mm is fixed for all dealers or driven by config or tyre spec, since the guide should not state a dealer-variable value as universal.
- The 20 mm cap and the two-decimal precision are also not in either PRD. Both point to the Figma prototype as the source of truth for UI behaviour. Verify there.

Cross-PRD conflict to resolve before documenting the web side: the tyre tread PRD says tread is not editable on the web, while the newer tyre info detection PRD says users can edit the tread values in the web modal. The newer doc is likely correct, but confirm before adding anything to the web dashboard section.

Optional guide addition: the tyre overview has a separate right-side indicator for whether all four tyres match on brand, model, size and rating (green if all match, red if they differ, with a proposed orange for incomplete data). Not currently documented.
