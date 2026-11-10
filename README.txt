Yoga Class Planner V8 — GitHub Pages

Upload index.html, sw.js, manifest.webmanifest and icon.svg to the root of your existing GitHub Pages repository, replacing V7 files.

IMPORTANT: Export a JSON backup from the existing app before updating. The main app continues to use localStorage key yoga-planner-v1 and retains your existing saved classes and exercise edits. The old recovery snapshot key is retained.

NEW:
- English and available Sanskrit pose names in the exercise library, class planner, teaching screen and printed plans. Names are only populated when known; descriptive chair variations may not have an established Sanskrit name. Existing user-entered Sanskrit names take priority.
- Larger timer in portrait and landscape, with responsive layout. Rotate your device with Auto-rotate enabled. Browser orientation locking is not required.
- Client mini app: choose Saved Classes > Client mini app or Class Planner > Export client mini app. Android may show a Share sheet, otherwise a standalone .html file downloads. Send the HTML file to your client. They can open it in a browser; it works without the instructor's account or internet once downloaded. Includes exercise names, Sanskrit where available, instructions, next exercise, countdown, previous/next, pause and reset.

PRIVACY: Client mini app contains the selected class only, not your entire exercise database, other clients, or calendar. Review class safety and instructions before sharing. HTML attachments can be blocked by some messaging services; use a file-sharing service if needed. Opening local HTML files can vary by Android browser.

NOTE: Timer pauses when the page is backgrounded, to avoid skipping exercises unexpectedly. Sun Salutations appear as one timed block with an expandable breakdown. Client mini apps are standalone files, not separate installable PWAs.

V9 FIXES: All built-in and custom Sun Salutations can be manually added to any class style, without disabling choices or compatibility errors. New classes default to Hatha Yoga (including Start fresh). Automatic class generation continues to suggest compatible sequences. Existing saved data uses the unchanged yoga-planner-v1 storage key.

V10: Client Companion class list, video searches, individually timed sun salutation movements, local music playback, bell and voice announcements.

V11: Client Companion supports multiple audio files, folder/album selection where supported, sequential playlist playback, track selection and next/previous controls. Voice announces the upcoming exercise at 3 seconds remaining; bell at transition.
