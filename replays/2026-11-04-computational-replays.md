# MathWise fixed-case computational replays — November 4, 2026

Four local replay records were made at approximately 1:53, 2:53, 3:55, and 4:54 a.m. Eastern Time using repository commit `a3247616fe3d645466d772576fba035998e698ea` and a recovered standalone verifier whose SHA-256 matches the historical manifest:

`80de885335bb07f3b1991c19543da14c1f125873788a9d6fcf039a45741d7882`

Each record contains two verifier runs. Both runs in each record passed the 14 implemented checks: finite-interval coverage, initial and total candidate counts, elimination tables, remaining survivor counts, and shadow checks. Each reported 1,361,889 Case A, 255,938 Case B, and 1,501,666 Case C candidate systems, with zero survivors in each case. These are candidate systems, not individual test cases. Two negative controls in each record detected their intended faults.

The separate recovered audit reported **CONDITIONAL PASS**; its compatibility check relies on recorded checkpoint statuses. The verifier's computational replay and the conditional audit are distinct from an independent mathematical proof review. The fixed-case scope is D = {3, 4, 7}, k = 1.

**Scope:** Two fresh processes on the same host replayed the fixed-case MathWise computation. The verifier checks the finite interval and recorded modular eliminations. Verifier outputs differed in elapsed time. Raw logs for these runs are retained separately.
