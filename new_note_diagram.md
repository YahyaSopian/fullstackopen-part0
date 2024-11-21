```mermaid
sequenceDiagram
participant browser
participant server
browser->>server: POST /notes
server-->>browser: Response
