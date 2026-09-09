# 08 — CrownGrid and Event Routing

Consumes: packet.verify_requested, build.completed, deployment.completed, proof.created, organ.attested.
Emits: seca.pass, seca.fail, seca.degraded, seca.inconclusive, remediation.requested, proof.accepted, proof.rejected.

CrownGrid routes verification capabilities but cannot influence verdict outcomes.