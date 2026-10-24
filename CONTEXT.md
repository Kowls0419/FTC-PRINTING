# FTC workspace context

Updated: 2026-10-24. Read this file alongside AGENTS.md and HANDOFF.md when switching between Claude Code and Codex.

## Purpose and preferences

- This repository mainly stores and shares FTC robot build files. It is not a mass-printing tracker.
- All repository documentation must be in English.
- Kyle is not expected to write meeting entries or duplicate the team's notebook here. Templates are optional.
- Assistants record useful facts, decisions, problems and results Kyle supplies in NOTES.md. Date each note and label its evidence source: Kyle-reported, file-inspected, measured/tested or proposed.
- The separate engineering notebook/portfolio is maintained using Kyle's Team 36444 KC Super Bee template. Repository notes and files may support it; do not fabricate notebook entries, meeting attendance, work hours or test results.

## Files and navigation

- README.md: storage navigation and current files.
- NOTES.md: dated context and decisions from Kyle and inspected files.
- HANDOFF.md: completed work, active tasks, next actions and session results.
- builds/bot-side-panels/: first supplied build, including original cut.3mf, sketch, stored plate previews and inspection.
- profiles/H2C-SETUP.md: reported kit inventory and intended material; distinguish expected hardware from inspected installation.
- notebook/README.md: optional mapping into the existing notebook, not a required journal.

## Current facts and limitations

The first source is the large bot side panel split into four smaller pieces/plates. Original cut.3mf is byte-preserved. Its embedded profile is P2S0.6HighFlow/blackPLA, not H2C/PETG. Plate1 and plate4 fail the two-faces-per-edge manifold criterion; see the inspection report. No H2C conversion, fresh slice or physical print is recorded.

Kyle reports the official H2C kit has six right induction hotends (4×0.4mm,1×0.2mm,1×0.6mm) and two left0.4mm standard hotends. One0.4mm on each side is expected pre-installed. Intended material is Bambu PETG Basic. Actual installation, selected print hotend, flow variant, colour, plate and spool mapping remain unverified.

FTC printing is planned after WRG printing finishes. Completion of WRG has not been confirmed. No automatic scheduling or live printer action is configured.

## Session handoff practice

Read AGENTS.md → HANDOFF.md → CONTEXT.md → README.md, then relevant notes and file records. Inspect actual files/git state before assuming a prior step finished. Keep stable preferences here, dated facts in NOTES.md and task state in HANDOFF.md. Append your own Claude/Codex entry under Delegated with status, files, commands/checks, findings and next checks; do not rewrite the other agent's history.

Commit/push only when Kyle asks. Initial publication was authorised and completed; do not interpret it as standing authorisation for every later change. Never send a print without Kyle's explicit instruction.
