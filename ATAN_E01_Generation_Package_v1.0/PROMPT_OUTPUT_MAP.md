# Prompt → output ID → filename

This is the save-as guide missing from the original package. It assigns names before generation. It does not generate, attach, approve or upload media.

For example:

| Item | Value |
|---|---|
| Prompt | `characters/Atan/01_master_face.txt` |
| Supplies reference group | `ATAN-PROPOSED-v02` |
| Output asset ID | `ATAN-PROPOSED-v02-FACE-MASTER` |
| First downloaded filename | `ATAN-PROPOSED-v02-FACE-MASTER_take01.png` |
| Planned relative directory | `media/references/ATAN-PROPOSED-v02/` |

1. Read the adjacent folder README before using a prompt.
2. Generate only the intended image or clip, using actual inspected input references.
3. Download it and apply the exact filename. Name the asset the same way in Flow where supported.
4. Increase take01 to take02 for another attempt. Keep the original take.
5. After inspection and acceptance, record the actual file path and selected take. The stable reference ID then resolves to that actual accepted asset.

The reference group can contain multiple angles. Output asset IDs distinguish those angles. The master face, front face and left profile must not overwrite each other. A take name stays stable when approved; approval is a separate field.

All paths below are relative to ATAN_E01_Generation_Package_v1.0. Planned filenames are not present files. This repository still contains prompts and metadata only; previously generated Flow assets remain external until registered. No existing asset is automatically renamed or approved.

For automation, use [PROMPT_OUTPUT_MAP.json](PROMPT_OUTPUT_MAP.json); for a spreadsheet, use [PROMPT_OUTPUT_MAP.csv](PROMPT_OUTPUT_MAP.csv). JSON reference bindings expose producer_output_asset_ids. Character manifests and shot.json files expose the exact output names too. This mapping is additive to content revision 1.1; the existing folder and scene IDs remain unchanged.

## Character prompts

