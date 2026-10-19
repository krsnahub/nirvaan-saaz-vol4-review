# Ruh — temporary take review

Phone-friendly listening interface for Nirvaan Saaz, Volume 4 — Ruh. The page reads `album.json` at runtime and renders every listed song and take. No cover artwork is available yet, so the page displays a labelled placeholder.

Choices, requests for new takes, and notes are provisional. They save only in the reviewer's browser on that device. The reviewer must copy or share the review URL back in chat, or download and attach the review JSON in chat. The URL fragment carries the decisions and notes; there is no automatic server sync. The review file includes selected take IDs and source WAV and lyric hashes supplied by `album.json`. Neither option selects a studio master or deletes a recording.

This temporary link and its hosted MP3s are publicly accessible to anyone who has the link. After feedback is backed up locally and the review is complete, remove the temporary page and hosted audio. Preserve pending reviews, local masters, canonical deliverables, permanent backups, and feedback archives. Removing access cannot recall downloaded copies.

The source page needs `index.html`, `style.css`, `app.js`, and a generated `album.json`. The referenced `audio/` MP3 files must be present at their relative paths. Deployment and media packaging are handled separately.
