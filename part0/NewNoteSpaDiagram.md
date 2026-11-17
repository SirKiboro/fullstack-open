```mermaid
sequenceDiagram
    participant browser
    participant server

    Note over browser,server: POST request sends new note as: <br>{content: "Note on the single page app", date: "2026-11-17T07:20:48.391Z"}

    browser->>server: POST https://studies.cs.helsinki.fi/exampleapp/new_note_spa
    server-->>browser: {message: "note created"}

```    