| Prompt / source selector | Output asset ID | Supplies reference | First filename |
|---|---|---|---|
| [characters/Atan/01_master_face.txt](characters/Atan/01_master_face.txt) | `ATAN-PROPOSED-v02-FACE-MASTER` | `ATAN-PROPOSED-v02` | `ATAN-PROPOSED-v02-FACE-MASTER_take01.png` |
| [characters/Atan/02_face_front.txt](characters/Atan/02_face_front.txt) | `ATAN-PROPOSED-v02-FACE-FRONT` | `ATAN-PROPOSED-v02` | `ATAN-PROPOSED-v02-FACE-FRONT_take01.png` |
| [characters/Atan/03_face_left_profile.txt](characters/Atan/03_face_left_profile.txt) | `ATAN-PROPOSED-v02-FACE-LEFT-PROFILE` | `ATAN-PROPOSED-v02` | `ATAN-PROPOSED-v02-FACE-LEFT-PROFILE_take01.png` |
| [characters/Atan/04_face_right_profile.txt](characters/Atan/04_face_right_profile.txt) | `ATAN-PROPOSED-v02-FACE-RIGHT-PROFILE` | `ATAN-PROPOSED-v02` | `ATAN-PROPOSED-v02-FACE-RIGHT-PROFILE_take01.png` |
| [characters/Atan/05_full_body_field_front.txt](characters/Atan/05_full_body_field_front.txt) | `ATAN-FIELD-PROPOSED-v02-BODY-FRONT` | `ATAN-FIELD-PROPOSED-v02` | `ATAN-FIELD-PROPOSED-v02-BODY-FRONT_take01.png` |
| [characters/Atan/06_full_body_field_rear.txt](characters/Atan/06_full_body_field_rear.txt) | `ATAN-FIELD-PROPOSED-v02-BODY-REAR` | `ATAN-FIELD-PROPOSED-v02` | `ATAN-FIELD-PROPOSED-v02-BODY-REAR_take01.png` |
| [characters/Atan/07_full_body_field_three-quarter.txt](characters/Atan/07_full_body_field_three-quarter.txt) | `ATAN-FIELD-PROPOSED-v02-BODY-3Q` | `ATAN-FIELD-PROPOSED-v02` | `ATAN-FIELD-PROPOSED-v02-BODY-3Q_take01.png` |
| [characters/Atan/08_full_body_court_front.txt](characters/Atan/08_full_body_court_front.txt) | `ATAN-COURT-PROPOSED-v02-BODY-FRONT` | `ATAN-COURT-PROPOSED-v02` | `ATAN-COURT-PROPOSED-v02-BODY-FRONT_take01.png` |
| [characters/Atan/09_full_body_court_rear.txt](characters/Atan/09_full_body_court_rear.txt) | `ATAN-COURT-PROPOSED-v02-BODY-REAR` | `ATAN-COURT-PROPOSED-v02` | `ATAN-COURT-PROPOSED-v02-BODY-REAR_take01.png` |
| [characters/Atan/10_expression_listening.txt](characters/Atan/10_expression_listening.txt) | `ATAN-PROPOSED-v02-EXPR-LISTENING` | `ATAN-PROPOSED-v02` | `ATAN-PROPOSED-v02-EXPR-LISTENING_take01.png` |
| [characters/Atan/11_expression_resolved.txt](characters/Atan/11_expression_resolved.txt) | `ATAN-PROPOSED-v02-EXPR-RESOLVED` | `ATAN-PROPOSED-v02` | `ATAN-PROPOSED-v02-EXPR-RESOLVED_take01.png` |
| [characters/Distant-Column/01_group_reference.txt](characters/Distant-Column/01_group_reference.txt) | `DISTANT-COLUMN-PROPOSED-v01-GROUP` | `DISTANT-COLUMN-PROPOSED-v01` | `DISTANT-COLUMN-PROPOSED-v01-GROUP_take01.png` |
| [characters/Officer-A/01_reference.txt](characters/Officer-A/01_reference.txt) | `OFFICER-A-PROPOSED-v01-BODY-FRONT` | `OFFICER-A-PROPOSED-v01` | `OFFICER-A-PROPOSED-v01-BODY-FRONT_take01.png` |
| [characters/Officer-B/01_reference.txt](characters/Officer-B/01_reference.txt) | `OFFICER-B-PROPOSED-v01-BODY-FRONT` | `OFFICER-B-PROPOSED-v01` | `OFFICER-B-PROPOSED-v01-BODY-FRONT_take01.png` |
| [characters/Withdrawal-Group/01_group_reference.txt](characters/Withdrawal-Group/01_group_reference.txt) | `WITHDRAWAL-GROUP-PROPOSED-v01-GROUP` | `WITHDRAWAL-GROUP-PROPOSED-v01` | `WITHDRAWAL-GROUP-PROPOSED-v01-GROUP_take01.png` |
| [characters/Worker-A/01_reference.txt](characters/Worker-A/01_reference.txt) | `WORKERS-A-PROPOSED-v01-BODY-FRONT` | `WORKERS-A-PROPOSED-v01` | `WORKERS-A-PROPOSED-v01-BODY-FRONT_take01.png` |
| [characters/Worker-B/01_reference.txt](characters/Worker-B/01_reference.txt) | `WORKERS-B-PROPOSED-v01-BODY-FRONT` | `WORKERS-B-PROPOSED-v01` | `WORKERS-B-PROPOSED-v01-BODY-FRONT_take01.png` |
| [characters/Worker-C/01_reference.txt](characters/Worker-C/01_reference.txt) | `WORKERS-C-PROPOSED-v01-BODY-FRONT` | `WORKERS-C-PROPOSED-v01` | `WORKERS-C-PROPOSED-v01-BODY-FRONT_take01.png` |

## Shot starting frames and clip outputs

The 12 animation instruction files each have separate portrait and landscape output records. Generate the selected ratio only. S03 remains an editorial locator export; its image files create optional paper texture, not geographic shapes.

