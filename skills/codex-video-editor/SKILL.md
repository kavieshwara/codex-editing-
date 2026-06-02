---
name: codex-video-editor
description: Use when editing or creating short-form videos with Codex, especially premium 9:16 business, AI, SaaS, podcast, educational, talking-head, motion-graphic, captioned, or social-media videos. Guides transcript analysis, motion graphics, captions, sound design, preview QA, and final MP4 export.
---

# Codex Video Editor

Act as a professional short-form video editor. Build the edit from the transcript first, then design visuals that match the meaning of each spoken beat.

## Default Deliverable

- Format: `9:16`
- Resolution: `1080x1920`
- FPS: `30`
- Top 50%: motion graphics
- Bottom 50%: talking head or source video
- Captions: centered in the middle separator band
- Motion change: every 3-4 seconds
- Palette: 2-3 colors unless the user explicitly asks for more
- Export: H.264 MP4

## Editing Workflow

1. Inspect the source with FFmpeg or ffprobe.
2. Extract or read the transcript.
3. Split the transcript into 3-4 second beats.
4. Assign one meaningful visual idea per beat.
5. Keep the speaker visible and professionally framed.
6. Put captions in the center separator, not over the speaker face.
7. Add subtle sound effects only when they support the message.
8. Render early, middle, and late preview stills.
9. Fix crop, overlap, blank scenes, caption size, and color issues.
10. Render the final MP4 and verify resolution, FPS, duration, and file size.

## Motion Graphics Rules

Choose visuals based on the spoken concept:

- Comparison: split cards, VS layout, score lanes
- Execution: repo tree, task queue, terminal, progress line
- Tools: connected nodes, cursor actions, UI cards
- Reviews: risk matrix, architecture graph, tradeoff cards
- Cost or speed: counters, bars, meters
- Workflow: build-review loop, handoff arrows, final system diagram

Hard rules:

- Do not repeat one graphic template for the whole video.
- Do not use random visuals that do not match the words.
- Keep graphic text mobile-readable.
- Use one primary idea per scene.
- Avoid cheap spins, flashes, meme zooms, and overcrowded screens.

## Caption Rules

- Use short phrase captions, not awkward one-word fragments.
- Highlight important terms: tools, model names, numbers, pros, cons, benefits.
- Keep captions in the center band for split-screen edits.
- Use high contrast, usually yellow/white text with a dark shadow or stroke.
- Never cover the speaker's face unless the user specifically asks for that style.

## Sound Design Rules

- Use SFX as support, not decoration.
- Use whooshes for section changes.
- Use clicks for UI moments.
- Use keyboard sounds for coding or writing moments.
- Use dings for success or key conclusions.
- Use impacts for strong claims.
- Keep effects subtle and spaced apart.

For a detailed beat checklist, read `references/video-editing-checklist.md`.
