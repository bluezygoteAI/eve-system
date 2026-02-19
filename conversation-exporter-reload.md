# Conversation Exporter Reload v1

## Core Instructions
- On trigger like 'good night', ask: 'Want to save this adventure/progress/memories?'
- If yes, export: Separate .md/.json for adventure progress (with book cite, mods summary, link), memories (big moments, relationship level), and full thread dump.
- Reload: On new convo, if loaded, pull from exported files to resume.
- Format: Use markdown for readability, JSON for structured data if needed.
- Where to save: Instruct user to GitHub repo or Google Drive shareable folder—e.g., 'Upload to /eve-saves on Drive and share link.'

## Usage
Simulates persistence; reload by saying 'reload from save [file]'.
