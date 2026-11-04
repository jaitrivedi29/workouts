# FORM — recomp tracker

A buildless, mobile-friendly workout and meal journal. No dependencies, server, or accounts.

## GitHub Pages
1. Create a GitHub repository and upload `index.html` to its root (README optional).
2. Open repository Settings → Pages → Deploy from a branch.
3. Select `main` and `/ (root)`, save, and open the URL GitHub provides after deployment.

No GitHub account was connected or repository deployed by this delivery.

## Using it
Choose a journal date. Add meals with manually entered calories and macros. Workouts include four editable full-body templates and per-set weight, reps and completion. Track steps, ride minutes, weight, waist and notes. Edit daily targets in Settings. Zero means unset. Use Export JSON regularly; Import replaces data after confirmation.

Data is saved in browser localStorage for that origin only, with no cloud sync. Changing browsers, domains or devices will not carry logs across automatically. Export then import to move data. Private browsing and clearing site data can remove logs. Public hosting exposes the app source, not browser-local logs; do not commit exported health logs to a public repository.

## Plan assumptions
Gym access, four sessions weekly, approximately 45–60 minutes each. Monday A, Tuesday B lighter, Thursday C, Saturday D lighter. Recovery on remaining days; optional easy 30-minute Zwift rides after strength or on recovery days. Begin at 8,000 steps, near current 7–8k baseline, and increase gradually as tolerated rather than immediately targeting 15k.

Warm-up: 5–8 minutes easy cycling/walking, then 1–2 light practice sets for first lower- and upper-body exercises. Two working sets each, ~3 reps in reserve; lighter on B/D. Rest 90–120 seconds, 60–90 for isolation. Increase load only after the top of the rep range is controlled and comfortable. This is an editable general template, not a rehabilitation prescription or guarantee of pain-free movement. Exercise names can be substituted in Workouts; set/rep structure can be changed in the `initialPlans` source array before first use (saved plans take precedence afterward).

Persistent back pain warrants clinical/physio assessment before increasing load. Stop movements that worsen symptoms. Emergency assessment for new bladder/bowel changes, groin numbness or weakness in both legs.

## Nutrition
Mifflin–St Jeor estimated BMR: 10×88 + 6.25×176 − 5×29 + 5 = 1,840 kcal/day. This is an estimate of resting needs, not total maintenance expenditure. Reported 2,200–2,500 needs clarification. Calories and macros intentionally start unset; the app does not prescribe a large deficit or automatically add exercise calories.

Sources:
- https://www.nhs.uk/conditions/back-pain/
- https://acsm.org/resistance-training-guidelines-update-2026/
- https://www.cdc.gov/healthy-weight-growth/losing-weight/
