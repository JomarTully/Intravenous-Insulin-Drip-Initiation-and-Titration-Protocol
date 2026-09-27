# IV insulin infusion calculator — review draft

Open `index.html` in a browser. For GitHub Pages, upload `index.html` to the repository root, then enable Pages for the main branch / root. On iPhone, open the Pages URL in Safari and choose Share → Add to Home Screen. The page has no dependencies and does not store or transmit entered values.

Source: user-supplied Clinical Nursing Policy Manual CC010, Appendix A, Insulin Infusion Protocol, revised March 23, 2023. The app includes initiation, hourly adjustment, BG <100 and ≤70 holds, 60-minute hold, restart, and DKA/HHS prompts. This is an unvalidated transcription for institutional clinical review, not a substitute for the current policy or patient orders.

Points requiring clinical policy-owner review: the rate table omits exactly 25 units/hr; the strict restart thresholds are >180 for others and >140 post-cardiothoracic surgery; the 50% restart or reduction can yield quarter-unit rates even though general infusion increments are 0.5 units/hr. The source provides no rounding rule for those cases, so the app shows the arithmetic result and asks for review. The 60-minute hold requires another BG check; it never automatically restarts. The app does not infer actions outside the table or remember a previous rate across sessions.

For previous BG >400 mg/dL, a drop of exactly 50 mg/dL is also unspecified in the source table; the calculator flags it for review.
