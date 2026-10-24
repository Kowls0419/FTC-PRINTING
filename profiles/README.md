# H2C profiles

Start with [H2C-SETUP.md](H2C-SETUP.md). The installed Bambu Studio 02.08.02.61 contains H2C machine presets for 0.2, 0.4, 0.6 and 0.8 mm, including `Bambu Lab H2C 0.4 nozzle` and `0.20mm Standard @BBL H2C`. These are available presets; Kyle's reported official-kit inventory and intended Bambu PETG Basic are recorded in H2C-SETUP.md. Actual installed configuration and selected print hotend still require verification.

`installed-profile-index.json` records names and SHA-256 hashes of the locally inspected factory preset files, dated 2026-10-22. It is a provenance index, not an importable or team-calibrated profile. Factory preset inheritance must be resolved through Bambu Studio before comparing effective settings.

## Creating or porting a project

Use the `bambu-3mf` and `reflect` skills. Back up source projects and preserve original meshes. Start with an H2C project saved from the actual target setup; use a validated same-printer/nozzle/material donor when available.

- Preserve target H2C machine limits, clearances, retraction, nozzle geometry and G-code. Port deliberate process choices individually.
- Preserve physical wall and shell thickness when changing line width or layer height; document before/after thickness in millimetres.
- Preserve existing JSON keys and list-length invariants during ordinary project-setting edits. Schema changes for geometry or embedded preset repair require explicit validation.
- Check active extruder and filament/nozzle mapping before editing multi-extruder arrays. Never tile arrays by position to make their lengths match. Validate coupled filament variant, self-index and mapping arrays together.
- Keep `different_settings_to_system` complete and verify it explicitly after every Studio save. Check `print_settings_id` and embedded process/filament preset identities agree.
- Validate ZIP CRC, JSON, XML, mesh counts, relationships, placements and bed clearance. Native GUI import and slicing of the exact final file are required; supplying external CLI settings can mask embedded-preset failures.
- Keep new material flow and pressure-advance calibration separate from another filament's tuning. Use manufacturer specifications for material facts and record unverified values clearly.

Reference: [Bambu Lab's official H2C introduction](https://blog.bambulab.com/bambu-lab-h2c-where-multi-material-vortek-system-meets-engineering-precision/).
