# Sentinel's Security Journal

This journal tracks critical security learnings and decisions.

## 2026-02-13 - Initial Setup
**Vulnerability:** Missing `.gitignore` file.
**Learning:** Repositories without `.gitignore` risk accidental commitment of sensitive files (secrets, logs, dependencies) and clutter.
**Prevention:** Added a comprehensive `.gitignore` covering common sensitive files, logs, dependencies, and build artifacts.
