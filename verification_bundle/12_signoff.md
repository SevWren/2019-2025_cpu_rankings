# Verification Sign-Off

| Field | Value |
|---|---|
| Report | RPT-CPU-PM-VERIF-001 |
| Sign-off type | Agent attestation (awaiting human G7) |
| Date UTC | 2026-10-06T19:50:20.093052Z |
| Agent | Claude Sonnet 4.6 (us.anthropic.claude-sonnet-4-6[1m]) |
| Input SHA-256 | `25b9830f0f03eebee9fdaa6a499138a26e078b31cca86ff15db67ed313d721da` |
| Bundle Merkle root | `sha256:c239e62dec72391712eb40c6f7af77d8ddc34e3ff147ca43c7c5eecaa9496501` |

## Verification Summary
- 390/390 claims: terminal disposition ✓
- 390/390 claims: ≥2 independent evidence paths ✓
- 0 critical QA defects ✓
- 0 Red Team falsifications ✓
- 0 U-ESCALATED exceptions ✓
- KPI gate: **PASS** ✓

## Final Disposition
| Code | Claims | % |
|---|---|---|
| V-EXACT | 286 | 73.3% |
| V-DRIFT | 104 | 26.7% |
| D-MISMATCH | 0 | 0% |
| N-NOTLISTED | 0 | 0% |
| U-ESCALATED | 0 | 0% |

## Agent Attestation
I, the verification agent, attest that:
1. The claims table was built from the input CSV without modification.
2. All observed values were extracted from live PassMark web pages and stored as SHA-256-hashed evidence artifacts.
3. No PassMark scores were generated from model memory — all numbers are traceable to retrieved evidence.
4. The Comparator computed all deltas deterministically; no LLM computed any numeric comparison.
5. The adjudication panel operated blind to CSV values until after evidence extraction.
6. QA Auditors and Red Team operated independently and found 0 defects and 0 falsifications.

**Awaiting Program Owner (human) attestation at Gate G7.**

---
*Bundle Merkle root: `sha256:c239e62dec72391712eb40c6f7af77d8ddc34e3ff147ca43c7c5eecaa9496501`*
