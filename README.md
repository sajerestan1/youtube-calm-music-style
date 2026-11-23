# Omazmusic calm album video workflow

This is the repeatable process for making long-form calm music videos for Omazmusic with original music, Video Express, and Canva. Keep the project manifest updated so a later session can resume without rebuilding assets or guessing track timing.

## Creative direction

- Use original music and artwork. Study other channels for audience needs, titles, pacing, and presentation, but do not copy their music, lyrics, artwork, branding, or exact titles.
- Keep the channel character consistent: a young adult man wearing headphones and reading a book.
- Make the setting bright and welcoming, such as a sunlit apartment or spacious library. Use the channel banner's colors as the palette. Avoid very dark scenes.
- Use a 16:9 YouTube canvas at 1920 × 1080. Keep important text and the character away from the edges.
- Keep the image calm, with a fixed or nearly fixed camera, slow natural motion, and a small waveform along the bottom that does not cover the reader or book.

## Project folder and manifest

Create an album folder in the working files and media apps. Keep source audio, final mix, artwork, generated motion clips, project file, and export easy to distinguish. Use names such as `AlbumName_Track01_Title.wav` and `AlbumName_Final_90min.mp3`.

Before editing, create a project manifest with:

| Field | Record |
| --- | --- |
| Album working title | |
| Target runtime | 1:30:00 unless the user changes it |
| Video format | 1920 × 1080, 16:9 |
| Artwork filename and location | |
| Track number, exact title, source filename, duration, start, end | One row per track |
| Mix filename and measured duration | |
| Video Express project name and duration | |
| Canva design link and duration | |
| Export filename, format, resolution, measured duration | |
| Open issues and resume point | |

Do not rely on a remembered list or folder upload order. Read the actual filenames and durations. Record the final track order and calculate each start and end from the audible mix. If the mix is shortened, record which tracks were trimmed or omitted and update the timing list.

## 1. Plan the album

1. Confirm the target runtime, audience, mood, and constraints. For the first album, the goal was about 90 minutes of calm music for reading, winding down, or listening on the way home.
2. Choose a searchable, human-sounding title around the listener's use case. Avoid vague invented phrases unless they accurately describe the music and help viewers find it.
3. Finalize the tracklist before assembling the mix. Give each track a distinct title and record exact title and source filename in the manifest.
4. Make or select original tracks for this album only. Do not use unrelated audio found in a shared media library.
5. Check the total source duration against the target before editing. A playlist total and a single mixed audio file are different things; verify both.

## 2. Prepare music and track timing

1. Create each requested track in CloneVoice or the chosen music workflow. Save separate files and listen to the start and end of every file.
2. Confirm each file opens, has the expected duration, and is the intended track. Keep file names and track numbers aligned.
3. Arrange only approved album tracks in order. Create a single continuous album mix if the editor handles one mix more reliably than many audio clips.
4. Measure the mix duration after rendering. Do not assume the mix contains every source track in full.
5. Build a timestamp sheet from the actual mix. For each track, calculate `start = previous end` and `end = start + audible duration`. Confirm the final end matches the mix.
6. If the sequence or durations do not reconcile, fix the mix or manifest before adding captions or publishing. Never invent chapter times from approximate file durations.

## 3. Create the channel artwork

1. Create a bright, inviting 16:9 image of the recurring reader. Keep his headphones and book visible. Use warm banner colors, soft daylight, and a comfortable, spacious room.
2. Review the full image at 1920 × 1080. Check face, hands, book, crop, contrast, and open space at the bottom for the waveform.
3. Save the approved still in the album folder and upload it to Video Express's project media library. Keep the original still in case the motion render needs to be recreated.
4. For future albums, keep the same character identity and palette while varying room or time of day.

## 4. Generate motion in Video Express

1. Open the intended Video Express project or create one in landscape 16:9. Confirm the project before editing.
2. Open **Create with AI → Create Video From Prompt → Use from Library** and choose the approved image from the album folder. For the first album it was in `Chatgpt created`.
3. Use a motion prompt that describes restrained action and preserves the image identity. Example:

> Keep the camera fixed and preserve the same young man, headphones, clothes, book, and bright room. He looks down at the book, makes one small natural page turn, then continues reading. Add only subtle breathing and a slight posture shift. Keep the warm daylight. No camera movement, cuts, extra fingers, text, or changes to the room.

