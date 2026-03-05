# Developer Log (DEVLOG.md)
## Monopoly Board Simulator (Spring 2026)
Minimum **6 entries** required.
Each entry must document learning and reasoning. Fabricated bugs are not expected.
---
## Allowed Entry Types
Each entry may be one of the following:
1) **Bug Fix Entry**
- The issue encountered.
- Error messages or symptoms.
- Attempts made.
- Final resolution.
2) **Edge Case / Testing Entry**
- A failure discovered through testing.
- The specific input/state that caused it.
- The change you made to handle it correctly.
3) **Engineering Decision Entry (up to 2 allowed)**
- A design decision you made.
- An alternative approach you considered.
- Why you chose one approach over another (tradeoffs).
---
### Entry 1
**Date:2026-03-03
**Entry Type: Engineering Decision
**Task worked on: movePlayer(int steps)
**Issue or decision: Possibility of redundant looping
**Error message / symptom (if applicable): N/A
**What I tried: Modulus Operator
**Fix / resolution (or final decision): Use modulu operator within a new variable to lessen the extent of the for loop.
**Commit(s): Made movePlayer() method better/more efficient by reducing redundant traversal (when doing full 360).
---
### Entry 2
**Date:2026-03-05
**Entry Type: Bug Fix 
**Task worked on: isEqual(MonopolySpace other)
**Issue or decision:(MonopolySpace other) would copy the entire thing
**Error message / symptom (if applicable): unnecessary copying
**What I tried: pass parameter as const and add &
**Fix / resolution (or final decision): other is now unmodifiable and easier to compare
**Commit(s): Improved isEqual(MonopolySpace other) by making the parameter unmodifiable and const. Also updated DEVLOG entries 1 & 2.
---
### Entry 3
**Date:** YYYY-MM-DD
**Entry Type:** Bug Fix / Edge Case / Engineering Decision
**Task worked on:**
**Issue or decision:**
**Error message / symptom (if applicable):**
**What I tried:**
**Fix / resolution (or final decision):**
**Commit(s):**
---
### Entry 4
**Date:** YYYY-MM-DD
**Entry Type:** Bug Fix / Edge Case / Engineering Decision
**Task worked on:**
**Issue or decision:**
**Error message / symptom (if applicable):**
**What I tried:**
**Fix / resolution (or final decision):**
**Commit(s):**
---
### Entry 5
**Date:** YYYY-MM-DD
**Entry Type:** Bug Fix / Edge Case / Engineering Decision
**Task worked on:**
**Issue or decision:**
**Error message / symptom (if applicable):**
**What I tried:**
**Fix / resolution (or final decision):**
**Commit(s):**
---
### Entry 6
**Date:** YYYY-MM-DD
**Entry Type:** Bug Fix / Edge Case / Engineering Decision
**Task worked on:**
**Issue or decision:**
**Error message / symptom (if applicable):**
**What I tried:**
**Fix / resolution (or final decision):**
**Commit(s):**