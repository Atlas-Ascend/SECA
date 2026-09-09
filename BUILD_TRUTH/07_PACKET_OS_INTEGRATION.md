# 07 — Packet OS Integration

Packets enter VERIFY only with declared acceptance criteria and proof class. SECA returns verdicts linked to packet_id. FAIL/DEGRADED creates or requests remediation work rather than silently altering the original packet.

PROVED/CLOSED transitions require the appropriate accepted verdict/proof path.