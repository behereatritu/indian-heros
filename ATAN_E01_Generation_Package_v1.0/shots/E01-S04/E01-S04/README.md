# E01-S04 — prompt outputs and filenames

Read the row for the prompt you use, generate the media, then download and rename it to the listed filename. Use take02, take03, etc. for retries. Names are assigned before generation; none of these planned files is registered or approved by this mapping update.

| Prompt | Output asset ID | Supplies reference | Save first take as |
|---|---|---|---|
| [image_9x16.txt](image_9x16.txt) | `E01-S04-F01-9x16-PROPOSED` | `E01-S04-F01-9x16-PROPOSED` | `E01-S04-F01-9x16-PROPOSED_take01.png` |
| [image_16x9.txt](image_16x9.txt) | `E01-S04-F01-16x9-PROPOSED` | `E01-S04-F01-16x9-PROPOSED` | `E01-S04-F01-16x9-PROPOSED_take01.png` |
| [animation.txt](animation.txt) | `E01-S04_9x16` | Finished shot clip | `E01-S04_9x16_take01.mp4` |
| [animation.txt](animation.txt) | `E01-S04_16x9` | Finished shot clip | `E01-S04_16x9_take01.mp4` |

The reference ID groups related views; the output asset ID identifies one specific view. Use the output filename as the Flow asset name where supported. Attach the actual inspected image in later shots; IDs alone do not attach media. Keep naming instructions outside the image/video prompt.

See the [complete output map](../../../PROMPT_OUTPUT_MAP.md) and [machine-readable register](../../../PROMPT_OUTPUT_MAP.json).

Required visual reference groups: `STYLE-E01-REAL-v01`, `GARHGAON-APPROACH-PROPOSED-v01`, `DISTANT-COLUMN-PROPOSED-v01`.

For image-to-video, the selected starting image is the actual frame input. Generate only the chosen aspect-ratio version. The narration stays a separate editorial track.