| Prompt / source selector | Output asset ID | Supplies reference | First filename |
|---|---|---|---|
| [shots/E01-S01/E01-S01/image_9x16.txt](shots/E01-S01/E01-S01/image_9x16.txt) | `E01-S01-F01-9x16-PROPOSED` | `E01-S01-F01-9x16-PROPOSED` | `E01-S01-F01-9x16-PROPOSED_take01.png` |
| [shots/E01-S01/E01-S01/image_16x9.txt](shots/E01-S01/E01-S01/image_16x9.txt) | `E01-S01-F01-16x9-PROPOSED` | `E01-S01-F01-16x9-PROPOSED` | `E01-S01-F01-16x9-PROPOSED_take01.png` |
| [shots/E01-S01/E01-S01/animation.txt](shots/E01-S01/E01-S01/animation.txt) — Use the 9x16 starting frame | `E01-S01_9x16` | Finished clip | `E01-S01_9x16_take01.mp4` |
| [shots/E01-S01/E01-S01/animation.txt](shots/E01-S01/E01-S01/animation.txt) — Use the 16x9 starting frame | `E01-S01_16x9` | Finished clip | `E01-S01_16x9_take01.mp4` |
| [shots/E01-S02/E01-S02/image_9x16.txt](shots/E01-S02/E01-S02/image_9x16.txt) | `E01-S02-F01-9x16-PROPOSED` | `E01-S02-F01-9x16-PROPOSED` | `E01-S02-F01-9x16-PROPOSED_take01.png` |
| [shots/E01-S02/E01-S02/image_16x9.txt](shots/E01-S02/E01-S02/image_16x9.txt) | `E01-S02-F01-16x9-PROPOSED` | `E01-S02-F01-16x9-PROPOSED` | `E01-S02-F01-16x9-PROPOSED_take01.png` |
| [shots/E01-S02/E01-S02/animation.txt](shots/E01-S02/E01-S02/animation.txt) — Use the 9x16 starting frame | `E01-S02_9x16` | Finished clip | `E01-S02_9x16_take01.mp4` |
| [shots/E01-S02/E01-S02/animation.txt](shots/E01-S02/E01-S02/animation.txt) — Use the 16x9 starting frame | `E01-S02_16x9` | Finished clip | `E01-S02_16x9_take01.mp4` |
| [shots/E01-S03/E01-S03/image_9x16.txt](shots/E01-S03/E01-S03/image_9x16.txt) | `E01-S03-F01-9x16-PROPOSED` | `E01-S03-F01-9x16-PROPOSED` | `E01-S03-F01-9x16-PROPOSED_take01.png` |
| [shots/E01-S03/E01-S03/image_16x9.txt](shots/E01-S03/E01-S03/image_16x9.txt) | `E01-S03-F01-16x9-PROPOSED` | `E01-S03-F01-16x9-PROPOSED` | `E01-S03-F01-16x9-PROPOSED_take01.png` |
| [shots/E01-S03/E01-S03/animation.txt](shots/E01-S03/E01-S03/animation.txt) — Use the 9x16 starting frame | `E01-S03_9x16` | Finished clip | `E01-S03_9x16_take01.mp4` |
| [shots/E01-S03/E01-S03/animation.txt](shots/E01-S03/E01-S03/animation.txt) — Use the 16x9 starting frame | `E01-S03_16x9` | Finished clip | `E01-S03_16x9_take01.mp4` |
| [shots/E01-S04/E01-S04/image_9x16.txt](shots/E01-S04/E01-S04/image_9x16.txt) | `E01-S04-F01-9x16-PROPOSED` | `E01-S04-F01-9x16-PROPOSED` | `E01-S04-F01-9x16-PROPOSED_take01.png` |
| [shots/E01-S04/E01-S04/image_16x9.txt](shots/E01-S04/E01-S04/image_16x9.txt) | `E01-S04-F01-16x9-PROPOSED` | `E01-S04-F01-16x9-PROPOSED` | `E01-S04-F01-16x9-PROPOSED_take01.png` |
| [shots/E01-S04/E01-S04/animation.txt](shots/E01-S04/E01-S04/animation.txt) — Use the 9x16 starting frame | `E01-S04_9x16` | Finished clip | `E01-S04_9x16_take01.mp4` |
| [shots/E01-S04/E01-S04/animation.txt](shots/E01-S04/E01-S04/animation.txt) — Use the 16x9 starting frame | `E01-S04_16x9` | Finished clip | `E01-S04_16x9_take01.mp4` |
| [shots/E01-S05/E01-S05/image_9x16.txt](shots/E01-S05/E01-S05/image_9x16.txt) | `E01-S05-F01-9x16-PROPOSED` | `E01-S05-F01-9x16-PROPOSED` | `E01-S05-F01-9x16-PROPOSED_take01.png` |
| [shots/E01-S05/E01-S05/image_16x9.txt](shots/E01-S05/E01-S05/image_16x9.txt) | `E01-S05-F01-16x9-PROPOSED` | `E01-S05-F01-16x9-PROPOSED` | `E01-S05-F01-16x9-PROPOSED_take01.png` |
| [shots/E01-S05/E01-S05/animation.txt](shots/E01-S05/E01-S05/animation.txt) — Use the 9x16 starting frame | `E01-S05_9x16` | Finished clip | `E01-S05_9x16_take01.mp4` |
| [shots/E01-S05/E01-S05/animation.txt](shots/E01-S05/E01-S05/animation.txt) — Use the 16x9 starting frame | `E01-S05_16x9` | Finished clip | `E01-S05_16x9_take01.mp4` |
| [shots/E01-S06/E01-S06/image_9x16.txt](shots/E01-S06/E01-S06/image_9x16.txt) | `E01-S06-F01-9x16-PROPOSED` | `E01-S06-F01-9x16-PROPOSED` | `E01-S06-F01-9x16-PROPOSED_take01.png` |
| [shots/E01-S06/E01-S06/image_16x9.txt](shots/E01-S06/E01-S06/image_16x9.txt) | `E01-S06-F01-16x9-PROPOSED` | `E01-S06-F01-16x9-PROPOSED` | `E01-S06-F01-16x9-PROPOSED_take01.png` |
| [shots/E01-S06/E01-S06/animation.txt](shots/E01-S06/E01-S06/animation.txt) — Use the 9x16 starting frame | `E01-S06_9x16` | Finished clip | `E01-S06_9x16_take01.mp4` |
| [shots/E01-S06/E01-S06/animation.txt](shots/E01-S06/E01-S06/animation.txt) — Use the 16x9 starting frame | `E01-S06_16x9` | Finished clip | `E01-S06_16x9_take01.mp4` |
| [shots/E01-S07/E01-S07-A/image_9x16.txt](shots/E01-S07/E01-S07-A/image_9x16.txt) | `E01-S07-A-F01-9x16-PROPOSED` | `E01-S07-A-F01-9x16-PROPOSED` | `E01-S07-A-F01-9x16-PROPOSED_take01.png` |
| [shots/E01-S07/E01-S07-A/image_16x9.txt](shots/E01-S07/E01-S07-A/image_16x9.txt) | `E01-S07-A-F01-16x9-PROPOSED` | `E01-S07-A-F01-16x9-PROPOSED` | `E01-S07-A-F01-16x9-PROPOSED_take01.png` |
| [shots/E01-S07/E01-S07-A/animation.txt](shots/E01-S07/E01-S07-A/animation.txt) — Use the 9x16 starting frame | `E01-S07-A_9x16` | Finished clip | `E01-S07-A_9x16_take01.mp4` |
| [shots/E01-S07/E01-S07-A/animation.txt](shots/E01-S07/E01-S07-A/animation.txt) — Use the 16x9 starting frame | `E01-S07-A_16x9` | Finished clip | `E01-S07-A_16x9_take01.mp4` |
| [shots/E01-S07/E01-S07-B/image_9x16.txt](shots/E01-S07/E01-S07-B/image_9x16.txt) | `E01-S07-B-F01-9x16-PROPOSED` | `E01-S07-B-F01-9x16-PROPOSED` | `E01-S07-B-F01-9x16-PROPOSED_take01.png` |
| [shots/E01-S07/E01-S07-B/image_16x9.txt](shots/E01-S07/E01-S07-B/image_16x9.txt) | `E01-S07-B-F01-16x9-PROPOSED` | `E01-S07-B-F01-16x9-PROPOSED` | `E01-S07-B-F01-16x9-PROPOSED_take01.png` |
| [shots/E01-S07/E01-S07-B/animation.txt](shots/E01-S07/E01-S07-B/animation.txt) — Use the 9x16 starting frame | `E01-S07-B_9x16` | Finished clip | `E01-S07-B_9x16_take01.mp4` |
| [shots/E01-S07/E01-S07-B/animation.txt](shots/E01-S07/E01-S07-B/animation.txt) — Use the 16x9 starting frame | `E01-S07-B_16x9` | Finished clip | `E01-S07-B_16x9_take01.mp4` |
| [shots/E01-S08/E01-S08-A/image_9x16.txt](shots/E01-S08/E01-S08-A/image_9x16.txt) | `E01-S08-A-F01-9x16-PROPOSED` | `E01-S08-A-F01-9x16-PROPOSED` | `E01-S08-A-F01-9x16-PROPOSED_take01.png` |
| [shots/E01-S08/E01-S08-A/image_16x9.txt](shots/E01-S08/E01-S08-A/image_16x9.txt) | `E01-S08-A-F01-16x9-PROPOSED` | `E01-S08-A-F01-16x9-PROPOSED` | `E01-S08-A-F01-16x9-PROPOSED_take01.png` |
| [shots/E01-S08/E01-S08-A/animation.txt](shots/E01-S08/E01-S08-A/animation.txt) — Use the 9x16 starting frame | `E01-S08-A_9x16` | Finished clip | `E01-S08-A_9x16_take01.mp4` |
| [shots/E01-S08/E01-S08-A/animation.txt](shots/E01-S08/E01-S08-A/animation.txt) — Use the 16x9 starting frame | `E01-S08-A_16x9` | Finished clip | `E01-S08-A_16x9_take01.mp4` |
| [shots/E01-S08/E01-S08-B/image_9x16.txt](shots/E01-S08/E01-S08-B/image_9x16.txt) | `E01-S08-B-F01-9x16-PROPOSED` | `E01-S08-B-F01-9x16-PROPOSED` | `E01-S08-B-F01-9x16-PROPOSED_take01.png` |
| [shots/E01-S08/E01-S08-B/image_16x9.txt](shots/E01-S08/E01-S08-B/image_16x9.txt) | `E01-S08-B-F01-16x9-PROPOSED` | `E01-S08-B-F01-16x9-PROPOSED` | `E01-S08-B-F01-16x9-PROPOSED_take01.png` |
| [shots/E01-S08/E01-S08-B/animation.txt](shots/E01-S08/E01-S08-B/animation.txt) — Use the 9x16 starting frame | `E01-S08-B_9x16` | Finished clip | `E01-S08-B_9x16_take01.mp4` |
| [shots/E01-S08/E01-S08-B/animation.txt](shots/E01-S08/E01-S08-B/animation.txt) — Use the 16x9 starting frame | `E01-S08-B_16x9` | Finished clip | `E01-S08-B_16x9_take01.mp4` |
| [shots/E01-S09/E01-S09/image_9x16.txt](shots/E01-S09/E01-S09/image_9x16.txt) | `E01-S09-F01-9x16-PROPOSED` | `E01-S09-F01-9x16-PROPOSED` | `E01-S09-F01-9x16-PROPOSED_take01.png` |
| [shots/E01-S09/E01-S09/image_16x9.txt](shots/E01-S09/E01-S09/image_16x9.txt) | `E01-S09-F01-16x9-PROPOSED` | `E01-S09-F01-16x9-PROPOSED` | `E01-S09-F01-16x9-PROPOSED_take01.png` |
| [shots/E01-S09/E01-S09/animation.txt](shots/E01-S09/E01-S09/animation.txt) — Use the 9x16 starting frame | `E01-S09_9x16` | Finished clip | `E01-S09_9x16_take01.mp4` |
| [shots/E01-S09/E01-S09/animation.txt](shots/E01-S09/E01-S09/animation.txt) — Use the 16x9 starting frame | `E01-S09_16x9` | Finished clip | `E01-S09_16x9_take01.mp4` |
| [shots/E01-S10/E01-S10/image_9x16.txt](shots/E01-S10/E01-S10/image_9x16.txt) | `E01-S10-F01-9x16-PROPOSED` | `E01-S10-F01-9x16-PROPOSED` | `E01-S10-F01-9x16-PROPOSED_take01.png` |
| [shots/E01-S10/E01-S10/image_16x9.txt](shots/E01-S10/E01-S10/image_16x9.txt) | `E01-S10-F01-16x9-PROPOSED` | `E01-S10-F01-16x9-PROPOSED` | `E01-S10-F01-16x9-PROPOSED_take01.png` |
| [shots/E01-S10/E01-S10/animation.txt](shots/E01-S10/E01-S10/animation.txt) — Use the 9x16 starting frame | `E01-S10_9x16` | Finished clip | `E01-S10_9x16_take01.mp4` |
| [shots/E01-S10/E01-S10/animation.txt](shots/E01-S10/E01-S10/animation.txt) — Use the 16x9 starting frame | `E01-S10_16x9` | Finished clip | `E01-S10_16x9_take01.mp4` |

