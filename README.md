# Supriya S P & Robin R — Cinematic Wedding Invitation

Open `index.html` in a browser or deploy the folder to any static host.

## Editable settings
Edit the `CONFIG` object near the bottom of `index.html`:
- bride / groom
- date/time
- venue
- maps
- music

Replace/add files inside `assets/` and update image paths in the HTML.

## Music
Browsers generally block autoplay. The music button starts playback after a user tap. Put your MP3 in `assets/` and set:
`music:"assets/wedding-music.mp3"`

## Exact map
The current button uses a Google Maps search URL for "Jayamahesh Auditorium". Replace `maps` with the exact Google Maps place URL when available.

## Note about retrieved assets
The available wedding-specific assets in the user's Library included the SR invitation artwork and ceremony-stage imagery. No bride/groom portrait or wedding-music file was found in the retrieved Library results, so those are intentionally left as editable slots rather than incorrectly presenting unrelated photos as the couple.


## RSVP / Attendance
The site now has an RSVP section. Create a Google Form with Name, Attendance (Yes/No), Number of people attending, phone (optional), and wishes (optional). Link the form responses to Google Sheets, then paste the form URL into CONFIG.rsvp in index.html. Google Forms provides response summaries and a linked spreadsheet.
