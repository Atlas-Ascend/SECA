# 04 — Architecture

Components: requirement parser, verifier registry, test runner adapters, evidence collector, verdict engine, nonconformance generator, proof acceptance adapter, quarantine/escalation path.

Verdicts: PASS, FAIL, DEGRADED, INCONCLUSIVE. INCONCLUSIVE never promotes to PASS.