## Style, locations, props and manually prepared references

Inline reference prompts are selected from SOURCE_PLAN.md. Specification-only entries do not contain a dedicated generation prompt; their names reserve a destination for a manually prepared or selected asset. The style entry names a selected reviewed example of STYLE_GUIDE.md, rather than claiming the guide is already an image.

| Prompt / source selector | Output asset ID | Supplies reference | First filename |
|---|---|---|---|
| [SOURCE_PLAN.md](SOURCE_PLAN.md) — Section 5 / Empty location and prop prompts / L01 plate | `COURT-PROPOSED-v02-PLATE` | `COURT-PROPOSED-v02` | `COURT-PROPOSED-v02-PLATE_take01.png` |
| [SOURCE_PLAN.md](SOURCE_PLAN.md) — Section 5 / Empty location and prop prompts / L02 plate | `GARHGAON-APPROACH-PROPOSED-v01-PLATE` | `GARHGAON-APPROACH-PROPOSED-v01` | `GARHGAON-APPROACH-PROPOSED-v01-PLATE_take01.png` |
| [SOURCE_PLAN.md](SOURCE_PLAN.md) — Section 5 / Empty location and prop prompts / L03 plate | `WITHDRAWAL-PATH-PROPOSED-v01-PLATE` | `WITHDRAWAL-PATH-PROPOSED-v01` | `WITHDRAWAL-PATH-PROPOSED-v01-PLATE_take01.png` |
| [SOURCE_PLAN.md](SOURCE_PLAN.md) — Section 5 / Empty location and prop prompts / L04 plate | `COMMAND-SHELTER-PROPOSED-v01-PLATE` | `COMMAND-SHELTER-PROPOSED-v01` | `COMMAND-SHELTER-PROPOSED-v01-PLATE_take01.png` |
| [SOURCE_PLAN.md](SOURCE_PLAN.md) — Section 5 / Empty location and prop prompts / L05 plate | `RIVER-PROPOSED-v02-PLATE` | `RIVER-PROPOSED-v02` | `RIVER-PROPOSED-v02-PLATE_take01.png` |
| [SOURCE_PLAN.md](SOURCE_PLAN.md) — Section 5 / Seat / beam row; select only: plain low-back timber seat | `SEAT-SYMBOL-v01` | `SEAT-SYMBOL-v01` | `SEAT-SYMBOL-v01_take01.png` |
| [SOURCE_PLAN.md](SOURCE_PLAN.md) — Section 5 / Seat / beam row; select only: straight two-metre timber beam | `BEAM-PROPOSED-v01` | `BEAM-PROPOSED-v01` | `BEAM-PROPOSED-v01_take01.png` |
| [STYLE_GUIDE.md](STYLE_GUIDE.md) — Current photographic visual specification | `STYLE-E01-REAL-v01` | `STYLE-E01-REAL-v01` | `STYLE-E01-REAL-v01_take01.png` |
| [SOURCE_PLAN.md](SOURCE_PLAN.md) — Section 3 / Props / TABLE-PROPOSED-v01 | `TABLE-PROPOSED-v01` | `TABLE-PROPOSED-v01` | `TABLE-PROPOSED-v01_take01.png` |
| [SOURCE_PLAN.md](SOURCE_PLAN.md) — Section 3 / Props / BUNDLES-PROPOSED-v01 | `BUNDLES-PROPOSED-v01` | `BUNDLES-PROPOSED-v01` | `BUNDLES-PROPOSED-v01_take01.png` |
| [SOURCE_PLAN.md](SOURCE_PLAN.md) — Section 6 / E01-S03 checked geographic base or dated-text fallback | `MAP-BASE-E01-PROPOSED-v01` | `MAP-BASE-E01-PROPOSED-v01` | `MAP-BASE-E01-PROPOSED-v01_take01.png` |
| [NARRATION.txt](NARRATION.txt) — Complete voiceover | `VO-E01-PROPOSED-v01` | `VO-E01-PROPOSED-v01` | `VO-E01-PROPOSED-v01_take01.wav` |
| [SOURCE_PLAN.md](SOURCE_PLAN.md) — Section 7 / Sound, captions and edit direction | `SFX-E01-PROPOSED-v01` | `SFX-E01-PROPOSED-v01` | `SFX-E01-PROPOSED-v01_take01.wav` |
| [SOURCE_PLAN.md](SOURCE_PLAN.md) — Section 7 / Sound, captions and edit direction | `MUSIC-E01-PROPOSED-v01` | `MUSIC-E01-PROPOSED-v01` | `MUSIC-E01-PROPOSED-v01_take01.wav` |
