# MONARK precommitments

Public SHA-256 fingerprints of MONARK research documents. Each one is recorded before the data the document governs is seen.

The documents stay private. A fingerprint shows that a document existed at the time of record and has not changed since:
changing a single character changes the fingerprint.

## What is here

- `PRECOMMITMENTS.md`: one row per recorded file, with the document it belongs to and its SHA-256 (64 hexadecimal characters).

Nothing else is stored here: no data, no code, no results.

## Time of record

The time of record is when GitHub received the push that added the row, as listed in this repository's activity log.
A commit's own date is set by its author, so it is not the reference.

## Checking a fingerprint

When a document is published later, anyone can recompute its fingerprint and compare it with the row:

```
sha256sum <file>
```
