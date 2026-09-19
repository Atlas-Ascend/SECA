# ARK Ω Runtime Binding v1.1.0 — SECA

Role: canonical verification gate.

Consume execution receipts preserving command_id, mission_id and packet_id. Validate declared outcome against artifacts, logs, policy and expected acceptance criteria.

Required transition: EXECUTING -> VERIFYING.

Emit seca_receipt with verdict PASS|FAIL|WITHHELD, checks[], evidence_refs[], verifier_version, timestamp and correlation ids.

FAIL or WITHHELD blocks DEVOS promotion and must surface unchanged to ARK Ω. No visual state may render SEALED from SECA alone.
