# Judge's guided tour

Public entry: https://shyfox-01.github.io/astro-health-monitor/media/judge-guide/

Six short English steps with Next, Back, step navigation, arrow keys, deep links and a real app launch. If JavaScript is disabled, all steps remain readable. No third-party scripts, fonts, trackers or APIs are needed to load the tour.

The tutorial explains the existing scripted prototype; it does not dispatch crew or issue commands. Clinical decisions stay with the medical officer. It does not claim a live generative AI agent or real astronaut physiology.

The overview covers vital signs, symptoms, sleep, mood, cabin conditions, radiation and reading quality. CO₂ is one worked example. The recheck page uses oxygen sensor contact; the NASA page covers Mars radiation. Glucose monitoring and a live generative agent are not presented as implemented.

## Captures and provenance

All six images are actual prototype UI captures made on 15 November 2026. No generated illustrations are presented as software evidence.

- `cabin.webp`: first-person spacecraft scene, cropped to the viewport.
- `body.webp`: Kim's tablet at 15:12, simulation labels retained.
- `spo2-before.webp` and `spo2-after.webp`: unaltered crops of Kim’s oxygen row at 15:08:30 and 15:10; simulated readings of 91% with poor contact and 97% after remeasurement. This is a quality check, not a treatment result.
- `verification.webp`: Ana's actual action record, command success and waiting for data.
- `mars.webp`: Mars helmet display with the real-radiation / simulated-crew distinction.

Source capture records: the source repository's `A_knowledge/docs/review_C_1115` and `review_F_1115`. Data descriptions follow `A_knowledge/docs/nasa_data_submission.md`. Crew avatars in captures: Microsoft Rocketbox (MIT). NASA data credits and links appear on step 5. Tour code and editorial layout were prepared with OpenAI Codex assistance.

## Deployment

Keep this folder under `media/`: the existing app publisher preserves that directory. The public README and homepage contain links to this tour. Source-template patches are provided separately under A's submission documents so a future full-app deployment can preserve those two entry links as well.

## Validation

- All six Next states, Back, arrow navigation, step jump and refresh/deep link checked in browser.
- 390 × 844 viewport: one visible step, no horizontal overflow, all six steps.
- Local links and image paths resolve; JavaScript syntax and Git whitespace checks pass.
- Live-demo launch reaches the actual app; detail disclosure expands; no tour console errors observed.
