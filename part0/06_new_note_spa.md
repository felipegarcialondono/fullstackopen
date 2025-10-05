```mermaid
sequenceDiagram
  participant browser
  participant server

  Note right of browser: The browser adds the note to the list of loaded notes and re-renders them.

  browser->>server: POST https://studies.cs.helsinki.fi/exampleapp/new_note_spa
  activate server
```