# WRITE_FILE Command — v1.0

Purpose:
Request deterministic file creation or modification.

Syntax:
WRITE_FILE:::<mode>:::<path>|||<content>

Modes:
- write      → create new file, fail if exists
- overwrite  → replace entire file content
- append     → append content to file

Rules:
- Paths MUST be relative
- No directory traversal allowed
- overwrite and append MUST require explicit user approval
- Content is not interpreted by the shell