4. Keep the frame landscape 16:9. Do not enable unrelated audio or lipsync options for a music-only visual.
5. Generate one short proof clip first. Wait for completion and locate it in **Media Library → My Media**.
6. Play the clip and inspect the beginning, middle, and end. Confirm the page turn is visible, hands and book look plausible, and the face and background remain consistent. A clip can be only a few seconds; do not mistake it for a full album video.
7. If motion is unclear or distorted, adjust the prompt and regenerate within the account limits. Record the accepted clip filename and duration.
8. Decide how accepted motion will cover the full runtime before replacing or looping the existing visual track. Test a short loop for jumps. Do not claim the whole album is animated if the clip appears at only one point.
9. Save the Video Express project after meaningful changes. Do not replace existing timeline tracks until the replacement is verified.

## 5. Assemble the long video in Canva

1. Open the existing Canva design in the current tab. Do not open duplicate tabs for the same design.
2. Check that the design is 1920 × 1080, 16:9. Confirm the intended reader image, waveform, and album mix are present.
3. Place all album audio on one continuous audio lane, in order, beginning at zero. Use the final mix or the separate source tracks, never both at once.
4. Extend or loop the reader image across the full audio duration. Add approved Video Express motion only after checking its duration and repeat behavior. Keep the waveform directly above the image track in the timeline, as requested.
5. Keep all tracks on one straight audio timeline. Do not split the album across stacked audio lanes unless the user asks.
6. Save regularly and wait for Canva's saved indicator. Confirm timeline end, audio end, image end, and waveform end agree.
7. Preview the beginning, middle, and end. Check for gaps, black frames, abrupt cuts, audio ending early, or overlays drifting out of position.

## 6. Track titles, captions, and chapters

1. For instrumental music, do not use speech auto-captioning as a substitute for track titles. Canva's Captions app transcribed instrumental audio into invented lyrics on the first album. Those 365 false caption segments were removed.
2. For sung lyrics, use an accurate lyric transcript and check it against audio before publishing. Never leave hallucinated text in the video.
3. If the user wants on-screen song titles, add restrained title cards only at verified track starts. Use exact titles and measured timestamps from the manifest. Preview each changeover.
4. Add YouTube chapters in the description from the same verified timing sheet. Chapter zero must begin at `00:00`; use exact track titles and one chapter per track.
5. Do not guess track boundaries from a combined mix. If the final sequence or source lengths are unavailable, ask for them or leave the video without track captions until verified.

## 7. Export and YouTube packaging

1. Export the full timeline as MP4 at 1920 × 1080. Choose a quality setting that does not shorten or truncate the video.
2. Wait for export completion. Open the file and verify actual runtime and playback near the beginning, middle, and end. Do not trust the editor timeline length alone.
3. Prepare a clear title, description, and chapter list using natural phrases tied to how viewers use the music. Do not claim instruments, moods, or durations the audio does not contain.
4. Include album and track credits and required attribution. Use only audio and artwork cleared for the channel.
5. Upload and schedule only after the user approves title, description, thumbnail, audience setting, visibility, and schedule. For a UK audience, calculate UK local time and confirm the date and time shown in YouTube before scheduling.
6. Verify the scheduled item in YouTube Studio.

## 8. Save and resume checklist

Before pausing or finishing a session, update the manifest with current state and exact next action. Confirm:

- Album source tracks and final mix filenames are recorded.
- Tracklist and timestamps add up to measured mix duration.
- Approved image and accepted motion clip are identified.
- Video Express and Canva designs are saved.
- Audio, image or motion, and waveform reach the intended timeline end.
- Export was opened and its duration checked.
- Captions or chapters use verified titles and timings; no fabricated speech captions remain.
- Any requested upload or schedule has the correct title, audience, and time.

If a session resumes with a project already open, inspect the current project and manifest first. Reuse completed audio and image assets. Do not repeat generations or rebuild a timeline unless inspection shows the existing work is missing or unusable.

## First-album notes and lessons

