# HANDOFF

## Goal
Create a public FTC build journal and file library focused on the Bambu Lab H2C: build revisions, print histories and evidence useful for the engineering notebook.

## Done
- Prepared README, build/revision and print-attempt templates, notebook evidence index, next-work list and H2C setup/profile references.
- Inspected official H2C profiles in Studio 02.08.02.61 on 2026-10-22. Installed hardware is still unrecorded.
- Kyle authorised installation, public repository creation and initial commit/push on 2026-10-24.
- Kyle clarified this is build logging/sharing, not mass printing. Updated the structure before initial publication.

## In progress
- Initial publication complete: public Kowls0419/FTC-PRINTING, main branch; initial commit ec5b0c7 and uploaded source verified via GitHub API.

## Next
1. Verify actual H2C installation and select side-panel hotend/plate/colour; intended material is Bambu PETG Basic.
2. Inspect source plate1/4 non-manifold edges in Studio before creating a separate H2C print revision.
2. After WRG finishes, record FTC print attempts, tests and resulting design decisions.
3. Link useful evidence to notebook entries as the team develops them.

## Gotchas
- First FTC design is archived: builds/bot-side-panels/source/cut.3mf. No calibrated team H2C profile or physical print result is recorded.
- No automatic printer scheduler is configured; WRG completion is unconfirmed.
- Preserve failed iterations and actual attempt settings; distinguish estimates from observations.

## Delegated

### Codex: FTC build journal setup (2026-10-24)
- **Status:** Complete: 27-file journal and first-build record published; all local Markdown links/JSON validated, source byte-identical, remote commit/source verified.
- **Files changed:** root docs, builds/ and print-history/ templates, notebook/ index, H2C/, WIP/, Original STLs/, profiles/, releases/, archive/ docs and .gitignore.
- **Commands run:** read WRG context and bambu-3mf/reflect skills; checked GitHub repo/Pages state; inspected local factory H2C JSON; generated scaffold; validated Markdown links/JSON; installed with byte comparison; git init and GitHub repository creation.
- **Findings:** FTC is a build journal and shared file library, not a production tracker. Official preset availability does not confirm installed hardware. No 3mf edits or printing performed.
- **Kyle/Claude check:** supply first design and actual H2C setup; preserve dated evidence for notebook reference.

### Codex: first build — bot side panels (2026-10-24)
- **Status:** source archived unchanged; H2C conversion and printing not performed.
- **Files:** builds/bot-side-panels/ source, sketch, 4 stored previews, inspection JSON and guide; README, build index, next-work list, notebook index and changelog updated.
- **Commands/checks:** ZIP CRC; XML/JSON parse; component/object mapping, triangle indices/mesh_stat, transformed dimensions, edge incidence; source SHA256 and byte comparison. Native GUI import and fresh slice not performed.
- **Findings:** 4 objects/4 plates, original title FTC Board Cut v1; embedded P2S0.6HF, blackPLA slot1,0.3layers/2walls/3-3shells/15%infill/no support. Override list absent in source; preserved unchanged. No estimates or physical outcomes invented.
- **Kyle/Claude check:** actual H2C setup, required panel quantity, joining method, dimensions/fit and joint tests remain unrecorded.

### Codex: H2C kit and source mesh findings (2026-10-24)
- **Hardware evidence:** Kyle reports official kit8hotends: right4×0.4 +0.2+0.6 induction; left2×0.4standard; expected preinstalled0.4each. Intended filament Bambu PETG Basic; colour/plate/chosenhotend/mapping unconfirmed. No high-flow assumption.
- **Mesh evidence:** source plate1 has805edges with4incidenttriangles, plate4has667; exact-coordinate welding leaves counts unchanged. Plates2/3all2incidentfaces. Originalsourceunchanged; no claim of printability or successful repair.
- **Publication scope:** public FTC buildjournal and firstsource/sketch authorised by Kyle; commit/push requested earlier. No live printing or source conversion performed.
