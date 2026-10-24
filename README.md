# FTC Build Journal — Bambu Lab H2C

Build files, design iterations and print histories for FTC robotics. A shared record of what we built, why we changed it and what we learned, with evidence that can support the engineering notebook.

FTC 機器人製作紀錄：分享設計檔、列印歷程、測試結果與改版原因，作為工程筆記的參考資料。

**First build:** [Bot side panels — cut v1](builds/bot-side-panels/), a large panel split into four printable pieces. Original project, sketch, plate previews and settings inspection are recorded; physical print results are pending. FTC printing is planned to follow WRG completion.

## Browse the project

| Area | What to find |
|---|---|
| [Builds](builds/) | Design files, revisions, decisions and test evidence for each mechanism or part |
| [Print history](print-history/) | Dated print attempts, settings, outcomes and follow-up changes |
| [Engineering notebook](notebook/) | Evidence index and prompts for turning build work into notebook entries |
| [H2C projects](H2C/) | Tested print projects linked to their build revisions and print records |
| [WIP](WIP/) | Experiments and untested project files |
| [Original source files](Original%20STLs/) | Unmodified source meshes and provenance |
| [Printer setup](profiles/H2C-SETUP.md) | H2C hardware, material and calibration record |
| [Next work](PRINT-QUEUE.md) | Upcoming builds and experiments |
| [Shared snapshots](releases/) | Notes for optional downloadable milestones |
| [Archive](archive/) | Superseded files retained for traceability |

## Record a build

1. Create `builds/<build-name>/` using the [build template](builds/TEMPLATE.md). Keep design sources and revisions with the build.
2. Record the problem, constraints, alternatives and reason for the chosen design. Link each printed revision to its exact source and `.3mf`.
3. Add a dated [print record](print-history/TEMPLATE.md) for each attempt, including failures. Record actual hardware/material, settings, sliced estimates, measured outcomes and photos.
4. Link testing and the resulting design decision in the build record. Add useful evidence to the [notebook index](notebook/README.md).

Distinguish observed results from assumptions and sliced estimates. Keep failed iterations: they explain how the design improved. This journal supports notebook writing; it does not by itself establish competition compliance.

## Get shared files

Browse a build folder for its source and revision history. Download a `.3mf` using **Download raw file**. Optional GitHub Releases can collect useful build milestones; no release is available yet. Check the linked test status before reusing a file.

The primary printer is **Bambu Lab H2C**. Kyle's official-kit hotend inventory and intended Bambu PETG Basic are recorded in the setup record. Actual installation, chosen hotend, plate, spool mapping and colour remain to be confirmed. Use official H2C profiles, then verify the exact project in Bambu Studio before printing. WRG P2S/X2D machine settings do not establish H2C hardware settings.

[WRG Mass Printing](https://github.com/Kowls0419/WRG-MASS-PRINTING) is a separate project.
