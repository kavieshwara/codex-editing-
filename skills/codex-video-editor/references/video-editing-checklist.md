# Video Editing Checklist

## Before Editing

- Inspect source duration, resolution, FPS, and audio.
- Confirm if the source already has burned-in captions.
- Extract audio when transcription is needed.
- Build a beat map from the transcript.
- If a reference video is provided, write a short style analysis before designing.
- Decide the color palette before designing graphics.
- Pick a different style direction from the previous edit unless the user asks for the same one.

## Layout

- Use a true 50/50 split when requested.
- Make the top motion area fully visible.
- Keep the speaker visible in the lower half.
- Avoid large empty black gaps.
- Keep captions centered at the separator.

## Motion Graphics

- Build a different composition every 3-4 seconds.
- Match each visual to the spoken concept.
- Use clean, readable labels.
- Animate entry, active state, and exit.
- Avoid too many colors.
- Check that the motion graphics are not the same repeated visual from earlier videos.

## Captions

- Use phrase-level captions.
- Highlight only important words.
- Keep lines short enough for mobile.
- Check that captions do not collide with faces or graphics.

## Sound

- Add subtle SFX only at meaningful moments.
- Keep SFX gain low compared with voice.
- Avoid placing effects too close together.
- Verify the final mix does not hide speech.

## Verification

- Render preview stills at early, middle, and late frames.
- Visually inspect crop, text, colors, and overlap.
- Compare previews to the chosen reference/style direction.
- Reject the output if it looks like the previous template without a clear reason.
- Run lint or type checks if code was edited.
- Render final MP4.
- Run ffprobe on final output.
- Put final videos in an easy-access final folder.