- Channel: Omazmusic.
- Approved visual direction: bright room; young man wearing headphones and reading; channel banner colors; small waveform near the bottom.
- The target was about 90 minutes. Canva showed `1:30:07` and used one combined mix. A prior source-duration calculation suggested the final track was cut off, so verify true sequence and track boundaries against the rendered mix before creating captions or chapters.
- Canva auto-captions produced false lyrics on instrumental music. They were removed; Canva then showed **All changes saved**.
- Video Express generated a 5-second image-to-video clip from the reader image. Generation completed and the clip appeared in Media Library. The 90-minute timeline was not replaced by that clip; looping or replacing the visual across the full album still needs a deliberate plan and playback check.
- Save before leaving either editor. Make timeline edits gently, add or replace one asset at a time, and inspect after each change.
## 9. Research, title, description, and schedule for Omazmusic
1. Before preparing each upload, search YouTube for current, successful channels and recent videos in the same listening niche. Include relevant examples such as Guitar Memories and Grandson Memories when they fit the album. Record the channel/video link, upload date, visible views, title wording, description structure, video length, thumbnail style, and any track/chapter information. Treat public view counts as a snapshot, not proof that one title caused the views.
2. Compare several relevant uploads. Look for repeated listener use cases and plain search phrases, such as relaxing after work, reading, studying, winding down, or listening on the way home. Note what recurs across examples, then write an original title that clearly matches this album and sounds natural when spoken. Do not copy another channel's exact title, branding, description, or artwork.
3. Draft a useful description in ordinary language. State what the listener will hear and when it may suit them, give the real runtime, include verified track names and chapters when timing is confirmed, and credit Omazmusic and any required collaborators or sources. Do not claim sleep, study, instruments, lyrics, or benefits unless the audio supports the claim. Use only a few relevant search phrases naturally; do not stuff keywords.
4. Prepare the final title, description, thumbnail, audience setting, visibility, and upload file for the Omazmusic YouTube channel. Review the final video and metadata together before upload.
5. Set the planned publication for 48 hours after the upload is ready. Convert the intended date and time to UK local time (Europe/London), accounting for GMT/BST on that date, and check the exact time displayed by YouTube Studio before confirming. Keep a record of the scheduled date, UK time, and YouTube Studio status. If the user has not approved the final package and time, prepare the upload but do not confirm the schedule.
6. After scheduling, reopen YouTube Studio and verify the video appears with the correct title, visibility, date, and UK time. Record the video link and scheduled details in the project manifest.


## 10. Keep the recurring character, vary each album scene

- Use the same recognizable young man from the approved channel artwork for every album. Preserve his face, age, hair, headphones, and overall identity. When creating a new image, use the approved image as the visual reference if available; do not invent a different lead character.
- Change his posture, activity, and environment for each album so each cover feels new while the channel still feels consistent. Keep the banner palette and bright, welcoming tone.
- For the next album, show the same man playing a guitar in a relaxed seated posture. Choose a distinct, inviting setting that fits the music, such as a sunlit living room or bright conservatory. Keep the guitar clearly visible and leave space near the bottom for the waveform.
- Before animating, check that the pose and hands suit the activity. Use subtle motion that fits the scene, such as gentle guitar picking, small finger movement, and natural breathing, with a mostly fixed camera. Review a proof clip for hand and instrument distortions before building the long video.


## 11. Current default: Canva-first album production

Canva is the main project for assembling, saving, and exporting each Omazmusic album. Keep each album in its own Canva design. Use the existing design tab when it is the intended project; do not open duplicate tabs for the same design.

1. Create or duplicate a 1920 × 1080 landscape design for the new album. Keep the same recognizable young man from the approved channel artwork, including his face and headphones, while changing his posture, activity, and setting to fit the album. Use the channel banner colors and a bright, welcoming scene.
2. Upload only this album’s artwork and original tracks to Canva. Add files one at a time and save after meaningful edits so the editor stays responsive.
3. Place the tracks in order on one continuous audio lane, beginning at zero. Use only the album’s tracks or its final mix, never both. If the source sequence is shorter than 90 minutes, repeat the full sequence and trim only the final repeat to the measured target. Verify the timeline end against the audio end.
4. Loop or extend the artwork and waveform to the full audio duration. Keep the waveform near the bottom and directly above the image lane. Use Canva’s available animation for gentle motion. If a separate short motion clip is specifically needed, import it into Canva and check that the visual covers the full timeline. Canva remains the saved project and final export location.
5. Use Canva’s Captions app only when the audio contains speech or sung lyrics. Check captions against the audio. Do not use speech captions for instrumental music; the first album’s auto-caption pass invented lyrics.
6. Save often. Preview the start, a middle point, and the end. Confirm the audio, artwork, and waveform all reach the same final time and check for gaps or abrupt loops.
7. Export from Canva as a 1920 × 1080 MP4. Open the export and verify its actual duration and playback near the beginning, middle, and end. Do not rely on the timeline display alone.
8. Prepare the Omazmusic title, description, and chapters from verified audio content and timing. Schedule for 48 hours after the upload is ready, using Europe/London local time. Upload and confirm scheduling only after the user approves the final package and displayed publication time.

Use the earlier Video Express motion instructions only when a separate motion asset is needed for import into Canva. Do not assemble or export the album in Video Express.
