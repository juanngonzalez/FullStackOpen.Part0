´´´mermaid
sequenceDiagram
  Browser->>Server: new_note POST {note: "string"}
  Server->>Browser: notes GET
  Server->>Browser: main.css GET
  Server->>Browser: main.js GET
  Server->>Browser: data.json GET
´´´



