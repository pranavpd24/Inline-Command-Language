# ICL Grammar — v1.0

COMMAND        := [A-Z_]+
MODE           := [a-z]+
TARGET         := relative-path
PAYLOAD        := any UTF-8 text

LINE           := COMMAND ":::" MODE ":::" TARGET "|||" PAYLOAD

Delimiter rules:
- ":::" separates command components
- "|||" separates metadata from payload
- Delimiters MUST NOT be overloaded or nested
