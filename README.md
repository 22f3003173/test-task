# Brief Builder - Test Brief

## Overview
Brief Builder is a lightweight, single-file web app to draft, preview, and export concise project briefs. It includes:
- Live Markdown preview of your brief
- Autosave to localStorage
- Light/Dark theme toggle
- Export/Import JSON
- Shareable link via URL hash
- Copy/Download Markdown

The app is self-contained (no external dependencies) and is ideal for quickly organizing and sharing a “test brief” or similar planning documents.

## Setup
- No installation required.
- Open index.html in any modern browser.

Optional:
- To persist theme and content, allow localStorage in your browser.

## Usage
1. Fill in the form on the left:
   - Project name
   - Round (1 or 2)
   - Overview
   - Goals, Features, Constraints, Metrics (one per line)
   - Notes/Risks, Attachments
   - Round 2 improvements (if applicable)
   - Checklist style and file slug
2. The README preview on the right updates live.
3. Actions:
   - Copy Markdown: Copies the generated README to your clipboard.
   - Download: Downloads a .md file using the provided slug.
   - Share link: Creates a URL with your brief embedded in the hash, and copies it.
   - Export JSON: Saves a .json snapshot of your brief.
   - Import JSON: Restores a saved .json snapshot.
   - Reset: Restores the default template.
4. Keyboard shortcuts:
   - Ctrl/Cmd+S: Save to localStorage
   - Ctrl/Cmd+B: Copy Markdown
5. Toggle Raw MD to switch between rendered and raw Markdown preview.

Notes:
- The app autosaves edits and restores them on reload.
- The shareable link stores your brief in the URL hash only; nothing is uploaded.

## If Round 2
- Set the Round field to 2 and list changes in “Round 2 improvements.” The README will include a dedicated section describing the improvements.