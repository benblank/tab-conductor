## Name ideas

- Tabber ("Tabbr" already exists)
- Tabby

## Feature ideas

- output
  - save to file
    - HTML (titles optional?)
    - Markdown (titles optional?)
    - plain text (indentation? titles?)
    - CSV
    - TSV
    - QR code? (is there a standard for multiple URLs in a single code?)
    - app-specific formats?
      - Google Docs
      - Google Sheets
      - MS Word
      - MS Excel
      - Notion
      - Evernote
      - …
  - copy to clipboard
    - (all formats for saving to file)
    - "rich" clipboard support?
  - "share"?
  - email?
  - method to select which tabs to save
    - retaining structure is optional?
    - allow editing structure/contents before save?
      - arbitrary depth?
  - tab icons!
- input
  - read from file/clipboard
    - dedicated support for export formats?
    - "just find every URL" (best-effort titles? structure?)
      - balanced parentheses (optional?)
      - no trailing "punctuation" (esp. period; optional?)
  - method to select which tabs to load
    - retaining structure is optional?
  - loading structure containing groups into browser which doesn't support them
    - option to ignore grouping or convert to windows
    - allow editing structure/contents before restore?
      - how to handle loading of structure with more depth than browser
        supports?
- structure
  - fixed depth?
    1. windows, if any (window names? "window 1", "window 2"?)
    2. groups, if any (how are group names/colors handled?)
    3. tabs
  - arbitrary depth?
  - if structure editor, edit open windows/groups/tabs without import/export?
    - automatic grouping by domain? (probably not)
- somehow track when tab URL last changed?
- crash protection?
  - listen for tab opening and closing, keep an "export" structure in extension
    settings?
    - automatic backup?
      - Dropbox/GDrive/OneWhatever/Sync support?
      - automatic restore? under what conditions?
- allow comments when saving, display when opening structured format?
  - do comments get "saved" between one export and the next?
    - attached to URL?
    - attached to tab object in memory?
      - how to handle browser restart?
- optional keybinding(s)
  - customizable "default" export settings, with dedicated keybinding?
- does Google Chrome (or others) have a way of saving extension options in a
  way that causes them to be synched between devices?
