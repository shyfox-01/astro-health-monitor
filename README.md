# Untethered Health Monitor — Team TAKE

**Welcome, judges. Start with our [one-minute guided tour →](https://shyfox-01.github.io/astro-health-monitor/media/judge-guide/)**

Click **Next** through six short steps, then enter the working prototype. No login or installation is needed.

| Start here | What you will see |
| --- | --- |
| [Guided tour](https://shyfox-01.github.io/astro-health-monitor/media/judge-guide/) | The problem, four crew members' responsibilities, verification and NASA data |
| [29.5-second demo video](https://shyfox-01.github.io/astro-health-monitor/media/astro-health-monitor-narrated-720p.mp4?v=2) | The updated English narration and subtitles |
| [Live spacecraft scene](https://shyfox-01.github.io/astro-health-monitor/app.html?t=14:48&play=1&speed=10) | Kim's first-person view just before the cabin CO₂ alert |
| [Live Mars scene](https://shyfox-01.github.io/astro-health-monitor/app.html?mission=rover&t=10:01&play=1&speed=5) | A radiation warning driven by NASA Curiosity MSL-RAD data |
| [Full overview and data boundaries](https://shyfox-01.github.io/astro-health-monitor/) | Dataset use, project limitations and all app entry points |

In the spacecraft scene: **drag** to look, **G** for the watch, **T** for the tablet, **Esc** to return. Click once to enable audio. Desktop is recommended for the 3D app; the guide and video also work on mobile.

## What this repository contains

This repository hosts the **built static demo and its lightweight guided tour** (application source and private development history are not included) for the NASA Space Apps Challenge 2026 project "Untethered Health Monitor" by Team TAKE.

- Live demo: https://shyfox-01.github.io/astro-health-monitor/
- Everything runs in the browser: simulation, monitoring, self-checks, response steps and device programs.
- Simulation prototype. Crew, symptoms and faults are simulated or scripted. Real NASA data: the rover's solar particle event (Curiosity MSL-RAD surface, unscaled), the spacecraft's radiation background (Artemis I / Orion HERA) and the cabin CO₂ history (ISS EDA telemetry). The spacecraft's solar particle event is constructed from the shape of a 2017 Curiosity event. Not a medical device and not clinically validated; decision support, not diagnosis.
- The demo video's narration is AI-generated (ElevenLabs); its original background music was synthesized in code written with AI assistance.
- Crew 3D avatars: Microsoft Rocketbox (MIT). Data courtesy of NASA OSDR (EDA, RadLab) and the MSL mission. Not affiliated with or endorsed by NASA.
