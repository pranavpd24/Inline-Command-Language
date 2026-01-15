# ICL Specification — Version 1.0

This document defines the normative behavior of Inline Command Language (ICL).

## 1. Output Constraints
- Plain text only
- One command per line
- No explanations or comments
- No markdown or formatting

## 2. Command Structure

COMMAND:::MODE:::TARGET|||PAYLOAD

Where:
- COMMAND is an uppercase identifier
- MODE defines intent
- TARGET is a relative path or identifier
- PAYLOAD is raw, uninterpreted text

## 3. Execution Model
- Commands are executed sequentially
- Execution is host-controlled
- User approval is required before execution
